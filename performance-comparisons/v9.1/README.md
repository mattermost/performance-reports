# Performance Comparison `v9.0.0` vs `v9.1.0-rc1`

## Comments

  - There is no significant difference in the number of supported users or in any of the other metrics considered. One of the most stable comparisons I've seen.
  - A small spike of goroutines happened around 30 minutes after the start of the MySQL Bounded test.
      - This spike correlates with a similarly small spike in the P99 API request times.
      - This spike correlates with a similarly small spike in the stack in use.
      - The spike is distributed among both nodes, where the number of gouroutines move from a stable 1.29K to 1.43K in the first node, and from 1.28K to 1.40K in the second.
      - The spike in goroutines correspond to the functions `net/http.(*persistConn).readLoop` and `net/http.(*persistConn).writeLoop`, which points to additional connections during the peak.
      - No additional information about the spike was found in the logs, so we can discard it as a one-off issue that may need attention if it happens again, but not for now.

## Next Steps

  - No next steps.

## Setup

| Setting                              | Value                                                                                                                                            |
| ------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| Load-test version                    | Branch `perf.comp.v9.1`, commit [9f6901a](https://github.com/mattermost/mattermost-load-test-ng/commit/9f6901aeedbc3b29fa052bc6314edded2413363d) |
| Dataset                              | DB dump from `v6.1.0` with 12M posts                                                                                                             |
| Bounded - number of users (Postgres) | 7500                                                                                                                                             |
| Bounded - number of users (MySQL)    | 5000                                                                                                                                             |
| Bounded - duration                   | 90 minutes                                                                                                                                       |
| Unbounded - MaxActiveUsers           | 20000                                                                                                                                            |
| Unbounded - num of users per agent   | 2000                                                                                                                                             |
| App instances                        | 2 x c5.2xlarge                                                                                                                                   |
| Agent instances                      | 11 x c5.xlarge                                                                                                                                   |
| Proxy Instance                       | 1 x c5.xlarge                                                                                                                                    |
| DB instances                         | 2 x db.r6g.2xlarge                                                                                                                               |

## Results

### Grafana

These are Raintank snapshots of the original Grafana dashboards:

  - [Bounded - MySQL](https://snapshots.raintank.io/dashboard/snapshot/AAjlFuklbJcMiH7xGSpdk8G6XPM3o8GI)
  - [Bounded - Postgres](https://snapshots.raintank.io/dashboard/snapshot/FvotySjgccNIzSXpXzUdSLI43toSLgNW)
  - [Unbounded - MySQL](https://snapshots.raintank.io/dashboard/snapshot/RrpYuEakiMonPLwAt322BrGscz9pz4YO)
  - [Unbounded - Postgres](https://snapshots.raintank.io/dashboard/snapshot/nLge4E6pGMx8Se3GVCKcRjUKiYOjxHGZ)

### Number of errors

| Test               | v9.0.0 | v9.1.0-rc1 | Delta    |
| ------------------ | ------ | ---------- | -------- |
| Bounded MySQL      | 1981   | 1953       | \-1.41%  |
| Bounded Postgres   | 4560   | 3493       | \-23.40% |
| Unbounded MySQL    | 203972 | 218776     | 7.26%    |
| Unbounded Postgres | 147908 | 149580     | 1.13%    |

### Supported users in unbounded tests

| Test     | v9.0.0 | v9.1.0-rc1 | Delta   |
| -------- | ------ | ---------- | ------- |
| MySQL    | 12229  | 12172      | \-0.47% |
| Postgres | 12261  | 12213      | \-0.39% |

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
