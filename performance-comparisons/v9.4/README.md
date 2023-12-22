# Performance Comparison `v9.3.0` vs `v9.4.0-rc3`

## Comments

  - This performance comparison was the first one 100% executed by @dylan.haussermann. Thank you, Dylan\!
  - The unbounded tests show a 5.6% increase in the number of supported users for both MySQL and Postgres. This number lies in the usual variance we've been seeing for supported users lately, so it is not significant enough to ensure there is an actual improvement.
  - The manual exploratory testing supports this apparent performance improvement as well.
  - The bounded tests show a couple of spikes in the number of goroutines and stack in use that quickly stabilize, for both MySQL and Postgres. Those spikes are not due to a spike in the number of connected users.
  - As identified in the past, the heap in use seems to be consistently larger for v9.4.0-rc3 than for v9.3.0. This remains something we need to investigate further: https://mattermost.atlassian.net/browse/MM-55191.
  - Due to an error in the collection of results (instances were out of sync with local state, and then I performed a destructive action), there are no Grafana dashboards available for Postgres unbounded, although the graphs are present.

## Next Steps

  - No next steps, release can continue as planned.

## Setup

| Setting                              | Value                                                                                   |
| ------------------------------------ | --------------------------------------------------------------------------------------- |
| Load-test version                    | [`v1.12.0`](https://github.com/mattermost/mattermost-load-test-ng/releases/tag/v1.12.0) |
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

The config files used are attached to this post.

## Results

### Grafana

The following are snapshots of the original dashboards. Due to an error in the collection of results, there is no Grafana dashboard available for Postgres unbounded.

  - [Bounded - MySQL](https://snapshots.raintank.io/dashboard/snapshot/Gq5nXbKUOOvHm5yQfuOdc8lpIONQrMEI)
  - [Bounded - Postgres](https://snapshots.raintank.io/dashboard/snapshot/8rKA5RXopXyRM41DIS7sDbLkbo8QELvA)
  - [Unbounded - MySQL](https://snapshots.raintank.io/dashboard/snapshot/x2DqaV7KH3D2LeyBJa50qlDpNuUXXhfw)

### Supported users in unbounded tests

| Test     | v9.3.0 | v9.4.0-rc3 | Delta |
| -------- | ------ | ---------- | ----- |
| MySQL    | 10616  | 11219      | 5.68% |
| Postgres | 10992  | 11606      | 5.59% |

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
