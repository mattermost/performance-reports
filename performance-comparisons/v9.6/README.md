# Performance Comparison `v9.5.1` vs `v9.6.0-rc1`

## Comments

- Number of supported users is virtually the same for both the base and new builds: a non-significant difference of -0.12% and -0.34%.
- Bounded tests do not show any significant difference either in any of the metrics considered.

## Next Steps

- No next steps.

## Setup

| Setting                              | Value                                                                                   |
| ------------------------------------ | --------------------------------------------------------------------------------------- |
| Load-test version                    | [`v1.14.0`](https://github.com/mattermost/mattermost-load-test-ng/releases/tag/v1.14.0) |
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

The following are Raintank snapshots of the original dashboards.

- [Bounded - MySQL](https://snapshots.raintank.io/dashboard/snapshot/xJGmk5mW9Pwylmxvi68CgNfZrjdbuspl)
- [Bounded - Postgres](https://snapshots.raintank.io/dashboard/snapshot/yn2bn611B22aMMwDuIobWFow18gQQ3op)
- [Unbounded - MySQL](https://snapshots.raintank.io/dashboard/snapshot/q4zdWovaP3Xn9NSOyC4yBUKIqhAGzgPY)
- [Unbounded - Postgres](https://snapshots.raintank.io/dashboard/snapshot/jQ8jjVrJTk8bSbzObvcQDDPasCHYOFNj)

### Supported users in unbounded tests

| Test     | v9.5.1 | v9.6.0-rc1 | Delta   |
| -------- | ------ | ---------- | ------- |
| MySQL    | 9230   | 9219       | \-0.12% |
| Postgres | 11330  | 11292      | \-0.34% |

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
