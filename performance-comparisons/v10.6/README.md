# Performance Comparison `v10.5.0` vs `v10.6.0-rc3`

## Comments

- This performance comparison had to be executed three times, one for each release candidate of v10.6.0:
  - [The comparison for RC1](https://community.mattermost.com/core/pl/ty6kgybndi8adme8558b9g9q1o) showed clear symptoms of a problem, the most prominent being that the app nodes suddenly stopped, with not apparent reason (see screenshot below). [The first theory](https://community.mattermost.com/core/pl/96pb4ytog38dmrbbi38jgna1ro) was that [a fix in the webhub](https://github.com/mattermost/mattermost/pull/30224) was not present in RC1, and was causing the issues, so we decided to repeat the comparison with RC2.
  - [The comparison for RC2](https://community.mattermost.com/core/pl/4rb6bx3ddbd5jyicsom1wpkgpo) showed the exact same symptoms, and after [a lengthy investigation](https://community.mattermost.com/core/pl/6wxmjeykdbd9zfo8ggrxdqcrgr), we found out [the real bug](https://mattermost.atlassian.net/browse/MM-63304), which was causing random crashes in the server.
  - That bug was fixed and released on RC3, and this report covers the results of that comparison.

![Screenshot of Grafana showing the app nodes suddenly stopping and thus disconnecting all its users](./report_img/crash.png)

- The results of this comparison are nonetheless surprising, specially regarding unbounded tests:
  - The reported number of supported users in `v10.6.0-RC3` with respect to `v10.5.0` is a 16.86% higher for MySQL and a 15.70% higher for Postgres.
  - Looking closely at the graphs, it seems that `v10.6.0-RC3` starts hitting the coordinator metrics slightly before `v10.5.0`, but the growth of users is more steady, so the coordinator stops the test way after, thus reporting a larger number of supported users. See screenshots below.
  - The number of supported users are back to what we were used to, with Postgres being slightly more performant than MySQL: a difference of 1.52% for the base build and a difference of 0.51% for the new build.

![Screenshot of the number of supported users in Postgres](./report_img/postgresunbounded.png)

![Screenshot of the number of supported users in MySQL](./report_img/mysqlunbounded.png)

- Metrics considered in the bounded tests do not show any significant difference.
- CPU profiles do not show large differences either. The only one showing a large difference is MySQL bounded: the whole tree under `app.(*Server).Start.(*Cors).Handler.func3` is removed/added in the new build because the root got renamed to `app.(*Server).Start.(*Cors).Handler.func4` (see screenshot below). The cause is still unknown, and it's not clear why it only happened on MySQL bounded. See the diffs of the CPU profiles, with the entire test considered for unbounded tests, and only the stable part considered for bounded tests:
  - [Postgres unbounded](https://flamegraph.com/share/5ec3609e-fdd4-11ef-8d53-2a7e77e4af82)
  - [MySQL unbounded](https://flamegraph.com/share/6338f87b-fdd4-11ef-8d53-2a7e77e4af82)
  - [Postgres bounded](https://flamegraph.com/share/67a051ef-fdd4-11ef-8d53-2a7e77e4af82)
  - [MySQL bounded](https://flamegraph.com/share/6e7ccb27-fdd4-11ef-8d53-2a7e77e4af82)

![Screenshot of the CPU profile diff](./report_img/cpudiff.png)

## Action Items

- Discuss the increase in number of supported users
- Discuss the difference in the CPU profile for MySQL bounded

## Setup

| Setting                              | Value                                                                                                                                                                                      |
| ------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Load-test version                    | [`v1.25.0`](https://github.com/mattermost/mattermost-load-test-ng/releases/tag/v1.25.0)                                                                                                    |
| Dataset                              | Dump from `v6.1.0`, 12M posts ([postgres](https://lt-public-data.s3.amazonaws.com/12M_610_fixed_psql.sql.gz), [mysql](https://lt-public-data.s3.amazonaws.com/12M_610_fixed_mysql.sql.gz)) |
| Bounded - number of users (Postgres) | 7500                                                                                                                                                                                       |
| Bounded - number of users (MySQL)    | 5000                                                                                                                                                                                       |
| Bounded - duration                   | 90 minutes                                                                                                                                                                                 |
| Unbounded - MaxActiveUsers           | 20000                                                                                                                                                                                      |
| Unbounded - num of users per agent   | 2000                                                                                                                                                                                       |
| App instances                        | 2 x c7i.2xlarge                                                                                                                                                                            |
| Agent instances                      | 11 x c7i.xlarge                                                                                                                                                                            |
| Proxy Instance                       | 1 x c7i.xlarge                                                                                                                                                                             |
| DB instances                         | 2 x db.r7g.2xlarge                                                                                                                                                                         |

## Results

### Grafana

These are snapshots of the original Grafana dashboards.

- [Bounded - MySQL](https://snapshots.raintank.io/dashboard/snapshot/dQa7igswhi9Ohx1pVAOlQcoH3n5ABLYa)
- [Bounded - Postgres](https://snapshots.raintank.io/dashboard/snapshot/caW05CibLAr6WuTQQ7yl5NjUeL1CPF7m)
- [Unbounded - MySQL](https://snapshots.raintank.io/dashboard/snapshot/pJezsAGu95c81VbxaNUw2a2T9Pj9P0ew)
- [Unbounded - Postgres](https://snapshots.raintank.io/dashboard/snapshot/9p9ZLK9FtSfFbXZVF5Ymii5IXCKobQGz)

### Supported users in unbounded tests

| Test     | v10.5.0 | v10.6.0-rc3 | Delta  |
| -------- | ------- | ----------- | ------ |
| MySQL    | 8552    | 9994        | 16.86% |
| Postgres | 8682    | 10045       | 15.70% |

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
