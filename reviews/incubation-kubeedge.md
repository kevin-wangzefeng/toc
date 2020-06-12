# KubeEdge proposal for CNCF Incubation

## Table of Contents



## Background
- [KubeEdge Sandbox Proposal](https://github.com/cncf/toc/blob/master/proposals/sandbox/kubeedge.adoc)
- [Project Review Proposal](https://github.com/cncf/toc/pull/440)
- [Original CNCF TOC meeting slides](https://docs.google.com/presentation/d/1e1ahun91Abn2xvX7Z8PVgGBz6c7Q7iO027XVzVuffDg/edit#slide=id.g25ca91f87f_0_0)


[KubeEdge](https://kubeedge.io/en/) is an open source system for extending native containerized application orchestration capabilities to hosts at Edge. It's built upon kubernetes and provides fundamental infrastructure support for network, application deployment and metadata synchronization between cloud and edge.

It aims to resolve three major challenges for edge computing: network reliability and bandwidth limit between cloud and edge, resource constraint at edge, highly distributed and heterogeneous device management.

**KubeEdge provides:**
1. Seamless Cloud-Edge Communication for both metadata and data
2. Edge Autonomy: Autonomous operation of Edge even during disconnection from cloud.
3. Low Resource Ready: KubeEdge can work in constrained resource situations (low memory, low bandwidth, low compute)
4. Simplified Device Communication: Easy communication between application and devices for IOT and IIOT

**KubeEdge was accepted as a CNCF Sandbox project on Mar 18, 2019.**
- [KubeEdge Sandbox Proposal](https://github.com/cncf/toc/blob/master/proposals/sandbox/kubeedge.adoc)
- [Original CNCF TOC meeting slides](https://docs.google.com/presentation/d/1e1ahun91Abn2xvX7Z8PVgGBz6c7Q7iO027XVzVuffDg/edit#slide=id.g25ca91f87f_0_0)


**Highlights of Last Year**
- Moved to 1.0
- 1400+ commits; 2400+ stars; 600+ forks; 300+ contributors
- 25+ Contributing organizations
- 5 User Adoptions and more under discussions
- Key Features Added: Device Management at Edge, Bluetooth Device Mapper, containerd support, QUIC as alternative to websocket, EdgeMesh, EdgeSite, CSI at Edge, Auto Registration of Edge Nodes, Device CRD Validation, Reliable Message delivery to Cloud




      Cortex was presented at the [CNCF TOC meeting on 6/5/2018](https://docs.google.com/presentation/d/190oIFgujktVYxWZLhLYN4q8p9dtQYoe4sxHgn4deBSI/edit#slide=id.g25ca91f87f_0_0). We’ve grown a lot since then and the project is a lot more active and mature now.

      Notable improvements in the last year include:
      * An easy to use single process version for people to test things out.
      * Queries are now much faster (up to 10x).
      * We now use a lot less disk space.
      * Cortex is now much more stable and easier to run, with more improvements on their way.
      * Our alerting and recording rule layer is now horizontally scalable.

      Further, a lot of the work in Cortex also involved improvements in upstream Prometheus and small subset include:
      * https://github.com/prometheus/prometheus/pull/4588
      * https://github.com/prometheus/prometheus/pull/5707
      * https://github.com/prometheus/tsdb/pull/642
      * https://github.com/prometheus/prometheus/pull/5316
      * https://github.com/prometheus/prometheus/pull/5131

## Alignment with Cloud Native

KubeEdge falls in the scope of [CNCF Runtime SIG](https://github.com/cncf/sig-runtime).

**KubeEdge targets on:**
  - building an open edge computing platform with cloud native technologies
  - helping users extending their business architecture, applications, services, etc. from cloud to edge in same experience
  - implementing extensible architecture based on Kubernetes
  - integration with CNCF projects, including (but not limited to) containerd, cri-o, Prometheus, Envoy, etc.
  - seamless development, deployment and run complex workloads at edge with optimized resources


## Incubation State Requirements

1. _Document that it is being used successfully in production by at least three independent end users which, in the TOC’s judgement, are of adequate quality and scope._

We have the list of public adopters in the repo, some notable users include:

* [Electronic Arts](https://www.ea.com/), is using Cortex for scaling their Prometheus servers.
* [DigitalOcean](https://www.digitalocean.com/), is using Cortex for scaling their Prometheus servers.
* [GoJek](https://www.gojek.com/), is using Cortex to build lens, the unified internal monitoring platform for all the services in its fleet.
* [Grafana Labs](https://www.grafana.com/), uses Cortex to run a commercial hosted Prometheus service.
* [Mayadata](https://www.mayadata.io/), is using Cortex to monitor the storage nodes for the users of its platform.
* [Weaveworks](https://www.weave.works/), uses Cortex to run a commercial hosted Prometheus service.


2. _Have a healthy number of committers. A committer is defined as someone with the commit bit; i.e., someone who can accept contributions to some or all of the project._

We have 8 maintainers 3 of who are independent and 4 of them from 3 different companies. The details are [here](https://github.com/cortexproject/cortex/blob/master/MAINTAINERS).

3. _Demonstrate a substantial ongoing flow of commits and merged contributions._

We are seeing a constant stream of performance improvements and features from the maintainers and community. See the stats here:

* [Commits per week over the last 6 months](https://cortex.devstats.cncf.io/d/2/commits-repository-groups?orgId=1&var-period=d7&var-repogroups=All&from=now-6M&to=now)

* [Issue Opened/Closed per week over the last 6 months](https://cortex.devstats.cncf.io/d/12/issues-opened-closed-by-repository-group?orgId=1&from=now-6M&to=now)

* [New PRs per week over the last 1 year](https://cortex.devstats.cncf.io/d/15/new-prs-in-repository-groups?orgId=1&from=now-1y&to=now)

4. _A clear versioning scheme._

We now have regular releases documented at: https://github.com/cortexproject/cortex/blob/master/RELEASE.md
We’ve only recently started our release process, but have 3 releases out already.

5. _Roadmap_

We're nowhere near done with Cortex and have a lot of plans for future development, and our roadmap currently includes:

* **Write-Ahead Log (In Progress)** - This would enable crash resiliency in Cortex. Right now we replicate each sample n-ways in the ingesters for that but we do have data-loss if enough ingesters crash.
* **Query Parallelisation (In Progress)** - Parallelise the processing of queries further where possible, enabling us to execute massive queries.
* **Simpler runtime configuration** - This would make Cortex easier to operate.
* **Downsampling** - Lets us store less data and over longer periods of time.
* **Recording Rule Substitution** - Right now whenever users add recording rules, they have to wait a long time for the recording rule to populate data before they can switch their dashboards to it. We’re exploring automatically detecting and replacing the original query with its recording rule when appropriate. Once this is in place, we can also detect regular large queries and automatically replace them with recording rules.
* **No dependencies cortex (no NoSQL/Object Store needed)** - This would make Cortex easier to operate on-prem and on bare-metal.
