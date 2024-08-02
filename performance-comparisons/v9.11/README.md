# Performance Comparison `v9.10.0` vs `v9.11.0-rc2`

## Comments

- The MySQL unbounded tests had to be repeated because of a one-off issue that caused a malfunction in the first run. The second run worked as expected.
- The difference in the number of supported users in unbounded tests is not significant: -3.64% in MySQL and +1.17% in Postgres, both under the usual variance of +/-5%.
- The metrics considered in bounded tests do not show any significant difference either.

## Action Items

- Release can continue as planned.
- No other action needed.

## Setup

| Setting                              | Value                                                                                   |
| ------------------------------------ | --------------------------------------------------------------------------------------- |
| Load-test version                    | [`v1.19.0`](https://github.com/mattermost/mattermost-load-test-ng/releases/tag/v1.19.0) |
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

No snapshots this time around.

### Supported users in unbounded tests

| Test     | v9.10.0 | v9.11.0-rc2 | Delta   |
| -------- | ------- | ----------- | ------- |
| MySQL    | 10356   | 9979        | \-3.64% |
| Postgres | 12086   | 12228       | 1.17%   |

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
