# Performance Comparison `v8.1.2` vs `v9.0.0-rc2`

## Comments

- The release can continue uninterrupted, there are no indications whatsoever of any regression.
  - Number of supported users seem to have actually increased for the new release. This comparison reports an increase of supported users of 9.09% for MySQL and of 11.97% for PostgreSQL.
  - Graphs back these numbers up: P99 API times are consistently lower for v9.0.0-RC2 than for v8.1.2 in both bounded tests.
- Meta information on the comparison:
  - The load-test tool version used is [a modified version of latest master](https://github.com/mattermost/mattermost-load-test-ng/tree/deploy-only), crafted to overcome the issues with the license bug (potentially caused by <https://mattermost.atlassian.net/browse/MM-54456>).
  - Both the base (`v8.1.2`) and the new (`v9.0.0-RC2`) builds of the server were patched with the changes from [PR #24524](https://github.com/mattermost/mattermost/pull/24524) to fix the license bug.
  - Graphs incorrectly label the new release as 9.1.0, but the tested version is 9.0.0-RC2, as shown in the `comparison.json` config file

## Next Steps

- Continue investigation on the license bug (<https://mattermost.atlassian.net/browse/MM-47877>, <https://mattermost.atlassian.net/browse/MM-54456>) to decide next steps. Potentially:
  - Polish [the `deploy-only` branch](https://github.com/mattermost/mattermost-load-test-ng/tree/deploy-only) to merge it into master
  - Merge <https://github.com/mattermost/mattermost/pull/24524> in the server

## Setup

| Setting                              | Value                                                                                                                                         |
| ------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Load-test version                    | Branch `deploy-only`, commit [85d265b](https://github.com/mattermost/mattermost-load-test-ng/commit/85d265bf77e0c2a7b953d70d097ca8e27b6c3231) |
| Dataset                              | DB dump from `v6.1.0` with 12M posts                                                                                                          |
| Bounded - number of users (Postgres) | 7500                                                                                                                                          |
| Bounded - number of users (MySQL)    | 5000                                                                                                                                          |
| Bounded - duration                   | 90 minutes                                                                                                                                    |
| Unbounded - MaxActiveUsers           | 20000                                                                                                                                         |
| Unbounded - num of users per agent   | 2000                                                                                                                                          |
| App instances                        | 2 x c5.2xlarge                                                                                                                                |
| Agent instances                      | 11 x c5.xlarge                                                                                                                                |
| Proxy Instance                       | 1 x c5.xlarge                                                                                                                                 |
| DB instances                         | 2 x db.r6g.2xlarge                                                                                                                            |

## Results

### Grafana

These are Raintank snapshots of the original Grafana dashboards:

  - [Bounded - MySQL(https://snapshots.raintank.io/dashboard/snapshot/8B7O5KyogORbwG4tKh1JqDMUT3MPDef6)
  - [Bounded - Postgres](https://snapshots.raintank.io/dashboard/snapshot/moMTdDi9ixHUU4LUNN8kRq8BUC7KuYdM)
  - [Unbounded - MySQL](https://snapshots.raintank.io/dashboard/snapshot/cbuX6CvL3JU5C2S3QAppPRQCTtk8e5km)
  - [Unbounded - Postgres](https://snapshots.raintank.io/dashboard/snapshot/EQkyvmL6gmDMFj0F3p418rIIanjFimR7)

### Number of errors

| Test               | v8.1.2 | v9.0.0-rc2 | Delta    |
| ------------------ | ------ | ---------- | -------- |
| Bounded MySQL      | 2257   | 2022       | \-10.41% |
| Bounded Postgres   | 3403   | 3517       | 3.35%    |
| Unbounded MySQL    | 205924 | 251293     | 22.03%   |
| Unbounded Postgres | 81176  | 166030     | 104.53%  |

### Supported users in unbounded tests

| Test     | v8.1.2 | v9.0.0-rc2 | Delta  |
| -------- | ------ | ---------- | ------ |
| MySQL    | 11745  | 12813      | 9.09%  |
| Postgres | 11383  | 12745      | 11.97% |

### Graphs - Bounded MySQL

| ![mysql_bounded_0_avg-api-times](graphs/mysql_bounded_0_avg-api-times.png)     | ![mysql_bounded_0_p99-api-times](graphs/mysql_bounded_0_p99-api-times.png)                             |
|--------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|
| ![mysql_bounded_0_avg-store-times](graphs/mysql_bounded_0_avg-store-times.png) | ![mysql_bounded_0_p99-store-times](graphs/mysql_bounded_0_p99-store-times.png)                         |
| ![mysql_bounded_0_cpu-utilization](graphs/mysql_bounded_0_cpu-utilization.png) | ![mysql_bounded_0_goroutines-in-use](graphs/mysql_bounded_0_goroutines-in-use.png)                     |
| ![mysql_bounded_0_heap-in-use](graphs/mysql_bounded_0_heap-in-use.png)         | ![mysql_bounded_0_number-of-connected-devices](graphs/mysql_bounded_0_number-of-connected-devices.png) |
| ![mysql_bounded_0_rps](graphs/mysql_bounded_0_rps.png)                         | ![mysql_bounded_0_stack-in-use](graphs/mysql_bounded_0_stack-in-use.png)                               |

### Graphs - Bounded Postgres

| ![postgresql_bounded_0_avg-api-times](graphs/postgresql_bounded_0_avg-api-times.png)     | ![postgresql_bounded_0_p99-api-times](graphs/postgresql_bounded_0_p99-api-times.png)                             |
|------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
| ![postgresql_bounded_0_avg-store-times](graphs/postgresql_bounded_0_avg-store-times.png) | ![postgresql_bounded_0_p99-store-times](graphs/postgresql_bounded_0_p99-store-times.png)                         |
| ![postgresql_bounded_0_cpu-utilization](graphs/postgresql_bounded_0_cpu-utilization.png) | ![postgresql_bounded_0_goroutines-in-use](graphs/postgresql_bounded_0_goroutines-in-use.png)                     |
| ![postgresql_bounded_0_heap-in-use](graphs/postgresql_bounded_0_heap-in-use.png)         | ![postgresql_bounded_0_number-of-connected-devices](graphs/postgresql_bounded_0_number-of-connected-devices.png) |
| ![postgresql_bounded_0_rps](graphs/postgresql_bounded_0_rps.png)                         | ![postgresql_bounded_0_stack-in-use](graphs/postgresql_bounded_0_stack-in-use.png)                               |

### Graphs - Unbounded MySQL
    
| ![mysql_unbounded_0_avg-api-times](graphs/mysql_unbounded_0_avg-api-times.png)     | ![mysql_unbounded_0_p99-api-times](graphs/mysql_unbounded_0_p99-api-times.png)                             |
|------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| ![mysql_unbounded_0_avg-store-times](graphs/mysql_unbounded_0_avg-store-times.png) | ![mysql_unbounded_0_p99-store-times](graphs/mysql_unbounded_0_p99-store-times.png)                         |
| ![mysql_unbounded_0_cpu-utilization](graphs/mysql_unbounded_0_cpu-utilization.png) | ![mysql_unbounded_0_goroutines-in-use](graphs/mysql_unbounded_0_goroutines-in-use.png)                     |
| ![mysql_unbounded_0_heap-in-use](graphs/mysql_unbounded_0_heap-in-use.png)         | ![mysql_unbounded_0_number-of-connected-devices](graphs/mysql_unbounded_0_number-of-connected-devices.png) |
| ![mysql_unbounded_0_rps](graphs/mysql_unbounded_0_rps.png)                         | ![mysql_unbounded_0_stack-in-use](graphs/mysql_unbounded_0_stack-in-use.png)                               |

### Graphs - Unbounded Postgres

| ![postgresql_unbounded_0_avg-api-times](graphs/postgresql_unbounded_0_avg-api-times.png)     | ![postgresql_unbounded_0_p99-api-times](graphs/postgresql_unbounded_0_p99-api-times.png)                             |
|----------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| ![postgresql_unbounded_0_avg-store-times](graphs/postgresql_unbounded_0_avg-store-times.png) | ![postgresql_unbounded_0_p99-store-times](graphs/postgresql_unbounded_0_p99-store-times.png)                         |
| ![postgresql_unbounded_0_cpu-utilization](graphs/postgresql_unbounded_0_cpu-utilization.png) | ![postgresql_unbounded_0_goroutines-in-use](graphs/postgresql_unbounded_0_goroutines-in-use.png)                     |
| ![postgresql_unbounded_0_heap-in-use](graphs/postgresql_unbounded_0_heap-in-use.png)         | ![postgresql_unbounded_0_number-of-connected-devices](graphs/postgresql_unbounded_0_number-of-connected-devices.png) |
| ![postgresql_unbounded_0_rps](graphs/postgresql_unbounded_0_rps.png)                         | ![postgresql_unbounded_0_stack-in-use](graphs/postgresql_unbounded_0_stack-in-use.png)                               |
