# Performance Comparison `v10.2.0` vs `v10.3.0-rc1`

## Comments

- This performance comparison is the first one using `c7i` and `db.r7g` instances (instead of the old `c5` and `db.r6g`). It seems to have resulted in a decrease of the number of supported users for both the base and new builds and for both Postgres ad MySQL: the performance comparison for v10.2 resulted in \~10K users for MySQL and \~13K users for Postgres, while this one ended up reporting \~7K users for MySQL and \~8K users for Postgres.
- This general decrease has not affected the percentual difference between the base and new builds. For MySQL this value is of +3.08%, while it is +3.78% for Postgres. These values fall in the interval \[-5%, +5%\] that [we recently identified as a valid threshold](https://mattermost.atlassian.net/wiki/spaces/XYZ/pages/3238199301/Variance+study).
- All tests show a general decrease of the size of the heap for the new build. This is something we have seen in other tests and, although its causes remain to be explained, it does not translate to a real difference in performance.
- Bounded tests don't show any other significant difference in the metrics considered.
- Regarding the unbounded tests, although the delta in number of supported is not significant, we can see there was a sudden decrease of number of users during the base build test on Postgres. This seems to be caused by a high number of `5xx` errors in the server according to the coordinator metrics, but logs don't show anything of interest here. As the issue was with the base build, and the final number of supported users was similar, we will not dig further.

## Action Items

- Release can continue as planned.
- No other action needed.

## Setup

| Setting                              | Value                                                                                   |
| ------------------------------------ | --------------------------------------------------------------------------------------- |
| Load-test version                    | [`v1.23.0`](https://github.com/mattermost/mattermost-load-test-ng/releases/tag/v1.23.0) |
| Dataset                              | DB dump from `v6.1.0` with 12M posts                                                    |
| Bounded - number of users (Postgres) | 7500                                                                                    |
| Bounded - number of users (MySQL)    | 5000                                                                                    |
| Bounded - duration                   | 90 minutes                                                                              |
| Unbounded - MaxActiveUsers           | 20000                                                                                   |
| Unbounded - num of users per agent   | 2000                                                                                    |
| App instances                        | 2 x c7i.2xlarge                                                                         |
| Agent instances                      | 11 x c7i.xlarge                                                                         |
| Proxy Instance                       | 1 x c7i.xlarge                                                                          |
| DB instances                         | 2 x db.r7g.2xlarge                                                                      |

## Results

### Grafana

These are snapshots of the original Grafana dashboards.

  - [Bounded - MySQL](https://snapshots.raintank.io/dashboard/snapshot/RB0FOJKfLQeo8U9y9Gjea8bENS2mJrcp)
  - [Bounded - Postgres](https://snapshots.raintank.io/dashboard/snapshot/7LiMsfcnWz5jLNshxkQFK3tqA5eHeB9x)
  - [Unbounded - MySQL](https://snapshots.raintank.io/dashboard/snapshot/StPkE9T3ZRjORv8SZfDkDEy43dGQhnQf)
  - [Unbounded - Postgres](https://snapshots.raintank.io/dashboard/snapshot/t6PDlyfuuCjS99UA4dssAP4G7rz8h68R)

### Supported users in unbounded tests

| Test     | v10.2.0 | v10.3.0-rc1 | Delta |
| -------- | ------- | ----------- | ----- |
| MySQL    | 7696    | 7933        | 3.08% |
| Postgres | 8323    | 8638        | 3.78% |


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
