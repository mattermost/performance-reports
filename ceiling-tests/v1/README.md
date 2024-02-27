# Report of Ceiling Tests v1

This document describes the specifications of the first version of the ceiling tests, executed between September 14, 2023 and October 24, 2023, as well as its results.

## Goals

The goals of this document are:

1. Provide a detailed description of the specification of the tests, so that:
    1. The tests are reproducible at any time
    2. The results of the tests are properly contextualized
2. Provide a detailed report of the results of the tests.

## Background reading

1. [Reference Architectures](https://docs.google.com/document/u/0/d/14A2dRqc03w5hAo3qfctcI5YwyaL9fnJMhBDXERcwoMU/edit), the document used to plan these tests.

## Disclaimer

This first version of the ceiling tests was an exploratory one, and as such, the results need to be taken with a pinch of salt. We were learning about the tool and the tests themselves as we executed them. This means that the results, although valid for giving us the bird's eye view of where the system currently stands, cannot be relied upon completely. They cannot be compared against each other either generally, since the conditions of each test ended up varying more than what we had designed in the first place. This is something that v2 will solve.

## Test specifications

### General description

The tests were executed in three phases:

- Phase 0 - Exploratory testing: Tests in this phase were designed to find out which family of AWS instances, both for the app nodes and the database nodes, the rest of the phases were going to test.
- Phase 1 - Broad overview: A wide range of architectures to understand how the system behaves with both horizontal and vertical scaling.
- Phase 2 - Ceiling tests: A carefully selected range of architectures to look for the actual maximum number of users supported by the system.

The naming of each test is defined by the initial plan designed in the [Reference Architectures](https://docs.google.com/document/u/0/d/14A2dRqc03w5hAo3qfctcI5YwyaL9fnJMhBDXERcwoMU/edit) document, as `{phase}.{test number}`, where phase is the number of the phase (0, 1 or 2) and test number is the identifier of the test (it can be just a number, or a number followed by a letter). Refer to the linked document for more information.

Each test was executed three times to get an averaged result.

A couple of notes about the second phase:
- The tests finally executed were only `2.1.a`, `2.1.b` and `2.1.d`.
- There were some errors during some of the additional runs, after which we decided to stop the tests and postpone them until v2. This happened in:
  - Test `2.1.b`, which was only executed once.
  - Test `2.1.d`, which was only executed twice.


### Common specifications

#### Load-test tool

All tests were executed using [the load-test tool](https://github.com/mattermost/mattermost-load-test-ng), a custom-built framework uniquely designed for stress-testing Mattermost servers.

All tests, except for those in phase 0, were *unbounded* tests; i.e., tests that estimate how much load a Mattermost server can support, according to some predefined metrics. These tests report the maximum number of users supported by the target system while maintaining all metrics under the specified thresholds. Learn more about the nature of such tests in [the tool documentation](https://github.com/mattermost/mattermost-load-test-ng/blob/dcc95b8250bbc821ac3cacaf020824b4ce955036/docs/faq.md#what-is-an-unbounded-load-test).

There are two important variables in how the tool is configured that greatly affect the results of tests:
- The actions executed by each simulated user, and their frequencies.
- The coordinator metrics that define what we understand by a healthy system.

Each of these are covered in the [Action frequencies](#action-frequencies) and [Coordinator metrics](#coordinator-metrics) sections below.

##### Load-test tool version

The version used for all tests, except for tests 1.1.x and 1.2.x, is the one built from this commit: [dcc95b8](https://github.com/mattermost/mattermost-load-test-ng/commit/dcc95b8250bbc821ac3cacaf020824b4ce955036).

Tests 1.1.x and 1.2.x used the officially released [version v1.12.0](https://github.com/mattermost/mattermost-load-test-ng/releases/tag/v1.12.0).

The [differences between those two versions](https://github.com/mattermost/mattermost-load-test-ng/compare/dcc95b8250bbc821ac3cacaf020824b4ce955036..0dcc114851870b64af32b2bb4a7db523e8d27e3d) are not negligible, so the results of tests 1.1.x and 1.2.x cannot be 100% compared with the rest of tests. We added those two tests later on to try to close a large gap in number of supported users between tests, as the initially tested architectures jumped from 1000 to 25000 users.

Later versions of this test suite will fix this difference in versions so that results can be compared.
  
##### Action frequencies

Each test simulates a number of users, who behave similar to a real user by executing a series of actions with given relative frequencies.

These frequencies were computed to match an average user in on our largest customer in Cloud, during a 2-hour time window where the number of concurrently connected devices were at its highest. The actual definition of the frequencies can be found [in the code](https://github.com/mattermost/mattermost-load-test-ng/blob/dcc95b8250bbc821ac3cacaf020824b4ce955036/loadtest/control/simulcontroller/controller.go#L19-L205), and the procedure of how these were computed in the [Action frequencies review](https://docs.google.com/document/d/1A4gRuJBymamP5cTgYkI-CJV3n4Sj4nF07Zn44seuaks/edit#) document. The following table shows the actions used in these tests sorted by relative frequency:

| Action                             | Freq   |
|------------------------------------|--------|
| `SwitchChannel`                    | 6.5219 |
| `ScrollChannel`                    | 1.9873 |
| `CreatePost`                       | 1      |
| `UnreadCheck`                      | 1      |
| `OpenDirectOrGroupChannel`         | 0.9843 |
| `ViewGlobalThreads`                | 0.6023 |
| `UpdateThreadRead`                 | 0.3236 |
| `ClickPermalink`                   | 0.3    |
| `ViewThread`                       | 0.2841 |
| `ReconnectWebSocket`               | 0.144  |
| `AddReaction`                      | 0.1306 |
| `EditPost`                         | 0.04   |
| `SearchUsers`                      | 0.032  |
| `ClickUserProfile`                 | 0.03   |
| `SearchPosts`                      | 0.0218 |
| `SearchGroupChannels`              | 0.0204 |
| `SearchChannels`                   | 0.015  |
| `CreateDirectChannel`              | 0.0055 |
| `UnfollowThread`                   | 0.005  |
| `DeletePost`                       | 0.0049 |
| `JoinChannel`                      | 0.0049 |
| `UpdateSidebarCategory`            | 0.004  |
| `CreateGroupChannel`               | 0.0029 |
| `UpdateCustomStatus`               | 0.0028 |
| `RemoveCustomStatus`               | 0.0026 |
| `FullReload`                       | 0.0008 |
| `LogoutLogin`                      | 0.0006 |
| `CreatePostReminder`               | 0.0005 |
| `FollowThread`                     | 0.0005 |
| `CreatePrivateChannel`             | 0.0002 |
| `AckToPost`                        | 0.0001 |
| `CreateAclPost`                    | 0.0001 |
| `CreatePersistentNotificationPost` | 0.0001 |
| `CreatePublicChannel`              | 0.0001 |
| `CreateSidebarCategory`            | 0.0001 |
| `MarkAllThreadsInTeamAsRead`       | 0.0001 |
| `SwitchTeam`                       | 0.0001 |

##### Config

There are multiple files to configure the tests, from the nature of the simulation to the specific behaviour of the users or the architecture of the server to test. However, most of that configuration was kept as default, modifying only the three following files:
- config.json
- coordinator.json
- deployer.json

The following subsections go through each of them, highlighting the interesting parts for the definition of the tests. For the complete contents of the files, check out the `common-config.json`, `common-coordinator.json` and `common-deployer.json` files. 

###### `config.json`

The first section of this file, `ConnectionConfiguration` doesn't change the defaults:

``` json
"ConnectionConfiguration": {
  "ServerURL": "http://localhost:8065",
  "WebSocketURL": "ws://localhost:8065",
  "AdminEmail": "sysadmin@sample.mattermost.com",
  "AdminPassword": "Sys@dmin-sample1"
}
```

The second section, `UserControllerConfiguration`, states that we are running a simulative test, and it contains the `RatesDistribution` setting, which defines how fast the users perform their actions in the simulation. Its value, 5.4, was empirically chosen to match the frequency of the `createPost` action in the reference server when running the same number of users connected during the reference time window.

```json
"UserControllerConfiguration": {
  "Type": "simulative",
  "RatesDistribution": [
    {
      "Rate": 5.4,
      "Percentage": 1
    }
  ],
  "ServerVersion": ""
}
```

The third section, `InstanceConfiguration`, although provided, is not used by the tests, since we provide the exact same set of initial data to all tests: see the [Database](#database) section for more information. We're not reproducing this section here.

The next section, `UsersConfiguration`, configures each agent to control 2000 users. This value is the *de facto* standard for the chosen instance type for each agent (see the [`deployer.json`](#deployerjson) section for more information).

``` json
"UsersConfiguration": {
  "InitialActiveUsers": 0,
  "UsersFilePath": "",
  "MaxActiveUsers": 2000,
  "AvgSessionsPerUser": 1
}
```

Finally, the `LogSettings` section contain debugging configuration that does not affect the results of the tests at all, so we're skipping it here as well.

###### `coordinator.json`

This file contains configuration for three main aspects:
- How many users the test can simulate in total.
- The metrics that define what a healthy system means.
- How fast the users are added when the system is healthy and can accept new connections.

The first section, `ClusterConfig`, was mainly the same for all tests, although the maximum number of users had to be increased for the larger tests. Thus, `ClusterConfig.MaxActiveUsers`'s value varied between 20000, 40000, 70000 or 100000.

``` json
"ClusterConfig": {
  "Agents": [
    {
      "Id": "lt0",
      "ApiURL": "http://localhost:4000"
    }
  ],
  "MaxActiveUsers": 20000
}
```

The second section, `MonitorConfig`, is the one defining the coordinator metrics. The way an unbounded test works is by connection new users to the server while the system is healthy. But how do we define when a system is healthy? We do that through the coordinator metrics under its `Queries` field. The coordinator metrics are a series of measurements of different system characteristics that are expected to be under a configured threshold to consider a system to be healthy. When any of these metrics surpass their corresponding threshold, the test disconnects some users to try to keep the system stable. When that occurs, it resume adding new users.

For a series of tests to be comparable against each other, they should have the same metrics, and that's how we designed these tests at the beginning. However, we realized later on that there were some characteristics of the system that we were not monitoring, so we decided to add additional metrics in `MonitorConfig.Queries` to some of the tests.

The following snippet lists all the possible metrics we used in every test, but see the [Individual specifications](#individual-specifications) section to know which tests used which metric.

``` json
"MonitorConfig": {
  "PrometheusURL": "http://localhost:9090",
  "UpdateIntervalMs": 2000,
  "Queries": [
    {
      "Description": "Percentage of HTTP 5xx server errors",
      "Query": "(sum(rate(mattermost_api_time_count{status_code=~\"5..\"}[1m]))/sum(rate(mattermost_api_time_count[1m])))*100",
      "Threshold": 0.025,
      "MinIntervalSec": 60,
      "Alert": true
    },
    {
      "Description": "Average client request duration",
      "Query": "sum(rate(loadtest_http_request_time_sum[1m]))/sum(rate(loadtest_http_request_time_count[1m]))",
      "Threshold": 0.1,
      "MinIntervalSec": 60,
      "Alert": true
    },
    {
      "Description": "99th percentile of client request duration",
      "Query": "histogram_quantile(0.99, sum(rate(loadtest_http_request_time_bucket[1m])) by (le))",
      "Threshold": 2,
      "MinIntervalSec": 60,
      "Alert": true
    },
    {
      "Description": "Percentage of HTTP 5xx client errors",
      "Query": "(sum(rate(loadtest_http_errors_total{status_code=~\"5..\"}[1m]))/sum(rate(loadtest_http_request_time_count[1m])))*100",
      "Threshold": 0.025,
      "MinIntervalSec": 60,
      "Alert": true
    },
    {
      "Description": "Percentage of client timeouts",
      "Query": "(sum(rate(loadtest_http_timeouts_total[1m]))/sum(rate(loadtest_http_request_time_count[1m]))) * 100",
      "Threshold": 0.025,
      "MinIntervalSec": 60,
      "Alert": true
    },
    {
      "Description": "CPU utilization",
      "Query": "100 - 100 * (avg(irate(node_cpu_seconds_total{instance=~\"app.*\",mode=\"idle\"}[5m])))",
      "Threshold": 85,
      "MinIntervalSec": 60,
      "Alert": true
    },
    {
      "Description": "Memory utilization",
      "Query": "100 - 100 * avg(node_memory_MemAvailable_bytes{instance=~\"app.*\"} / node_memory_MemTotal_bytes{instance=~\"app.*\"})",
      "Threshold": 85,
      "MinIntervalSec": 60,
      "Alert": true
    },
    {
      "Description": "Percentage of TCP timeouts in the proxy node",
      "Query": "100 * rate(node_netstat_TcpExt_TCPTimeouts{instance=~\"proxy:9100\"}[1m]) / (rate(node_netstat_TcpExt_TCPTimeouts{instance=~\"proxy:9100\"}[1m]) + node_netstat_Tcp_CurrEstab{instance=~\"proxy:9100\"})",
      "Threshold": 0.2,
      "MinIntervalSec": 60,
      "Alert": true
    },
    {
      "Description": "Percentage of TCP timeouts in the app nodes",
      "Query": "100 * avg(rate(node_netstat_TcpExt_TCPTimeouts{instance=~\"app.*\"}[1m])) / (avg(rate(node_netstat_TcpExt_TCPTimeouts{instance=~\"app.*\"}[1m])) + avg(node_netstat_Tcp_CurrEstab{instance=~\"app.*\"}))",
      "Threshold": 3,
      "MinIntervalSec": 60,
      "Alert": true
    }
  ]
},
```

The last section of the file defines, apart from the settings of the logs, which are irrelevant to the results of the tests, the rate at which the users are added or removed. This does affect the final result, since the login process is a computationally heavy one. Again, these values should have stayed the same for all tests, but as we executed the larger tests, we realized that they would have taken too long using the initial values. Thus, we had to increment them. All of `NumUsersInc`, `NumUsersDec` and `RestTimeSec` took values of 4 initially. For the larger tests, they had to be bumped to 8.

``` json
"NumUsersInc": 4,
"NumUsersDec": 4,
"RestTimeSec": 4,
```

###### `deployer.json`

This is the file containing the definition of the architecture to deploy in each test. As such, this file is the one with the more expected modifications among tests. We're going to skip most of the file contents here and focus on the interesting parts. As stated above, you can find the whole file in `common-deployer.json`.

The AMI used as the base of all instances in the deployment is `ami-003d3d03cfe1b0468`: an Ubuntu 22.04 LTS image.

``` json
"AWSAMI": "ami-003d3d03cfe1b0468",
```

The architecture of the server is defined with the `AppInstance*` fields, with which we specify:
- The number of app nodes: 1 for simple deployments, 2 or more for High-Availability deployments, where a proxy is automatically deployed as well.
- The specs of each app node: the instance type defines the number of cores, memory and network characteristics.

These two values define the horizontal and vertical scaling of the server to test, playing the biggest role (along with the DB specs) in the number of supported users. All tests used an instance type in the `c6i` family.

```json
"AppInstanceCount": 2,
"AppInstanceType": "c6i.xlarge",
```

There are similar values for the agent nodes; i.e., the nodes simulating the users and generating the load directed to the server. The instance type was `c6i.xlarge` for all tests, with which we can simulate up to 2000 users. Depending on the final number of users needed, tests modified the count of agent instances to cover them.

``` json
"AgentInstanceCount": 10,
"AgentInstanceType": "c6i.xlarge",
```

No tests in this first suite used ElasticSearch nor job servers. See the [Architecture](#architecture) for more information on this.

``` json
"ElasticSearchSettings": {
  "InstanceCount": 0,
  ...
},
"JobServerSettings": {
  "InstanceCount": 0,
  ...
},
```

Then we need to define the type of instance for the proxy, which is used automatically for deployments with more than one app node. We started using `m6i.4xlarge`, and then experimented with `m6in.4xlarge`, which incremented the network bandwidth. We did this trying to prove the hypothesis that the proxy network was the bottleneck in some of the tests. The hypothesis was proven to be false, so v2 will use `m6i.4xlarge` for each and every test.

``` json
"ProxyInstanceType": "m6i.4xlarge",
```

There are a couple of values that *need* to be defined as follows due to the dataset we used:
- `SiteURL` needs to be set to the hostname used in the permalinks present in the dataset's posts.
- `UsersFilePath` needs to point to a file containing the credentials of the users present in the dataset. This file, `users.txt`, can be found in this archive as well.

``` json
"SiteURL": "ltserver",
"UsersFilePath": "/home/ubuntu/ctassets/users.txt",
```

Now we get to the settings for the database. Here, as with the `AppInstance*` fields, we define the horizontal and vertical scaling of the database server. Again, as with the `AppInstance*` fields, the `TerraformDBSettings` section is the one playing the biggest role in the final number of supported users.

All tests used an instance type in the `r6g` family.

Note that we also need to set the `DBName` to `agnivaltdb` due to the database name in the dump used.

``` json
"TerraformDBSettings": {
  "InstanceCount": 2,
  "InstanceEngine": "aurora-postgresql",
  "InstanceType": "db.r6g.xlarge",
  "UserName": "mmuser",
  "Password": "mostest80098bigpass_",
  "EnablePerformanceInsights": false,
  "DBParameters": [],
  "ClusterIdentifier": "agm-ltcluster-15122023-6",
  "DBName": "agnivaltdb"
},
```

We also used an existing bucket that contains the files pointed out by the posts in the database dump. One needs to specify the Amazon credentials, that are redacted here.

``` json
"ExternalBucketSettings": {
  "AmazonS3AccessKeyId": "REDACTED",
  "AmazonS3SecretAccessKey": "REDACTED",
  "AmazonS3Bucket": "agm-ct-bucket-20230829-01",
  "AmazonS3PathPrefix": "",
  "AmazonS3Region": "us-east-1",
  "AmazonS3Endpoint": "s3.amazonaws.com",
  "AmazonS3SSL": true,
  "AmazonS3SignV2": false,
  "AmazonS3SSE": false
},
```

All tests were designed to stress the latest [ESR version](https://docs.mattermost.com/upgrade/extended-support-release.html) at the time of testing: v8.1. See more about this in the [Mattermost version](#mattermost-version) section.

The license used was an internal one used by developers for tests, but any Enterprise license would do.


``` json
"MattermostDownloadURL": "https://releases.mattermost.com/8.1.7/mattermost-8.1.7-linux-amd64.tar.gz",
"MattermostLicenseFile": "/home/ubuntu/licenses/prod/dev-enterprise.mattermost-license",
```

The version of the load-test tool was either:
- A custom build from commit `dcc95b8`.
- The released v1.12.0.

See the [Load-test tool version](#load-test-tool-version) section to know more about it.

``` json
"LoadTestDownloadURL": "file:///home/ubuntu/ctassets/mattermost-load-test-ng-v1.9.1-53-gdcc95b8-linux-amd64.tar.gz",
```

Finally, and due to the usage of v1.12.0, tests 1.1.x and 1.2.x used the following additional configuration, that allowed a finer configuration of the disk storage in the different instances, as well as finer configuration for the Pyroscope profiling. These settings do not affect the final results of the tests.

``` json
"StorageSizes": {
  "Agent": 10,
  "Proxy": 10,
  "App": 10,
  "Metrics": 100,
  "Job": 0,
  "ElasticSearch": 0
},
"PyroscopeSettings": {
  "EnableAppProfiling": true,
  "EnableAgentProfiling": false
}
```

#### Mattermost
##### Mattermost version

We used a version modified on top of `v8.1.0`, with the two following changes:

* [Fix panic in jobs/base_workers.go](https://github.com/mattermost/mattermost/pull/24678)
* [Fix potential read after write issue when loading license](https://github.com/mattermost/mattermost/pull/24524)

This is functionally equivalent to [`v8.1.7`](https://github.com/mattermost/mattermost/pull/24524), which can be used to reproduce these results.

##### Architecture

For this first version of the test, the architecture of the servers considered both:
- Single-node deployments, where a single instance was used as the server High Availability deployments 
- High Availability deployments, where two or more nodes were deployed in a cluster with a proxy node on front acting as the entry point and sharing the requests among all app nodes.

The deployment architecture omitted both of:

- [ElasticSearch](https://docs.mattermost.com/scale/elasticsearch.html). This means that all tests' servers relied in the database for searching. 
- [Job servers](https://docs.mattermost.com/scale/high-availability-cluster.html#job-server). This means that the tests did not stress data-intensive tasks like LDAP syncing or data retention.

All deployments have the database running in a different server, considering both:
- Single-node deployments.
- Multiple node deployments, with a writer instance and the rest acting as reader replicas.

##### License

All servers were executed with en Enterprise license.

#### Database

The database used for all tests was PostgreSQL v14.7 through Amazon Aurora instances.

Two parameters were modified through a custom parameter group:
- `random_page_cost` was set to 1.1
- `work_mem` was set to 32768

The data with which all tests start is the same: a PostgreSQL dump specially designed for these tests. You can download its gzipped version (18.7GB) [in our public S3 bucket](https://lt-public-data.s3.amazonaws.com/100M_710_withmemberships.sql.gz), but some interesting highlights:
- Posts count: ~100 million
- Users count: ~3000
- Teams count: 20
- Channels count: ~720000

The data was generated using the generative controller of the loda-test tool, simulating 5 consecutive batches of 600 users that generated the data. This generation created disjoint sets of channel membership, with each of the 5 sets of 600 users being members of different set of channels. This was later fixed by a post-processing of the data that added the users to channels in some of the other sets.

The distribution of channels per type is as follows:

| Type    | Count  |
|---------|--------|
| Public  | 21640  |
| Private | 50400  |
| Group   | 108233 |
| Direct  | 540264 |

Out of the channels attached to a team; i.e., private or public channels, but not direct or group messages, their distribution per team is as follows:

| Team # | Channel count |
|--------|---------------|
| 1      | 8296          |
| 2      | 8222          |
| 3      | 8127          |
| 4      | 8098          |
| 5      | 4661          |
| 6      | 4618          |
| 7      | 4549          |
| 8      | 4532          |
| 9      | 2933          |
| 10     | 2847          |
| 11     | 2832          |
| 12     | 2779          |
| 13     | 1676          |
| 14     | 1645          |
| 15     | 1628          |
| 16     | 1600          |
| 17     | 804           |
| 18     | 734           |
| 19     | 730           |
| 20     | 729           |

### Individual specifications

The tests differed mainly in the number and type of instances for both the application and the database nodes. The following table specifies each configuration:

| Test  | Number of app nodes | Type of app instance | Number of DB nodes | Type of DB instance |
|-------|---------------------|----------------------|--------------------|---------------------|
| 0.1   | 2                   | c6i.2xlarge          | 2                  | db.r5.2xlarge       |
| 0.2   | 2                   | m6i.2xlarge          | 2                  | db.r5.2xlarge       |
| 0.3   | 2                   | c6i.2xlarge          | 2                  | db.r6g.2xlarge      |
| 0.4   | 2                   | m6i.2xlarge          | 2                  | db.r6g.2xlarge      |
| 1.1   | 1                   | c6i.large            | 1                  | db.r6g.large        |
| 1.1.x | 1                   | c6i.xlarge           | 1                  | db.r6g.xlarge       |
| 1.2   | 2                   | c6i.large            | 2                  | db.r6g.large        |
| 1.2.x | 2                   | c6i.xlarge           | 2                  | db.r6g.xlarge       |
| 1.3   | 2                   | c6i.2xlarge          | 2                  | db.r6g.2xlarge      |
| 1.4   | 5                   | c6i.2xlarge          | 5                  | db.r6g.2xlarge      |
| 2.1.a | 5                   | c6i.4xlarge          | 5                  | db.r6g.4xlarge      |
| 2.1.b | 4                   | c6i.4xlarge          | 5                  | db.r6g.4xlarge      |
| 2.1.d | 6                   | c6i.4xlarge          | 5                  | db.r6g.4xlarge      |

Although unplanned, the coordinator metrics ended up being different for some of the tests as well. These metrics were only applicable to tests in phases 1 and 2, since tests in phase 0 ran bounded tests, that have no metrics. The following table summarizes which metrics were used in each of those tests:

| Query                                          | 1.1 | 1.1.x | 1.2 | 1.2.x | 1.3 | 1.4 | 2.1.a | 2.1.b | 2.1.d |
|------------------------------------------------|-----|-------|-----|-------|-----|-----|-------|-------|-------|
| "Percentage of HTTP 5xx server errors"         | x   | x     | x   | x     | x   | x   | x     | x     | x     |
| "Average client request duration"              | x   | x     | x   | x     | x   | x   | x     | x     | x     |
| "99th percentile of client request duration"   | x   | x     | x   | x     | x   | x   | x     | x     | x     |
| "Percentage of HTTP 5xx client errors"         | x   | x     | x   | x     | x   | x   | x     | x     | x     |
| "Percentage of client timeouts"                | x   | x     | x   | x     | x   | x   | x     | x     | x     |
| "CPU utilization"                              | x   | x     | x   | x     | x   | x   | x     | x     | x     |
| "Memory utilization"                           |     | x     |     | x     |     |     |       |       |       |
| "Percentage of TCP timeouts in the proxy node" |     | x     |     | x     |     |     |       |       |       |
| "Percentage of TCP timeouts in the app nodes"  |     | x     |     | x     |     |     |       |       |       |

Find the exact configuration files for each test under `config/` inside the corresponding directories named after the test number.

## Test results

For each test configured as specified above, three independent runs were executed so we could average the final reported number of supported users. The results of each test, ordered by this average number, can be seen in the following table:

| Test  | Number of app nodes | Type of app instance | Number of DB nodes | Type of DB instance | Number of supported users |
|-------|---------------------|----------------------|--------------------|---------------------|---------------------------|
| 1.1   | 1                   | c6i.large            | 1                  | db.r6g.large        | 100                       |
| 1.2   | 2                   | c6i.large            | 2                  | db.r6g.large        | 1000                      |
| 1.1.x | 1                   | c6i.xlarge           | 1                  | db.r6g.xlarge       | 8000                      |
| 1.2.x | 2                   | c6i.xlarge           | 2                  | db.r6g.xlarge       | 15000                     |
| 1.3   | 2                   | c6i.2xlarge          | 2                  | db.r6g.2xlarge      | 25000                     |
| 1.4   | 5                   | c6i.2xlarge          | 5                  | db.r6g.2xlarge      | 50000                     |
| 2.1.b | 4                   | c6i.4xlarge          | 5                  | db.r6g.4xlarge      | 70000                     |
| 2.1.a | 5                   | c6i.4xlarge          | 5                  | db.r6g.4xlarge      | 79000                     |
| 2.1.d | 6                   | c6i.4xlarge          | 5                  | db.r6g.4xlarge      | 88000                     |

Individual results for each run, as well as additional information (Raintank snapshots of the Grafana dashboards and certain profile data) for some of the tests, can be found under `results/` inside the corresponding directories named after the test number.
