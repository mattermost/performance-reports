# Performance Comparison `v9.4.0` vs `v9.5.0-rc1`

## Comments

- The bounded tests show no significant difference in any of the metrics reported.
- The unbounded tests, both for MySQL and Postgres, report a decrease in the number of supported users of around 10%.
  - However, the analysis of the logs and Prometheus metrics did not show the reason behind this decrease.
  - A second run of the comparison with the exact same setup showed a difference in MySQL of ~20% in the number of supported users, while Postgres stayed in the expected 5% threshold.
  - A third run, now with the previous version of the load-test tool, v1.12, found no significant difference between builds in any of Postgres (-4.57%) or MySQL (+1.24%).
  - The fourth run, using the current v1.13 but setting `PercentOfUsersAreAdmin` to 0, showed no significant difference between builds in any of Postgres (-5.41%) or MySQL (-4.38%).
  - We concluded that the new [coverage of the user-reporting feature](https://github.com/mattermost/mattermost-load-test-ng/pull/675) was affecting the results. [A following investigation](https://community.mattermost.com/core/pl/ysp57xtihj8ftq54qtsr7gbzch) showed no actual effect of this on controlled bounded tests, though.

## Setup

| Setting                              | Value                                                                                   |
| ------------------------------------ | --------------------------------------------------------------------------------------- |
| Load-test version                    | [`v1.13.0`](https://github.com/mattermost/mattermost-load-test-ng/releases/tag/v1.13.0) |
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

- [Bounded - MySQL](https://snapshots.raintank.io/dashboard/snapshot/hGa5Jr7u8ZaH4JK7H4EyImp4IXK7XxqD)
- [Bounded - Postgres](https://snapshots.raintank.io/dashboard/snapshot/MJO5mVaSapVoRj28CpVY2qeSymzBsqjI)
- [Unbounded - MySQL](https://snapshots.raintank.io/dashboard/snapshot/SD50C7vkpRwNMyIEZe1wcoQ1bGZCWa41)
- [Unbounded - Postgres](https://snapshots.raintank.io/dashboard/snapshot/gOIwBpSZFeVG5pATTC06VpyCh7Wxlz2u)

### Supported users in unbounded tests

| Test     | v9.4.0 | v9.5.0-rc1 | Delta    |
| -------- | ------ | ---------- | -------- |
| MySQL    | 8780   | 7889       | \-10.15% |
| Postgres | 11478  | 10377      | \-9.59%  |

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
