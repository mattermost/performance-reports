
# Performance Comparison `v11.2.0` vs `v11.3.0-rc1`

## Comments

- One of the most boring (boring is good\!) performance comparisons as of lately:
  - The unbounded test shows no significant difference: a 1.61% decrease in the number of supported users for the new release, well within the \[-5%, +5%\] interval.
  - The bounded test shows no significant difference in any of the metrics considered.

## Action Items

- Release can continue as planned.
- No other action needed.

## Setup

| Setting                              | Value                                                                                              |
| ------------------------------------ | -------------------------------------------------------------------------------------------------- |
| Load-test version                    | [`v1.30.0`](https://github.com/mattermost/mattermost-load-test-ng/releases/tag/v1.30.0)            |
| Dataset                              | [Dump from `v6.1.0`, 12M posts](https://lt-public-data.s3.amazonaws.com/12M_610_fixed_psql.sql.gz) |
| Bounded - number of users (Postgres) | 6500                                                                                               |
| Bounded - duration                   | 90 minutes                                                                                         |
| Unbounded - MaxActiveUsers           | 20000                                                                                              |
| Unbounded - num of users per agent   | 2000                                                                                               |
| App instances                        | 2 x c7i.2xlarge                                                                                    |
| Agent instances                      | 11 x c7i.xlarge                                                                                    |
| Proxy Instance                       | 1 x c7i.xlarge                                                                                     |
| DB instances                         | 2 x db.r7g.2xlarge                                                                                 |

## Results

### Grafana

These are snapshots of the original Grafana dashboards.

- [Bounded test](https://snapshots.raintank.io/dashboard/snapshot/wu1SNJDruUSKkmKCNnJ3xpp0JPFCdaJz)
- [Unbounded test](https://snapshots.raintank.io/dashboard/snapshot/cJXc61zCpg5AgQ6Jv9mMoh2LQ1OQYqBh)

### Supported users in unbounded test

| v11.2.0 | v11.3.0-rc1 | Delta   |
| ------- | ----------- | ------- |
| 15641   | 15389       | \-1.61% |

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
