# Report of Ceiling Tests v2

This document describes the specifications of the second version of the ceiling tests, executed between July 18, 2024 and August 7, 2024, as well as its results.

Along this report, you can also find the specifics of each test run under its corresponding directory. There, you will find:
- A `config` directory, containing the specific configuration files used for the test run execution.
- An `*.out.gz` file, containing the metrics gathered during the test run execution.
- A `results.txt` file, containing:
  - The time the test run started and finished
  - The reported number of supported users at the end of the test run
  - Snapshots of the main Grafana dashboards covering the test run

## Goals

The goals of this document are:

1. Provide a detailed report of the results of the tests.
2. Provide a detailed description of the specification of the tests, so that:
    1. The tests are reproducible at any time
    2. The results of the tests are properly contextualized

## Background reading

1. [Ceiling Tests v2](https://mattermost.atlassian.net/wiki/spaces/XYZ/pages/2809004081/Ceiling+Tests+V2), the document used to plan these tests.
2. [Report of Ceiling Tests v1](../v1/README.md), the document with the results of the first version of these tests.

## General description of test specifications

The tests were executed with a common specification, aiming to only modify the architecture for the server and the database.
- From test to test, only the number and type of instances used for the server, database and Elasticsearch changed.
- We used a fixed family of instances for the server, `c7i`, and a fixed family of instances for the database, `db.r7g`.
- We used a fixed instance type for Elasticsearch, `r6g.xlarge.search`, and only tested with either 0 or 2 nodes.
- The vertical scaling of both the app and database instances is synced, using corresponding instances in both.

This is better explained with the nomenclature that we used, which follows the pattern `FAMILY.ABC`, where:

- `FAMILY` is one of `L`, `XL`, `2XL` or `4XL`, corresponding to the type of both the app and DB nodes.
- `A` is the number of app nodes
- `B` is the number of DB nodes
- `C` is the number of ES nodes

For example, the test `4XL.662` uses 6 nodes for the app, 6 nodes for the database and 2 nodes for Elasticsearch, using the `4XL` type of instances for the app and database; i.e., `c7i.4xlarge` for the app and `db.r7g.4xlarge` for the database.

Each test was executed three times with identical setups.

For a more detailed description of the test specifications, see [Test specifications](#test-specifications).

## Results

### Test results

The results in the following tables are categorized by the type of instance used in both the application and database node, as explained above: `*.large`, `*.xlarge`, `*.2xlarge` and `*.4xlarge`. For each test, we list:
- The type of instance for the proxy node
- The number and type of application instances
- The number and type of database instances
- Whether Elasticsearch was enabled or not
- The reported number of supported users for that architecture. This is computed as the average of reported number of supported users for each of the three runs.
- The main bottleneck perceived when analyzing the results. In parenthesis, secondary bottlenecks are listed.

The login rate is 8 users every 2 seconds for all tests.

#### Family L

|           | **Proxy type** | **App nodes**  | **DB nodes**       | **ES enabled** | **Supported users** | **Bottleneck** |
|-----------|----------------|----------------|--------------------|----------------|---------------------|----------------|
| **L.110** | `m7i.4xlarge`  | 1 x`c7i.large` | 1 x `db.r7g.large` | No             | **217**             | DB             |
| **L.220** | `m7i.4xlarge`  | 2 x`c7i.large` | 2 x `db.r7g.large` | No             | **231**             | DB             |
| **L.222** | `m7i.4xlarge`  | 2 x`c7i.large` | 2 x `db.r7g.large` | yes            | **2221**            | DB             |

#### Family XL

|            | **Proxy type** | **App nodes**    | **DB nodes**        | **ES** | **Supported users** | **Bottleneck** |
|------------|----------------|------------------|---------------------|--------|---------------------|----------------|
| **XL.220** | `m7i.4xlarge`  | 2 x `c7i.xlarge` | 2 x `db.r7g.xlarge` | No     | **17206**           | CPU            |
| **XL.222** | `m7i.4xlarge`  | 2 x `c7i.xlarge` | 2 x `db.r7g.xlarge` | Yes    | **17128**           | CPU/RAM        |

#### Family 2XL

|             | **Proxy type** | **App nodes**     | **DB nodes**         | **ES** | **Supported users** | **Bottleneck** |
|-------------|----------------|-------------------|----------------------|--------|---------------------|----------------|
| **2XL.220** | `m7i.4xlarge`  | 2 x `c7i.2xlarge` | 2 x `db.r7g.2xlarge` | No     | **29504**           | CPU            |
| **2XL.222** | `m7i.4xlarge`  | 2 x `c7i.2xlarge` | 2 x `db.r7g.2xlarge` | Yes    | **30661**           | CPU            |
| **2XL.330** | `m7i.4xlarge`  | 3 x `c7i.2xlarge` | 3 x `db.r7g.2xlarge` | No     | **43371**           | CPU            |
| **2XL.440** | `m7i.4xlarge`  | 4 x `c7i.2xlarge` | 4 x `db.r7g.2xlarge` | No     | **51572**           | CPU            |
| **2XL.550** | `m7i.4xlarge`  | 5 x `c7i.2xlarge` | 5 x `db.r7g.2xlarge` | No     | **61461**           | CPU            |
| **2XL.552** | `m7i.4xlarge`  | 5 x `c7i.2xlarge` | 5 x `db.r7g.2xlarge` | Yes    | **58851**           | CPU (ES CPU)   |

#### Family 4XL

|             | **Proxy type** | **App nodes**     | **DB nodes**         | **ES** | **Supported users** | **Bottleneck**                 |
|-------------|----------------|-------------------|----------------------|--------|---------------------|--------------------------------|
| **4XL.440** | `m6in.8xlarge` | 4 x `c7i.4xlarge` | 4 x `db.r7g.4xlarge` | No     | **80573**           | CPU                            |
| **4XL.442** | `m6in.8xlarge` | 4 x `c7i.4xlarge` | 4 x `db.r7g.4xlarge` | Yes    | **80532**           | CPU (ES CPU)                   |
| **4XL.550** | `m6in.8xlarge` | 5 x `c7i.4xlarge` | 5 x `db.r7g.4xlarge` | No     | **93808**           | CPU                            |
| **4XL.552** | `m6in.8xlarge` | 5 x `c7i.4xlarge` | 5 x `db.r7g.4xlarge` | Yes    | **91571**           | CPU (network, cluster, ES CPU) |
| **4XL.662** | `m6in.8xlarge` | 6 x `c7i.4xlarge` | 6 x `db.r7g.4xlarge` | Yes    | **100926**          | CPU (network, cluster, ES CPU) |


### Insights

Apart from the raw numbers in the previous table, running these tests revealed some key points:

- The main bottleneck we see across most of the tests is application CPU.
- Elasticsearch: Ceiling Tests v2 is the first time we add Elasticsearch to a batch of performance tests in a structured way. We learned some interesting things:
  - Elasticsearch improved performance by an order of magnitude in the lower-end tests, when the main bottleneck was the DB. This proves that Elasticsearch is the best solution when the database is struggling.
  - However, ES did absolutely nothing in the high-end tests, that were always bound by CPU.
  - Hence, for Elasticsearch to improve stuff, the bottleneck *has to be* in the database.
  - We used 2 nodes with a fixed instance type for all tests. The CPU of the instances maxed out starting with ~30k users. Thus, the potential improvement attributed to Elasticsearch is actually lost in tests with more than 30k users. We need to scale it, either vertically or horizontally, along with the expected number of supported users to see an improvement. We need more tests to provide a solid answer to this.
- Network:
  - High bandwidth is definitely a bottleneck in higher scales. This happens in micro-bursts, not in the average usage of the network, which comfortably sits below the thresholds set by the instance types used in the tests. However, due to usage peaks, we had to bump the originally planned proxy instance type for it to be able to handle the high load.
  - Intra-cluster communication started to show some signs of deterioration after ~90k with 5 app nodes. It isn't a bottleneck at all for now, but it may be soon. Increasing the app types or even the number of app nodes may help, because the bottleneck here was network and the hardware wasn't able to cope with it. We need more tests to provide a solid answer to this.

Based on these learnings, we have a series of planned improvements:

- Immediate steps:
  - Add `ethtool` stats to the Grafana dashboards ([MM-59994](https://mattermost.atlassian.net/browse/MM-59994)): this will help us monitor not only the average bandwidth used, but the potential micro-bursts resulting in dropped packets.
  - Use network-optimized instances (the *n.* series) for both proxy and app nodes: this will help remove the bottleneck in the network.
  - Surface AWS internal metrics via Cloudwatch ([MM-60020](https://mattermost.atlassian.net/browse/MM-60020)): this will help us monitor AWS-controlled instances, like the database, Elasticsearch or Redis.
- Big steps ahead:
  - Improve intra-cluster communication ([MM-58564](https://mattermost.atlassian.net/browse/MM-58564)): this will be needed as we scale further, although it is not a bottleneck right now.
  - Multi-proxy setups: scaling further with only one entry point seems to be unsustainable, so we need to investigate setups with more than one proxy.
  - In-depth investigation on CPU: all tests in the higher-end are bottlenecked by application CPU, so we need to investigate the causes and potential solutions.


## Test specifications
### Load-test tool

All tests were executed using [the load-test tool](https://github.com/mattermost/mattermost-load-test-ng), a custom-built framework uniquely designed for stress-testing Mattermost servers.

All tests were *unbounded*; i.e., tests that estimate how much load a Mattermost server can support, according to some predefined metrics. These tests report the maximum number of users supported by the target system while maintaining all metrics under the specified thresholds. Learn more about the nature of such tests in [the tool documentation](https://github.com/mattermost/mattermost-load-test-ng/blob/042ef8673cea46248a540cbc682ccba8758cb1fd/docs/faq.md#what-is-an-unbounded-load-test).

There are two important variables in how the tool is configured that greatly affect the results of tests:
- The actions executed by each simulated user, and their frequencies.
- The coordinator metrics that define what we understand by a healthy system.

Each of these are covered in the [Action frequencies](#action-frequencies) and [Coordinator metrics](#coordinator-metrics) sections below.
  
#### Load-test tool version

When talking about the version used in the load-test tool, one needs to specify two different things:
- The version used by the agents; i.e., the one specified in the `LoadTestDownloadURL` field in the `deployer.json` field.
- The version used to deploy; i.e., the commit your repo is in when you launch `go run ./cmd/ltctl deployment create`.

The first one is straightforward: agents used [`v1.18.0`](https://github.com/mattermost/mattermost-load-test-ng/releases/tag/v1.18.0).

For the second one, one needs to use branch `ceiling-tests-v2`, commit [`042ef86`](https://github.com/mattermost/mattermost-load-test-ng/commit/042ef8673cea46248a540cbc682ccba8758cb1fd). It is essentially [`v1.18.0`](https://github.com/mattermost/mattermost-load-test-ng/releases/tag/v1.18.0), but with two additional modifications:
- [A fix of a bug](https://github.com/mattermost/mattermost-load-test-ng/pull/778) that prevented the correct configuration of `nginx`.
- [An ad-hoc change](https://github.com/mattermost/mattermost-load-test-ng/commit/042ef8673cea46248a540cbc682ccba8758cb1fd) to bump the metrics instance, which was needed for the large amount of datapoints collected.

#### Action frequencies

Each test simulates a number of users, who behave similar to a real user by executing a series of actions with given relative frequencies.

These frequencies were computed to match an average user in on our largest customer in Cloud, during a 2-hour time window where the number of concurrently connected devices were at its highest. The actual definition of the frequencies can be found [in the code](https://github.com/mattermost/mattermost-load-test-ng/blob/042ef8673cea46248a540cbc682ccba8758cb1fd/loadtest/control/simulcontroller/controller.go#L19-L209), and the procedure of how these were computed in the [Action frequencies review](https://docs.google.com/document/d/1A4gRuJBymamP5cTgYkI-CJV3n4Sj4nF07Zn44seuaks/edit#) document. The following table shows the actions used in these tests sorted by relative frequency:

| Action                           | Freq   |
|----------------------------------|--------|
| SwitchChannel                    | 6.5219 |
| ScrollChannel                    | 1.9873 |
| UnreadCheck                      | 1      |
| CreatePost                       | 1      |
| OpenDirectOrGroupChannel         | 0.9843 |
| ViewGlobalThreads                | 0.6023 |
| UpdateThreadRead                 | 0.3236 |
| ClickPermalink                   | 0.3    |
| ViewThread                       | 0.2841 |
| ReconnectWebSocket               | 0.144  |
| AddReaction                      | 0.1306 |
| EditPost                         | 0.0400 |
| SearchUsers                      | 0.0320 |
| ClickUserProfile                 | 0.03   |
| SearchPosts                      | 0.0218 |
| SearchGroupChannels              | 0.0204 |
| SearchChannels                   | 0.0150 |
| CreateDirectChannel              | 0.0055 |
| UnfollowThread                   | 0.0050 |
| JoinChannel                      | 0.0049 |
| DeletePost                       | 0.0049 |
| UpdateSidebarCategory            | 0.0040 |
| CreateGroupChannel               | 0.0029 |
| UpdateCustomStatus               | 0.0028 |
| RemoveCustomStatus               | 0.0026 |
| FullReload                       | 0.0008 |
| LogoutLogin                      | 0.0006 |
| CreatePostReminder               | 0.0005 |
| FollowThread                     | 0.0005 |
| CreatePrivateChannel             | 0.0002 |
| SwitchTeam                       | 0.0001 |
| CreateSidebarCategory            | 0.0001 |
| CreatePublicChannel              | 0.0001 |
| MarkAllThreadsInTeamAsRead       | 0.0001 |
| CreateAclPost                    | 0.0001 |
| AckToPost                        | 0.0001 |
| CreatePersistentNotificationPost | 0.0001 |
| GenerateUserReport               | 0.0001 |
  
#### Coordinator metrics

The way an unbounded test works is by connection new users to the server while the system is healthy. But how do we define when a system is healthy? We do that through the coordinator metrics: a series of measurements of different system characteristics that are expected to be under a configured threshold to consider a system to be healthy. 

Whenever any of these metrics crosses its specified threshold, the coordinator removes 8 users to try to keep the system healthy. When the system reached an equilibrium point, the test finishes and the average of users connected during the last 30 minutes is reported as the number of supported users for this test.

The coordinator metrics used throughout all the tests are the following:

| Description                                    | PromQL query                                                                                                                                    | Threshold |
|------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|-----------|
| HTTP 5xx server errors (%)                     | `(sum(rate(mattermost_api_time_count{status_code=~"5.."}[1m]))/sum(rate(mattermost_api_time_count[1m])))*100`                                   | 0.025     |
| Average client request duration (s)            | `sum(rate(loadtest_http_request_time_sum[1m]))/sum(rate(loadtest_http_request_time_count[1m]))`                                                 | 0.1       |
| 99th percentile of client request duration (s) | `histogram_quantile(0.99, sum(rate(loadtest_http_request_time_bucket[1m])) by (le))`                                                            | 2         |
| HTTP 5xx client errors (%)                     | `(sum(rate(loadtest_http_errors_total{status_code=~"5.."}[1m]))/sum(rate(loadtest_http_request_time_count[1m])))*100`                           | 0.025     |
| Client timeouts (%)                            | `(sum(rate(loadtest_http_timeouts_total[1m]))/sum(rate(loadtest_http_request_time_count[1m]))) * 100`                                           | 0.025     |
| CPU utilization - Average of app nodes (%)     | `100 - 100 * (avg(irate(node_cpu_seconds_total{instance=~"app.*",mode="idle"}[5m])))`                                                           | 85        |
| Memory utilization - Average of app nodes (%)  | `100 - 100 * avg(node_memory_MemAvailable_bytes{instance=~"app.*"} / node_memory_MemTotal_bytes{instance=~"app.*"})`                            | 85        |
| TCP retransmissions in the app nodes (%)       | `(avg(rate(node_netstat_Tcp_RetransSegs{instance=~"app.*"}[1m])) / avg(rate(node_netstat_Tcp_OutSegs{instance=~"app.*"}[1m]))) * 100`           | 1         |
| TCP retransmissions in the proxy node (%)      | `(avg(rate(node_netstat_Tcp_RetransSegs{instance=~"proxy:9100"}[1m])) / avg(rate(node_netstat_Tcp_OutSegs{instance=~"proxy:9100"}[1m]))) * 100` | 1         |


#### Configuration

There are multiple files to configure the tests, from the nature of the simulation to the specific behaviour of the users or the architecture of the server to test. However, most of that configuration was kept as default, modifying only the three following files:
- config.json
- coordinator.json
- deployer.json

The following subsections go through each of them, highlighting the interesting parts for the definition of the tests. For the complete contents of the files, check out the `common-config.json`, `common-coordinator.json` and `common-deployer.json` files. 

##### `config.json`

The first section that deviates from the defaults is `UserControllerConfiguration`: it states that we are running a simulative test, and it contains the `RatesDistribution` setting, which defines how fast the users perform their actions in the simulation. Its value, 5.4, was empirically chosen to match the frequency of the `createPost` action in the reference server when running the same number of users connected during the reference time window.

```json
"UserControllerConfiguration": {
  "Type": "simulative",
  "RatesDistribution": [
    {
      "Rate": 5.4,
      "Percentage": 1
    }
  ],
}
```

The `UsersConfiguration` section configures each agent to control 2000 users. This value is the *de facto* standard for the chosen instance type for each agent (see the [`deployer.json`](#deployerjson) section for more information):

``` json
"UsersConfiguration": {
  "MaxActiveUsers": 2000,
}
```

##### `coordinator.json`

This file contains configuration for three main aspects:
- How many users the test can simulate in total.
- The metrics that define what a healthy system means.
- How fast the users are added when the system is healthy and can accept new connections.

The first section, `ClusterConfig`, was mainly the same for all tests, although the maximum number of users had to be increased for the larger tests. Thus, `ClusterConfig.MaxActiveUsers`'s value varied between 4000 for the lower-end tests up to 150000 for the largest ones.

``` json
"ClusterConfig": {
  "MaxActiveUsers": 20000
}
```

The second section, `MonitorConfig`, is the one defining the coordinator metrics. Read the [Coordinator metrics](#coordinator-metrics) section to see a list of all the metrics used and a description of what they mean.

The last section of the file defines the rate at which the users are added or removed. This does affect the final result, since the login process is a computationally heavy one. We use a login/logoff rate of 8 users every 2 seconds. This means that every 2 seconds, the coordinator checks the specified metrics: if all of them are below their corresponding thresholds, the coordinator adds 8 new users; if any of them are above the threshold, the coordinator removes 8 users.

``` json
"NumUsersInc": 8,
"NumUsersDec": 8,
"RestTimeSec": 2,
```

##### `deployer.json`

This is the file containing the definition of the architecture to deploy in each test. As such, this file is the one with the more expected modifications among tests. We're going to skip most of the file contents here and focus on the interesting parts. As stated above, you can find the whole file in `common-deployer.json`.

The AMI used as the base of all instances in the deployment is `ami-003d3d03cfe1b0468`: an Ubuntu 22.04 LTS image.

``` json
"AWSAMI": "ami-003d3d03cfe1b0468",
```

The architecture of the server is defined with the `AppInstance*` fields, with which we specify:
- The number of app nodes: 1 for simple deployments, 2 or more for High-Availability deployments, where a proxy is automatically deployed as well.
- The specs of each app node: the instance type defines the number of cores, memory and network characteristics.

These two values define the horizontal and vertical scaling of the server to test, playing the biggest role (along with the DB specs) in the number of supported users. All tests used an instance type in the `c7i` family.

```json
"AppInstanceCount": 2,
"AppInstanceType": "c7i.xlarge",
```

There are similar values for the agent nodes; i.e., the nodes simulating the users and generating the load directed to the server. The instance type was `c7i.xlarge` for all tests, with which we can simulate up to 2000 users. Depending on the final number of users needed, tests modified the count of agent instances to cover them.

``` json
"AgentInstanceCount": 10,
"AgentInstanceType": "c7i.xlarge",
```

Elasticsearch was deployed for a subset of the tests. The number of instances remained constant for all tests with it enabled, as well as the instance type. We used ElasticSearch v7.10 and a prepared snapshot of the database used in all tests. This way, all tests that used Elasticsearch started with an already populated cluster that indexes the database.

```json
"ElasticSearchSettings": {
  "InstanceCount": 2,
  "InstanceType": "r6g.xlarge.search",
  "VpcID": "vpc-0a18f1a4cdf62d256",
  "Version": "Elasticsearch_7.10",
  "CreateRole": false,
  "SnapshotRepository": "lt-opensearch-100m-v9.5",
  "SnapshotName": "lt-100m-v9.5-index",
  "RestoreTimeoutMinutes": 45,
  "ClusterTimeoutMinutes": 45
}
```

No tests in in this batch used job servers. See the [Architecture](#architecture) for more information on this.

``` json
"JobServerSettings": {
  "InstanceCount": 0,
},
```

Then we need to define the type of instance for the proxy, which is used automatically for deployments with more than one app node. We used `m7i.4xlarge` for the smaller tests and `m6in.8xlarge` for the larger ones, since microbursts in network usage were increasing the TCP retransmissions.

``` json
"ProxyInstanceType": "m6i.4xlarge",
```

There are a couple of values that *need* to be defined as follows due to the dataset we used:
- `SiteURL` needs to be set to the hostname used in the permalinks present in the dataset's posts.
- `UsersFilePath` needs to point to a file containing the credentials of the users present in the dataset. This file, `users.txt`, can be found in this archive as well.

``` json
"SiteURL": "ltserver",
"UsersFilePath": "/home/ubuntu/ctassets/users3.txt",
```

Now we get to the settings for the database. Here, as with the `AppInstance*` fields, we define the horizontal and vertical scaling of the database server. Again, as with the `AppInstance*` fields, the `TerraformDBSettings` section is the one playing the biggest role in the final number of supported users.

All tests used an instance type in the `db.r7g` family.

Note that we also need to set the `DBName` to `ltdb` due to the database name in the dump used.

As explained in [Database](#database), we set two custom parameters: `random_page_cost` and `work_mem`. The `ClusterIdentifier` field is set to a restored backup of the 100M database.

``` json
"TerraformDBSettings": {
  "InstanceCount": 6,
  "InstanceEngine": "aurora-postgresql",
  "InstanceType": "db.r7g.4xlarge",
  "UserName": "mmuser",
  "Password": "mostest80098bigpass_",
  "EnablePerformanceInsights": true,
  "DBParameters": [
    {
      "Name": "random_page_cost",
      "Value": "1.1",
      "ApplyMethod": "immediate"
    },
    {
      "Name": "work_mem",
      "Value": "32768",
      "ApplyMethod": "immediate"
    }
  ],
  "ClusterIdentifier": "agm-ct4xl662-6",
  "DBName": "ltdb"
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

All tests were designed to stress the latest [ESR version](https://docs.mattermost.com/upgrade/extended-support-release.html) at the time of testing: v9.5.7.

The license used was an internal one used by developers for tests, but any Enterprise license would do.

``` json
"MattermostDownloadURL": "https://releases.mattermost.com/8.1.7/mattermost-8.1.7-linux-amd64.tar.gz",
"MattermostLicenseFile": "/home/ubuntu/licenses/lt_enterprise-500K.mattermost-license",
```

The version of the load-test tool used by agents was v1.18.0. See the [Load-test tool version](#load-test-tool-version) section to know more about it.

``` json
"LoadTestDownloadURL": "https://github.com/mattermost/mattermost-load-test-ng/releases/download/v1.18.0/mattermost-load-test-ng-v1.18.0-linux-amd64.tar.gz",
```

The final settings do not affect the results of the tests, but are needed to allow for disk usage for each type of instance. The `Metrics` and `ElasticSearch` disks were modified for different tests, ranging from 50 to 200GiB. Pyroscope's profiling for agents was disabled for the larger tests, since it created large amounts of data:

``` json
"StorageSizes": {
  "Agent": 10,
  "Proxy": 10,
  "App": 10,
  "Metrics": 200,
  "ElasticSearch": 200
},
"PyroscopeSettings": {
  "EnableAppProfiling": true,
  "EnableAgentProfiling": false
}
```

### Mattermost
#### Mattermost version

The tested version of Mattermost was [v9.5.7](https://github.com/mattermost/mattermost/releases/tag/v9.5.7).

#### Architecture

- Application:
  - The first test use a single-node deployment.
  - All other tests use High Availability deployments, with two or more application nodes deployed in a cluster with a proxy node on front acting as the entry point and sharing the requests among all app nodes. 
- Elasticsearch: Tests with Elasticsearch enabled always used 2 instances of the same instance type.
- Job servers; the deployment architecture omitted [job servers](https://docs.mattermost.com/scale/high-availability-cluster.html#job-server). Tests did not stress data-intensive tasks like LDAP syncing or data retention either.
- TLS: tests are only stressing HTTP traffic, HTTPS is not supported by the tool at this moment.
- Database: All deployments have the database running in a different server, considering both:
  - Single-node DB deployments.
  - Multiple node DB deployments, with a writer instance and the rest acting as reader replicas.

#### Proxy

All deployments with more than one app node had a proxy acting as a load balancer:
- Specs: the proxy ran in an `m7i.4xlarge` instance for the lower-end tests and in an `m7i.8xlarge` instance for the higher-end ones.
- Version: the proxy ran `nginx v1.27.1`.
- Configuration: the proxy was configured with the following settings:

```
> cat /etc/nginx/nginx.conf

user www-data;
worker_processes auto;
worker_rlimit_nofile 100000;
pid /run/nginx.pid;
include /etc/nginx/modules-enabled/*.conf;

events {
  worker_connections 20000;
  use epoll;
}

http {
  map $status $loggable {
    ~^[23] 0;
    default 1;
  }

  sendfile on;
  tcp_nopush on;
  tcp_nodelay off;
  keepalive_timeout 75s;
  keepalive_requests 16384;
  types_hash_max_size 2048;
  include /etc/nginx/mime.types;
  default_type application/octet-stream;
  ssl_prefer_server_ciphers on;
  access_log /var/log/nginx/access.log combined if=$loggable;
  error_log /var/log/nginx/error.log;
  gzip on;
  include /etc/nginx/sites-enabled/*;
}
```

Note that the `upstream backend` directive below is dynamically populated with the IPs of all app nodes:

```
> cat /etc/nginx/sites-available/mattermost

upstream backend {
  server 172.27.205.186:8065 max_fails=0;
  server 172.27.213.167:8065 max_fails=0;

  keepalive 256;
}

proxy_cache_path /var/cache/nginx levels=1:2 keys_zone=mattermost_cache:10m max_size=3g inactive=60m use_temp_path=off;

server {
  listen 80 reuseport;
  server_name _;

  location ~ /api/v[0-9]+/(users/)?websocket$ {
    proxy_set_header Upgrade $http_upgrade;
    proxy_set_header Connection "upgrade";
    include /etc/nginx/snippets/proxy.conf;
  }

  location ~ /api/v[0-9]+/users/[a-z0-9]+/image$ {
    proxy_set_header Connection "";
    include /etc/nginx/snippets/proxy.conf;
    include /etc/nginx/snippets/cache.conf;
    proxy_ignore_headers Cache-Control Expires;
    proxy_cache_valid 200 24h;
  }

  location / {
    proxy_set_header Connection "";
    include /etc/nginx/snippets/proxy.conf;
    include /etc/nginx/snippets/cache.conf;
  }
}
```

```
> cat /etc/nginx/snippets/cache.conf

proxy_cache mattermost_cache;
proxy_cache_revalidate on;
proxy_cache_min_uses 2;
proxy_cache_use_stale timeout;
proxy_cache_lock on;
```

```
> cat /etc/nginx/snippets/proxy.conf

client_max_body_size 50M;
proxy_set_header Host $http_host;
proxy_set_header X-Real-IP $remote_addr;
proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
proxy_set_header X-Forwarded-Proto $scheme;
proxy_set_header X-Frame-Options SAMEORIGIN;
proxy_buffers 256 16k;
proxy_buffer_size 16k;
client_body_timeout 60s;
send_timeout        300s;
lingering_timeout   5s;
proxy_connect_timeout   30s;
proxy_send_timeout      90s;
proxy_read_timeout      90s;
proxy_http_version 1.1;
proxy_pass http://backend;
```

#### License

All servers were executed with en Enterprise license.

### Database

The database used for all tests was PostgreSQL v14.7 through Amazon Aurora instances.

Two parameters were modified through a custom parameter group:
- `random_page_cost` was set to 1.1
- `work_mem` was set to 32768

The data with which all tests start is the same: a PostgreSQL dump specially designed for these tests. You can download its gzipped version (18.7GB) [in our public S3 bucket](https://lt-public-data.s3.amazonaws.com/100M_710_withmemberships.sql.gz), but some interesting highlights:
- Posts count: ~100 million
- Users count: ~3000
- Teams count: 20
- Channels count: ~720000

The data was generated using the generative controller of the load-test tool, simulating 5 consecutive batches of 600 users that generated the data. This generation created disjoint sets of channel membership, with each of the 5 sets of 600 users being members of different set of channels. This was later fixed by a post-processing of the data that added the users to channels in some of the other sets.

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

