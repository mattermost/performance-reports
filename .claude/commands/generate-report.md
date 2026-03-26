Generate a performance comparison report README for version $ARGUMENTS.

## Instructions

### 0. Normalize version argument

The user may pass either `11.5` or `v11.5`. Normalize to always use the `v` prefix:
- If `$ARGUMENTS` already starts with `v`, use it as-is (e.g. `v11.5` → `v11.5`).
- If `$ARGUMENTS` does not start with `v`, prepend it (e.g. `11.5` → `v11.5`).

Use the normalized version (referred to as `$VERSION` below) for all directory paths and file references throughout this skill. For example, the report path is `performance-comparisons/$VERSION/README.md`.

Create a `README.md` file at `performance-comparisons/$VERSION/README.md` by following these steps:

### 1. Research Mattermost code changes between versions (run in background)

Use a subagent **in the background** to research what changed in the Mattermost server between the base and new versions. This runs in parallel with steps 2 and 3 — its output is only needed in step 4.

Read `performance-comparisons/$VERSION/config/comparison.json` first to get the version labels (fields `BaseBuild.Label` and `NewBuild.Label`, e.g. `release-11.4.0` and `release-11.5.0-rc2`), then launch the subagent.

The subagent must use the `gh` CLI (via the Bash tool) to gather **actual code changes** from the `mattermost/mattermost` repository — do NOT rely on release notes, changelogs, or blog posts. Specifically, the subagent should:

**HARD CONSTRAINT**: You must complete this task in **5 or fewer Bash tool calls** total. Do not iterate through individual commits. Do not fetch patches for individual files. The two API calls below give you everything you need.

0. **Convert labels to git tags**: The `BaseBuild.Label` and `NewBuild.Label` values use the format `release-X.Y.Z` (e.g. `release-11.4.0`), but the actual git tags in the `mattermost/mattermost` repository use the format `vX.Y.Z` (e.g. `v11.4.0`). Before making any API calls, strip the `release-` prefix and prepend `v` to get the correct tag names. Use these converted tags (referred to as `{BaseTag}` and `{NewTag}` below) in all `gh api` commands.
1. **Get commit list and stats** (1 Bash call, 1 API request): Run `gh api repos/mattermost/mattermost/compare/{BaseTag}...{NewTag} --jq '{total_commits: .total_commits, files_changed: (.files | length), additions: ([.files[].additions] | add), deletions: ([.files[].deletions] | add), commits: [.commits[] | {sha: .sha[0:8], message: (.commit.message | split("\n") | .[0])}]}'` to get the high-level summary and commit list. Note: the JSON compare endpoint returns at most 300 files and 250 commits — the commit list is usually complete, but the file list may be truncated. That's fine; step 2 gets the full file list.
2. **Get full diff, extract file list and migrations** (1 Bash call, 1 API request): The JSON compare API truncates at 300 files, which misses store/, jobs/, model/, and migration SQL files. Instead, request the raw diff using the `Accept: application/vnd.github.diff` header and process it locally. Run this single command:
    ```
    gh api repos/mattermost/mattermost/compare/{BaseTag}...{NewTag} -H "Accept: application/vnd.github.diff" > /tmp/mm-compare.diff && echo "=== PERFORMANCE-SENSITIVE FILES ===" && grep "^diff --git" /tmp/mm-compare.diff | sed 's|diff --git a/\(.*\) b/.*|\1|' | grep -E "(store/|sqlstore/|api4/|app/|migrations/|model/|jobs/|web/|wsapi/)" && echo "=== MIGRATION SQL (up only) ===" && awk '/^diff --git.*migrations\/postgres\/.*\.up\.sql/{found=1} found{print} /^diff --git/ && found && !/migrations\/postgres\/.*\.up\.sql/{found=0}' /tmp/mm-compare.diff
    ```
    This downloads the diff once and extracts: (a) the list of all changed files in performance-sensitive paths (no 300-file limit), and (b) the full content of all `.up.sql` migration files.

From this data, the subagent should produce a summary of:
- Key changes: new features, significant refactors, database migrations, new background jobs, changes to store layer or API handlers.
- Changes that could plausibly affect performance: new queries, schema changes, new periodic jobs, changes to hot paths like post creation, channel loading, websocket handling, etc.

### 2. Gather inputs

Read ALL of the following files for the target version:

- `performance-comparisons/$VERSION/config/comparison.json` — base and new build labels/URLs
- `performance-comparisons/$VERSION/config/config.json` — user controller and user configuration
- `performance-comparisons/$VERSION/config/coordinator.json` — MaxActiveUsers for unbounded test
- `performance-comparisons/$VERSION/config/deployer.json` — infrastructure details (instance types/counts, load-test version, DB settings)
- `performance-comparisons/$VERSION/results/results.txt` — supported users, error counts, test types
- `performance-comparisons/$VERSION/results/report_0_postgresql_bounded_*.md` — bounded test detailed metrics
- `performance-comparisons/$VERSION/results/report_1_postgresql_unbounded.md` — unbounded test detailed metrics

Also list the graph files in `performance-comparisons/$VERSION/graphs/` to confirm what's available.

### 3. Extract key data

From the files gathered above, extract:

- **Version labels**: base version and new RC version (from `comparison.json` fields `BaseBuild.Label` and `NewBuild.Label`). Strip the `release-` prefix to get clean version numbers (e.g. `release-11.4.0` becomes `v11.4.0`).
- **Load-test version**: from the `LoadTestDownloadURL` in `deployer.json` (parse the version string from the URL, e.g. `v1.32.0-rc2`)
- **Dataset URL**: from `comparison.json` `LoadTests[].DBDumpURL`
- **Bounded test config**: `NumUsers` and `Duration` from `comparison.json` `LoadTests[]` entry with `"Type": "bounded"`
- **Unbounded test config**: `MaxActiveUsers` from `coordinator.json` `ClusterConfig.MaxActiveUsers`, num users per agent from `config.json` `UsersConfiguration.MaxActiveUsers`
- **Infrastructure**: from `deployer.json`:
  - `AppInstanceCount` x `AppInstanceType`
  - `AgentInstanceCount` x `AgentInstanceType`
  - `ProxyInstanceCount` x `ProxyInstanceType`
  - `TerraformDBSettings.InstanceCount` x `TerraformDBSettings.InstanceType`
- **Supported users**: base and actual values from `results.txt` (look for `Supported Users:` lines), calculate delta percentage as `(actual - base) / base * 100`, rounded to 2 decimal places
- **Error counts**: from `results.txt` `Errors:` lines for both bounded and unbounded tests

### 4. Analyze the detailed reports

Scan the bounded and unbounded report markdown files for:

- **Large regressions**: any metric with Delta % > 100% that isn't a rarely-called operation. Consider absolute times too — a 200% increase from 2ms to 6ms is noise, but 100ms to 300ms is significant.
- **Large improvements**: any notable improvements worth highlighting
- **API-level regressions**: check the "API times avg/p99 (worsened)" sections specifically since these are user-facing
- **Overall pattern**: determine if this is a nominal comparison or if there are systemic issues (many operations regressing in the same direction suggests a real problem vs. a few outliers)
- **Root-cause correlation**: if any significant regressions are found, cross-reference them with the Mattermost changes summary from step 1. Try to identify which specific change (new feature, migration, refactor) could explain the regression. Include this correlation in the report comments when there is a plausible match.

#### Interpretation guidelines

- **Supported users delta is the most important metric.** An absolute change larger than 5% in supported users from the unbounded test is the single most significant signal. If this happens, the release must be held pending investigation — this is not optional.
- **Bounded graph spikes are often noise.** The bounded test graphs show occasional spikes that do not indicate real regressions. Before flagging a spike, check graphs from previous versions to see if similar spikes appeared there too. Only flag a spike if it is clearly new and sustained, not a one-off.
- **Heap and stack graphs typically show large differences.** This is a known phenomenon with an unknown root cause. Differences in heap-in-use and stack-in-use between base and actual are expected and should NOT be flagged as regressions in the report.

### 5. Write the report

Generate the README using the template below. Replace all `{PLACEHOLDER}` values with the extracted data.

#### Comment style guidance

The comment style should be factual and concise. Use the following patterns based on what the data shows:

- **Nominal results (supported users delta within [-5%, +5%])**: Describe as "no significant difference", state the delta and that it falls within the expected interval.
- **Positive results (improvement > 2%)**: Note the improvement but still frame it within the expected variance unless it exceeds +5%.
- **Regression in supported users > 5%**: This is critical. The action item MUST state that the release should be held pending investigation. Use the Mattermost changes summary from step 1 to suggest likely causes.
- **Notable store/API regressions**: Only mention specific operations in comments if they are significant enough to warrant investigation — high absolute times (>50ms delta) or user-facing API regressions. Small percentage swings on low-latency operations (<5ms base) are noise. When flagging a regression, include any correlation with specific Mattermost code changes identified in step 1.

#### Delta formatting

- Negative deltas: use `\-` prefix (backslash-escaped for markdown), e.g. `\-2.62%`
- Positive deltas: use `+` prefix, e.g. `+4.28%`
- The `\` escape prevents markdown from rendering the `-` as a list item in some renderers.

#### Template

````markdown
# Performance Comparison `{BASE_VERSION}` vs `{NEW_VERSION}`

## Comments

- {Overall assessment as a bullet point}:
  - {Unbounded test result}: the unbounded test shows {no significant difference / a N.NN% increase/decrease} in the number of supported users{, which lies in the \[-5%, +5%\] interval of usual variance / , which exceeds the \[-5%, +5%\] expected interval}.
  - {Bounded test result}: the bounded test shows {no significant difference in any of the metrics considered / significant differences in ...}.
{- Optional: notable regressions or improvements worth calling out, with specifics (operation name, base -> actual, delta %)}

## Action Items

- {Release decision: "Release can continue as planned." or "Release should be held pending investigation of ..."}
- {Specific investigation items, or "No other action needed."}

## Setup

| Setting                              | Value                                                                                              |
| ------------------------------------ | -------------------------------------------------------------------------------------------------- |
| Load-test version                    | [`{LT_VERSION}`](https://github.com/mattermost/mattermost-load-test-ng/releases/tag/{LT_VERSION}) |
| Dataset                              | [Dump from `v6.1.0`, 12M posts]({DATASET_URL})                                                    |
| Bounded - number of users            | {BOUNDED_USERS}                                                                                    |
| Bounded - duration                   | {BOUNDED_DURATION} minutes                                                                         |
| Unbounded - MaxActiveUsers           | {MAX_ACTIVE_USERS}                                                                                 |
| Unbounded - num of users per agent   | {USERS_PER_AGENT}                                                                                  |
| App instances                        | {APP_COUNT} x {APP_TYPE}                                                                           |
| Agent instances                      | {AGENT_COUNT} x {AGENT_TYPE}                                                                       |
| Proxy Instance                       | {PROXY_COUNT} x {PROXY_TYPE}                                                                       |
| DB instances                         | {DB_COUNT} x {DB_TYPE}                                                                             |

## Results

### Grafana

These are snapshots of the original Grafana dashboards.

- [Bounded test](TBD)
- [Unbounded test](TBD)

### Supported users in unbounded test

| {BASE_VERSION} | {NEW_VERSION} | Delta   |
| -------------- | ------------- | ------- |
| {BASE_USERS}   | {ACTUAL_USERS}| {DELTA} |

### Graphs - Bounded

| ![postgresql_bounded_0_avg-api-times](graphs/postgresql_bounded_0_avg-api-times.png) | ![postgresql_bounded_0_p99-api-times](graphs/postgresql_bounded_0_p99-api-times.png) |
| --- | ---|
| ![postgresql_bounded_0_avg-store-times](graphs/postgresql_bounded_0_avg-store-times.png) | ![postgresql_bounded_0_p99-store-times](graphs/postgresql_bounded_0_p99-store-times.png) |
| ![postgresql_bounded_0_cpu-utilization](graphs/postgresql_bounded_0_cpu-utilization.png) | ![postgresql_bounded_0_goroutines-in-use](graphs/postgresql_bounded_0_goroutines-in-use.png) |
| ![postgresql_bounded_0_heap-in-use](graphs/postgresql_bounded_0_heap-in-use.png) | ![postgresql_bounded_0_number-of-connected-devices](graphs/postgresql_bounded_0_number-of-connected-devices.png) |
| ![postgresql_bounded_0_rps](graphs/postgresql_bounded_0_rps.png) | ![postgresql_bounded_0_stack-in-use](graphs/postgresql_bounded_0_stack-in-use.png) |

### Graphs - Unbounded

| ![postgresql_unbounded_0_avg-api-times](graphs/postgresql_unbounded_0_avg-api-times.png)     | ![postgresql_unbounded_0_p99-api-times](graphs/postgresql_unbounded_0_p99-api-times.png)                             |
| --- | ---|
| ![postgresql_unbounded_0_avg-store-times](graphs/postgresql_unbounded_0_avg-store-times.png) | ![postgresql_unbounded_0_p99-store-times](graphs/postgresql_unbounded_0_p99-store-times.png)                         |
| ![postgresql_unbounded_0_cpu-utilization](graphs/postgresql_unbounded_0_cpu-utilization.png) | ![postgresql_unbounded_0_goroutines-in-use](graphs/postgresql_unbounded_0_goroutines-in-use.png)                     |
| ![postgresql_unbounded_0_heap-in-use](graphs/postgresql_unbounded_0_heap-in-use.png)         | ![postgresql_unbounded_0_number-of-connected-devices](graphs/postgresql_unbounded_0_number-of-connected-devices.png) |
| ![postgresql_unbounded_0_rps](graphs/postgresql_unbounded_0_rps.png)                         | ![postgresql_unbounded_0_stack-in-use](graphs/postgresql_unbounded_0_stack-in-use.png)                               |

{OPTIONAL_FOOTNOTES}
````

#### Template notes

- **Grafana links**: Always use `TBD` — the raintank.io snapshots are created manually after the report.
- **Graph image paths**: Use relative paths (`graphs/...`). The 10 standard graph names per test type are: `avg-api-times`, `p99-api-times`, `avg-store-times`, `p99-store-times`, `cpu-utilization`, `goroutines-in-use`, `heap-in-use`, `number-of-connected-devices`, `rps`, `stack-in-use`. Only include graphs that actually exist in the `graphs/` directory.
- **Graph table layout**: Always a 2-column table. The pairs are: api-times (avg | p99), store-times (avg | p99), cpu | goroutines, heap | connected-devices, rps | stack. The separator row is `| --- | ---|`.
- **Footnotes**: Use `[^1]` markdown footnote syntax only if there's a word in the comments that benefits from a clarifying note (e.g. `boring[^1]` → `[^1]: boring is good!`). Most reports don't use footnotes.
- **Setup table alignment**: Use `| ---- |` style dashes (at least 4), left-aligned. Match the column widths from the template.
- **Multiple bounded configs**: If `comparison.json` lists multiple bounded tests (e.g. different user counts), generate graph sections for each.
