# Performance Comparison `v9.11.0` vs `v10.0.0-rc2`

## Comments

- Investigation issues:
  - This report is based on the results of the second run of this comparison. The first one, tested against v10.0.0-RC1, had to be repeated because of [a bug](https://mattermost.atlassian.net/browse/MM-60269) that was uncovered during the comparison itself.
  - During the investigation of the previous bug, something interesting came up: `v10.0.0` no longer calls `RoleStore.GetByNames`. This is intended, and an improvement introduced during the implementation of Redis, where [a bug regarding this call](https://github.com/mattermost/mattermost/pull/27752#discussion_r1692578541) was found and fixed.
- Results:
  - The difference in number of supported users is not significant enough, falling in the 5% variance we usually see: -0.45% for MySQL, -2.96% for Postgres.
  - There is a reported regression in the DB store times, both in average and P99 metrics. This is perceptible in all tests, but as an example, we can take a look at some numbers from the Postgres bounded one. Taking a time window of one hour in the stable phase of the test, and looking at the `mattermost_db_store_time` metric:
    - In average, this metric is 1.9 milliseconds slower in the newer version.
    - For 99% of requests, this metric is 14.7 milliseconds slower in the newer version.
  - These times are not incredibly concerning, but they are consistent across all tests, and were reproduced in both runs of the comparison.
  - However, when removing the `RoleStore.GetByNames` metric from the computation, these numbers are virtually zero, and technically favorable to the newer version:
    - In average, this metric is 0.0525 milliseconds faster in the newer version.
    - For 99% of requests, this metric is 0.462 milliseconds slower in the newer version.
  - This shows that there is no actual regression in the DB store methods, but that the lack of calls to one of those methods in only one version skewed the computations.

## Action Items

- Release can continue as planned.
- No other action needed.

## Setup

| Setting                              | Value                                                                                   |
| ------------------------------------ | --------------------------------------------------------------------------------------- |
| Load-test version                    | [`v1.20.0`](https://github.com/mattermost/mattermost-load-test-ng/releases/tag/v1.20.0) |
| Dataset                              | DB dump from `v6.1.0` with 12M posts                                                    |
| Bounded - number of users (Postgres) | 7500                                                                                    |
| Bounded - number of users (MySQL)    | 5000                                                                                    |
| Bounded - duration                   | 90 minutes                                                                              |
| Unbounded - MaxActiveUsers           | 20000                                                                                   |
| Unbounded - num of users per agent   | 2000                                                                                    |
| App instances                        | 2 x c5.2xlarge                                                                          |
| Agent instances                      | 11 x c5.xlarge                                                                          |
| Proxy Instance                       | 1 x c5.xlarge                                                                           |
| DB instances                         | 2 x db.r6g.2xlarge                                                                      |

## Results

### Grafana

These are snapshots of the original Grafana dashboards.

- [Bounded - MySQL](https://snapshots.raintank.io/dashboard/snapshot/JUwAMKQOZ6T7FLFfYuuuKZj4SJRuh05b)
- [Bounded - Postgres](https://snapshots.raintank.io/dashboard/snapshot/ulEmHfw5ThOVxmtmj6PilZTeiQhhtvlT)
- [Unbounded - MySQL](https://snapshots.raintank.io/dashboard/snapshot/xpQtiiOP0304CneZqLubWVPbpxfpA5ep)
- [Unbounded - Postgres](https://snapshots.raintank.io/dashboard/snapshot/CpTlm8dkZuZKoxdSRzGuGXFY9pUIfMLs)

### Supported users in unbounded tests

| Test     | v9.11.0 | v10.0.0-rc2 | Delta   |
| -------- | ------- | ----------- | ------- |
| MySQL    | 11137   | 11087       | \-0.45% |
| Postgres | 13223   | 12832       | \-2.96% |


### Graphs - Bounded MySQL

| ![mysql_bounded_0_avg-api-times](graphs/mysql_bounded_0_avg-api-times.png) | ![mysql_bounded_0_p99-api-times](graphs/mysql_bounded_0_p99-api-times.png) |
| --- | ---|
| ![mysql_bounded_0_avg-store-times](graphs/mysql_bounded_0_avg-store-times.png) | ![mysql_bounded_0_p99-store-times](graphs/mysql_bounded_0_p99-store-times.png) |
| ![mysql_bounded_0_cpu-utilization](graphs/mysql_bounded_0_cpu-utilization.png) | ![mysql_bounded_0_goroutines-in-use](graphs/mysql_bounded_0_goroutines-in-use.png) |
| ![mysql_bounded_0_heap-in-use](graphs/mysql_bounded_0_heap-in-use.png) | ![mysql_bounded_0_number-of-connected-devices](graphs/mysql_bounded_0_number-of-connected-devices.png) |
| ![mysql_bounded_0_rps](graphs/mysql_bounded_0_rps.png) | ![mysql_bounded_0_stack-in-use](graphs/mysql_bounded_0_stack-in-use.png) |

### Graphs - Bounded Postgres

| ![postgresql_bounded_0_avg-api-times](graphs/postgresql_bounded_0_avg-api-times.png) | ![postgresql_bounded_0_p99-api-times](graphs/postgresql_bounded_0_p99-api-times.png) |
| --- | ---|
| ![postgresql_bounded_0_avg-store-times](graphs/postgresql_bounded_0_avg-store-times.png) | ![postgresql_bounded_0_p99-store-times](graphs/postgresql_bounded_0_p99-store-times.png) |
| ![postgresql_bounded_0_cpu-utilization](graphs/postgresql_bounded_0_cpu-utilization.png) | ![postgresql_bounded_0_goroutines-in-use](graphs/postgresql_bounded_0_goroutines-in-use.png) |
| ![postgresql_bounded_0_heap-in-use](graphs/postgresql_bounded_0_heap-in-use.png) | ![postgresql_bounded_0_number-of-connected-devices](graphs/postgresql_bounded_0_number-of-connected-devices.png) |
| ![postgresql_bounded_0_rps](graphs/postgresql_bounded_0_rps.png) | ![postgresql_bounded_0_stack-in-use](graphs/postgresql_bounded_0_stack-in-use.png) |

### Graphs - Unbounded MySQL

| ![mysql_unbounded_0_avg-api-times](graphs/mysql_unbounded_0_avg-api-times.png)     | ![mysql_unbounded_0_p99-api-times](graphs/mysql_unbounded_0_p99-api-times.png)                             |
| --- | --- |
| ![mysql_unbounded_0_avg-store-times](graphs/mysql_unbounded_0_avg-store-times.png) | ![mysql_unbounded_0_p99-store-times](graphs/mysql_unbounded_0_p99-store-times.png)                         |
| ![mysql_unbounded_0_cpu-utilization](graphs/mysql_unbounded_0_cpu-utilization.png) | ![mysql_unbounded_0_goroutines-in-use](graphs/mysql_unbounded_0_goroutines-in-use.png)                     |
| ![mysql_unbounded_0_heap-in-use](graphs/mysql_unbounded_0_heap-in-use.png)         | ![mysql_unbounded_0_number-of-connected-devices](graphs/mysql_unbounded_0_number-of-connected-devices.png) |
| ![mysql_unbounded_0_rps](graphs/mysql_unbounded_0_rps.png)                         | ![mysql_unbounded_0_stack-in-use](graphs/mysql_unbounded_0_stack-in-use.png)                               |


### Graphs - Unbounded Postgres

| ![postgresql_unbounded_0_avg-api-times](graphs/postgresql_unbounded_0_avg-api-times.png)     | ![postgresql_unbounded_0_p99-api-times](graphs/postgresql_unbounded_0_p99-api-times.png)                             |
| --- | ---|
| ![postgresql_unbounded_0_avg-store-times](graphs/postgresql_unbounded_0_avg-store-times.png) | ![postgresql_unbounded_0_p99-store-times](graphs/postgresql_unbounded_0_p99-store-times.png)                         |
| ![postgresql_unbounded_0_cpu-utilization](graphs/postgresql_unbounded_0_cpu-utilization.png) | ![postgresql_unbounded_0_goroutines-in-use](graphs/postgresql_unbounded_0_goroutines-in-use.png)                     |
| ![postgresql_unbounded_0_heap-in-use](graphs/postgresql_unbounded_0_heap-in-use.png)         | ![postgresql_unbounded_0_number-of-connected-devices](graphs/postgresql_unbounded_0_number-of-connected-devices.png) |
| ![postgresql_unbounded_0_rps](graphs/postgresql_unbounded_0_rps.png)                         | ![postgresql_unbounded_0_stack-in-use](graphs/postgresql_unbounded_0_stack-in-use.png)                               |
                                                                                                                                                                                                 |                                                                                                                                                                                                                         |
                                                                                                                                                                                                               |                                                                                                                                                                                                                                       |
