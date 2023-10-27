# Performance Comparison `v9.1.0` vs `v9.2.0-rc1`

## Comments

- Meta comments:
  - Used new coordinator metrics, the same set used in the ceiling tests.
  - Used new version of the load-test tool, [v1.10.0](https://github.com/mattermost/mattermost-load-test-ng/releases/tag/v1.10.0).
- Analysis:
  - Number of users has not changed significantly (+1.13% in Postgres, -3.48% in MySQL).
  - Metrics don't show any change in general, with the only exception being the stack size, which has increased significantly in all tests. This is something we see from time to time in these comparisons, and never analyzed properly. Some numbers:
    - MySQL bounded: from $7.5 \times 10^{7}$ to $9.5 \times 10^{7}$
    - MySQL unbounded (latest 15-20 minutes): from $1.6 \times 10^{8}$ to $1.8 \times 10^{8}$
    - Postgres bounded: from $1.15 \times 10^{8}$ to $1.35 \times 10^{8}$
    - Postgres unbounded (latest 15-20 minutes): from $1.6 \times 10^{8}$ to $1.8 \times 10^{8}$

## Next Steps

  - No performance regression was found: the release can continue as planned.
  - Created [this ticket](https://mattermost.atlassian.net/browse/MM-55191) to track the investigation on the stack size differences.

## Setup

| Setting                              | Value                                                                                   |
| ------------------------------------ | --------------------------------------------------------------------------------------- |
| Load-test version                    | [`v1.10.0`](https://github.com/mattermost/mattermost-load-test-ng/releases/tag/v1.10.0) |
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

- Comparison dashboard
  - Postgres unbounded: <https://snapshots.raintank.io/dashboard/snapshot/o5T6b05p1hXvpTFlozXTIsz7C4GEkzgR>
  - Postgres bounded: <https://snapshots.raintank.io/dashboard/snapshot/yfXfLVxYmB57LSTUNshm89Je5xdUUPke>
  - MySQL unbounded: <https://snapshots.raintank.io/dashboard/snapshot/XWyhhFv1xOxSJZY3HGSIxxc3K7Nsy0aS>
  - MySQL bounded: <https://snapshots.raintank.io/dashboard/snapshot/itnJUUGO6jwLhBCCgG5V9DPqaTxEGYUv>
- Performance dashboard
  - Base
    - Postgres unbounded: <https://snapshots.raintank.io/dashboard/snapshot/GAUUDd39LoNOaE30LGqATQJEnEavwJKl>
    - Postgres bounded: <https://snapshots.raintank.io/dashboard/snapshot/x49Hsw1Bk21rOZV0rEL5gNpQ2LdA8Qvm>
    - MYSQL unbounded: <https://snapshots.raintank.io/dashboard/snapshot/hjbKd2iBlLRz4tnSYdzhLUxzMor6qfR2>
    - MySQL bounded: <https://snapshots.raintank.io/dashboard/snapshot/b994DHOEksZy72YBv5IJdLdqD2FJQkbc>
  - New
    - Postgres unbounded: <https://snapshots.raintank.io/dashboard/snapshot/TNn1eUJInUbXQkCHGu28ivrjuNVJHpzL>
    - Postgres bounded: <https://snapshots.raintank.io/dashboard/snapshot/R1fYJhdFr2LhXzeJ9edRCmo3lKdthrYZ>
    - MYSQL unbounded: <https://snapshots.raintank.io/dashboard/snapshot/8s3Qd8U78AOlgqVuSyakbyCnDH9w2LGp>
    - MySQL bounded: <https://snapshots.raintank.io/dashboard/snapshot/pU42Bo6Ani0AmVgM33cq1xRblqZqCYpJ>

### Number of errors

| Test             | v9.1.0 | v9.2.0-rc1 | Delta   |
| ---------------- | ------ | ---------- | ------- |
| Bounded Postgres | 4333   | 4146       | \-4.32% |
| Bounded MySQL    | 2491   | 2507       | 0.64%   |

### Supported users in unbounded tests

| Test     | v9.1.0 | v9.2.0-rc1 | Delta   |
| -------- | ------ | ---------- | ------- |
| Postgres | 10571  | 10690      | 1.13%   |
| MySQL    | 10588  | 10220      | \-3.48% |

### Graphs - Bounded MySQL

| ![mysql_bounded_0_avg-api-times](graphs/mysql_bounded_0_avg-api-times.png) | ![mysql_bounded_0_p99-api-times](graphs/mysql_bounded_0_p99-api-times.png) |
| --- | --- |
| ![mysql_bounded_0_avg-store-times](graphs/mysql_bounded_0_avg-store-times.png) | ![mysql_bounded_0_p99-store-times](graphs/mysql_bounded_0_p99-store-times.png) |
| ![mysql_bounded_0_cpu-utilization](graphs/mysql_bounded_0_cpu-utilization.png) | ![mysql_bounded_0_goroutines-in-use](graphs/mysql_bounded_0_goroutines-in-use.png) |
| ![mysql_bounded_0_heap-in-use](graphs/mysql_bounded_0_heap-in-use.png) | ![mysql_bounded_0_number-of-connected-devices](graphs/mysql_bounded_0_number-of-connected-devices.png) |
| ![mysql_bounded_0_rps](graphs/mysql_bounded_0_rps.png) | ![mysql_bounded_0_stack-in-use](graphs/mysql_bounded_0_stack-in-use.png) |

### Graphs - Bounded Postgres

| ![postgresql_bounded_0_avg-api-times](graphs/postgresql_bounded_0_avg-api-times.png) | ![postgresql_bounded_0_p99-api-times](graphs/postgresql_bounded_0_p99-api-times.png) |
| --- | --- |
| ![postgresql_bounded_0_avg-store-times](graphs/postgresql_bounded_0_avg-store-times.png) | ![postgresql_bounded_0_p99-store-times](graphs/postgresql_bounded_0_p99-store-times.png) |
| ![postgresql_bounded_0_cpu-utilization](graphs/postgresql_bounded_0_cpu-utilization.png) | ![postgresql_bounded_0_goroutines-in-use](graphs/postgresql_bounded_0_goroutines-in-use.png) |
| ![postgresql_bounded_0_heap-in-use](graphs/postgresql_bounded_0_heap-in-use.png) | ![postgresql_bounded_0_number-of-connected-devices](graphs/postgresql_bounded_0_number-of-connected-devices.png) |
| ![postgresql_bounded_0_rps](graphs/postgresql_bounded_0_rps.png) | ![postgresql_bounded_0_stack-in-use](graphs/postgresql_bounded_0_stack-in-use.png) |

### Graphs - Unbounded MySQL

| ![mysql_unbounded_0_avg-api-times](graphs/mysql_unbounded_0_avg-api-times.png) | ![mysql_unbounded_0_p99-api-times](graphs/mysql_unbounded_0_p99-api-times.png) |
| --- | --- |
| ![mysql_unbounded_0_avg-store-times](graphs/mysql_unbounded_0_avg-store-times.png) | ![mysql_unbounded_0_p99-store-times](graphs/mysql_unbounded_0_p99-store-times.png) |
| ![mysql_unbounded_0_cpu-utilization](graphs/mysql_unbounded_0_cpu-utilization.png) | ![mysql_unbounded_0_goroutines-in-use](graphs/mysql_unbounded_0_goroutines-in-use.png) |
| ![mysql_unbounded_0_heap-in-use](graphs/mysql_unbounded_0_heap-in-use.png) | ![mysql_unbounded_0_number-of-connected-devices](graphs/mysql_unbounded_0_number-of-connected-devices.png) |
| ![mysql_unbounded_0_rps](graphs/mysql_unbounded_0_rps.png) | ![mysql_unbounded_0_stack-in-use](graphs/mysql_unbounded_0_stack-in-use.png) |

### Graphs - Unbounded Postgres

| ![postgresql_unbounded_0_avg-api-times](graphs/postgresql_unbounded_0_avg-api-times.png) | ![postgresql_unbounded_0_p99-api-times](graphs/postgresql_unbounded_0_p99-api-times.png) |
| --- | --- |
| ![postgresql_unbounded_0_avg-store-times](graphs/postgresql_unbounded_0_avg-store-times.png) | ![postgresql_unbounded_0_p99-store-times](graphs/postgresql_unbounded_0_p99-store-times.png) |
| ![postgresql_unbounded_0_cpu-utilization](graphs/postgresql_unbounded_0_cpu-utilization.png) | ![postgresql_unbounded_0_goroutines-in-use](graphs/postgresql_unbounded_0_goroutines-in-use.png) |
| ![postgresql_unbounded_0_heap-in-use](graphs/postgresql_unbounded_0_heap-in-use.png) | ![postgresql_unbounded_0_number-of-connected-devices](graphs/postgresql_unbounded_0_number-of-connected-devices.png) |
| ![postgresql_unbounded_0_rps](graphs/postgresql_unbounded_0_rps.png) | ![postgresql_unbounded_0_stack-in-use](graphs/postgresql_unbounded_0_stack-in-use.png) |
