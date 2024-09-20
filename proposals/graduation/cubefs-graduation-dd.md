# CubeFS Graduation Due Diligence

- Link to [CubeFS Graduation application](https://github.com/cncf/toc/pull/1140)

  <!-- This template provides the TOC with the outline for completing due diligence of a project to move levels. This universal template is designed to capture all criteria so the TOC may ensure prior level criteria do not regress. As part of completing the due diligence, the TOC member should update the template to convey the level the project applied for the criteria by bolding the level indicated where the criteria is relevant. -->

## Graduation Evaluation Summary for CubeFS

### Criteria Evaluation

Kevin Wang conducted the due diligence of CubeFS who applied for graduation. The project has completed the criteria that show its maturity at graduation. The following criteria implementations are noteworthy to call out... $NOTABLES. The following actions were provided to the project that were considered blocking but since resolved... $BLOCKERS. The following recommendations were provided to the project that are non-blocking in the TOC's assessment but should be completed by the project to ensure continued viability of the project... $RECOMMENDATIONS.

### Adoption Evaluation

_The adopter interviews reflect a project [in use/too early] for the level which the project applied. They show ... $INTERVIEWSUMMARY._

### Final Assessment

_[The TOC has found the project to have satisfied the criteria for $LEVEL/ The TOC's evaluation of the project shows a needed focus to complete the outstanding blockers and reapply when the following conditions are met ... $CONDITIONS]._

### Criteria

## Application Process Principles

### Suggested

N/A

### Required

- [x] **Give a presentation and engage with the domain specific TAG(s) to increase awareness**

  <!-- (TOC Evaluation goes here) -->
  Record of CubeFS presentation at the Storage TAG on April 24, 2024. [link to video](https://www.youtube.com/watch?v=UgRBZhzfr4w)

- [ ] **TAG provides insight/recommendation of the project in the context of the landscape**

  <!-- (TOC Evaluation goes here) -->
  ******* Kevin:
  TODO: add recommendation from TAG-storage here.

- [x] **All project metadata and resources are [vendor-neutral](https://contribute.cncf.io/maintainers/community/vendor-neutrality/).**

  <!-- (TOC Evaluation goes here) -->
  - **Neutral resources** - CubeFS has its own channels (community branded and managed), including:
    - Homepage: <cubefs.io>
    - Mailing list: <users@cubefs.groups.io>
    - Slack: <cubefs.slack.com>
    - WeChat: <https://github.com/cubefs/cubefs/issues/604>
    - Twitter: <https://x.com/cubefs_storage>
    - Community Meeting: <https://meeting.tencent.com/dm/IpNLDdT7uyEH>

  - **Governance** - [GOVERNANCE.md](https://github.com/cubefs/cubefs/blob/6617aa1eb7bf6b63bfacc2c266eeb711c650973f/GOVERNANCE.md) defined vendor-neutrality requirements on the TSC, Maintainers, Committers, including:
    - [The structure of the Technical Steering Committee Section](https://github.com/cubefs/cubefs/blob/6617aa1eb7bf6b63bfacc2c266eeb711c650973f/GOVERNANCE.md#the-structure-of-the-maintainers) says: `No single vendor can exceed 50% of the total number of personnel.`
    - [The structure of the Maintainers Section](https://github.com/cubefs/cubefs/blob/6617aa1eb7bf6b63bfacc2c266eeb711c650973f/GOVERNANCE.md#the-structure-of-the-maintainers) says: `No single vendor can exceed 50% of the total number of personnel.`
    - [The structure of the Committers Section](https://github.com/cubefs/cubefs/blob/6617aa1eb7bf6b63bfacc2c266eeb711c650973f/GOVERNANCE.md#the-structure-of-the-committers) says: `No single vendor can exceed 50% of the total number of personnel.`

- [x] **Review and acknowledgement of expectations for [graduated](sandbox.cncf.io) projects and requirements for moving forward through the CNCF Maturity levels.**
  - [x] Met during Project's application on 10-Apr-2024 as a kick-off meeting.
  - And met multiple times during the due diligence review. Meeting notes available at [Tracking Doc for CubeFS Graduation](https://docs.google.com/document/d/1wJIFwXFsvWM9wqayaqhr5n1KCVbttkZPYx_hCs2MbbQ).

  <!-- (TOC Evaluation goes here) -->

Completion of this due diligence document, resolution of concerns raised, and presented for public comment satisifies the Due Diligence Review criteria.

- [x] **Additional documentation as appropriate for project type, e.g.: installation documentation, end user documentation, reference implementation and/or code samples.**

  <!-- (TOC Evaluation goes here) -->
  - [CubeFS introduction documentation](https://cubefs.io/docs/master/overview/introduction.html) introduces the CubeFS architecture and main features.
  - [CubeFS installation documentation](https://cubefs.io/docs/master/deploy/env.html) covers serveral ways of deployment.
  - [CubeFS end user documentation](https://cubefs.io/docs/master/user-guide/volume.html) includes basics operations as creating a volume, using volume and using cli tool.

## Governance and Maintainers

Note: this section may be augmented by the completion of a Governance Review from TAG Contributor Strategy.

### Suggested

- [x] **Governance has continuously been iterated upon by the project as a result of their experience applying it, with the governance history demonstrating evolution of maturity alongside the project's maturity evolution.**

  <!-- (TOC Evaluation goes here) -->
  CubeFS has been continuously updating governance doc to reflect project growth, some examples are:
  - CubeFS inintail governance: <https://github.com/cubefs/cubefs/blob/017c689013cfaef9c430680bc2c68f62c25a8fa9/GOVERNANCE.md#credits>
  - Added Commiter role in May. 2023: <https://github.com/cubefs/cubefs/pull/1976>
  - Added Steering Committee in Apr. 2024: <https://github.com/cubefs/cubefs/pull/3312>
  - Update maintainer list according to activity and add steering commitee member: <https://github.com/cubefs/cubefs/pull/3311>
  - Update the Governance Document to eliminate the role of the leader: <https://github.com/cubefs/cubefs/pull/3382>
    The description of 'project lead' implies a somewhat authoritarian role, but with the establishment of a steering committee, the steering committee should be considered the highest decision-making body.Thus CubeFS delete the role of 'project lead'.
  - Adding governance rules related to SIGs.: <https://github.com/cubefs/cubefs/pull/3430>
  - Adding governance rules related to RoadMap.: <https://github.com/cubefs/cubefs/pull/3430>

### Required

- [x] **Clear and discoverable project governance documentation.**

  <!-- (TOC Evaluation goes here) -->
  CubeFS governance documentation: [GOVERNANCE.md](https://github.com/cubefs/cubefs/blob/6617aa1eb7bf6b63bfacc2c266eeb711c650973f/GOVERNANCE.md)

- [x] **Governance is up to date with actual project activities, including any meetings, elections, leadership, or approval processes.**

  <!-- (TOC Evaluation goes here) -->

  Examples showing that governance is up to date:
  - Update the document of the roadmap: <https://github.com/cubefs/cubefs/pull/3358>
  - Add new Committer: <https://github.com/cubefs/cubefs/pull/3384>
  - Nomination of Chairs and Tech Leads for SIG-CSI and SIG-Docs: <https://github.com/cubefs/cubefs-community/pull/13>

- [x] **Governance clearly documents [vendor-neutral](https://contribute.cncf.io/maintainers/community/vendor-neutrality/) of project direction.**

  <!-- (TOC Evaluation goes here) -->
  CubeFS has clear vendor-neutrality description the [governance doc](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md), including matters related to information transparency, channel transparency, decision-making, and other aspects among vendors.

- [x] **Document how the project makes decisions on leadership, contribution acceptance, requests to the CNCF, and changes to governance or project goals.**

  <!-- (TOC Evaluation goes here) -->
  - Decision making process on leadership roles: [GOVERNANCE.md#decision-making-process](https://github.com/cubefs/cubefs/blob/6617aa1eb7bf6b63bfacc2c266eeb711c650973f/GOVERNANCE.md#decision-making-process)
  - Contribution acceptance: [CONTRIBUTING.md](https://github.com/cubefs/cubefs/blob/6617aa1eb7bf6b63bfacc2c266eeb711c650973f/CONTRIBUTING.md)
  - Requests to the CNCF: [GOVERNANCE.md#cubefs-and-cncf](https://github.com/cubefs/cubefs/blob/6617aa1eb7bf6b63bfacc2c266eeb711c650973f/GOVERNANCE.md#cubefs-and-cncf)
  - Changes to governance or project goals
    - Changes to governance or project goals: [GOVERNANCE.md#changes-in-project-governance](https://github.com/cubefs/cubefs/blob/6617aa1eb7bf6b63bfacc2c266eeb711c650973f/GOVERNANCE.md#changes-in-project-governance)
    - Steering Committee Member is responsible for formulation  roadmap: [GOVERNANCE.md#expectations-from-the-steering-committee](https://github.com/cubefs/cubefs/blob/6617aa1eb7bf6b63bfacc2c266eeb711c650973f/GOVERNANCE.md#expectations-from-the-steering-committee)

- [x] **Document how role, function-based members, or sub-teams are assigned, onboarded, and removed for specific teams (example: Security Response Committee).**

  <!-- (TOC Evaluation goes here) -->
  Main CubeFS project role update according to governance doc:
  - [Becoming a Maintainer](https://github.com/cubefs/cubefs/blob/6617aa1eb7bf6b63bfacc2c266eeb711c650973f/GOVERNANCE.md#becoming-a-maintainer)
  - [Changes in Maintainer membership](https://github.com/cubefs/cubefs/blob/6617aa1eb7bf6b63bfacc2c266eeb711c650973f/GOVERNANCE.md#changes-in-maintainership)
  - [Expectations From the steering committee](https://github.com/cubefs/cubefs/blob/6617aa1eb7bf6b63bfacc2c266eeb711c650973f/GOVERNANCE.md#expectations-from-the-steering-committee)
  - [Changes in Steering Committee](https://github.com/cubefs/cubefs/blob/6617aa1eb7bf6b63bfacc2c266eeb711c650973f/GOVERNANCE.md#changes-in-steering-committee)
  - [Becoming a committer](https://github.com/cubefs/cubefs/blob/6617aa1eb7bf6b63bfacc2c266eeb711c650973f/GOVERNANCE.md#becoming-a-committer)
  - [Changes in committer membership](https://github.com/cubefs/cubefs/blob/6617aa1eb7bf6b63bfacc2c266eeb711c650973f/GOVERNANCE.md#changes-in-commitership)

  Governance of to SIGs. Rules for assignment, onboarding, and removal: [GOVERNANCE.md#sig](https://github.com/cubefs/cubefs/blob/6617aa1eb7bf6b63bfacc2c266eeb711c650973f/GOVERNANCE.md#sig)
  Product Security Committee Membership: Rules for assignment, onboarding, and removal: [security-release-process.md#product-security-committee-membership](https://github.com/cubefs/cubefs/blob/6617aa1eb7bf6b63bfacc2c266eeb711c650973f/security/security-release-process.md#product-security-committee-membership)

- [x] **Document complete list of current maintainers, including names, contact information, domain of responsibility, and affiliation.**

  <!-- (TOC Evaluation goes here) -->
  CubeFS documents maintainers list at: <https://github.com/cubefs/cubefs/blob/6617aa1eb7bf6b63bfacc2c266eeb711c650973f/MAINTAINERS.md>

- [x] **A number of active maintainers which is appropriate to the size and scope of the project.**

  <!-- (TOC Evaluation goes here) -->
  CubeFS has 14 top level maintainers from: JD.com, BEIKE, OPPO, Bytedance, LinkedIn, XFusion. Ref: <https://github.com/cubefs/cubefs/blob/6617aa1eb7bf6b63bfacc2c266eeb711c650973f/MAINTAINERS.md>

  Activities of maintainers can be found at: [chubaofs.devstats.cncf.io](https://chubaofs.devstats.cncf.io/d/66/developer-activity-counts-by-companies?orgId=1&var-period_name=Last%20year&var-metric=contributions&var-repogroup_name=All&var-country_name=All&var-companies=All)

- [x] **Document a complete maintainer lifecycle process (including roles, onboarding, offboarding, and emeritus status).**
  
  <!-- (TOC Evaluation goes here) -->
  CubeFS has a clear maintainer lifecycle process documented in their governance doc:
  - [GOVERNANCE.md#becoming-a-maintainer](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md#becoming-a-maintainer)
  - Document changes in maintainership, onboarding, offboarding: [GOVERNANCE.md#changes-in-maintainership](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md#changes-in-maintainership)

- [ ] **Demonstrate usage of the maintainer lifecycle with outcomes, either through the addition or replacement of maintainers as project events have required.**

  <!-- (TOC Evaluation goes here) -->
  TODO: Kevin

  - According to the GOVERNANCE documentation, in the section on [Changes in Maintainership](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md#changes-in-maintainership), some maintainers are not sufficiently active. Therefore, a TSC member launched a [pull request](https://github.com/cubefs/cubefs/pull/3311) and mentioned the relevant maintainers in the request
  - Example



  - <https://github.com/cubefs/cubefs/pull/3386> Chuanqing Zhang was added as a new committer
  - <https://github.com/cubefs/cubefs/pull/3384> Shuqiang Zheng was added as a new committer
  - <https://github.com/cubefs/cubefs/pull/3311> updated maintainer list including removal of inactive maintainers, and added steering committee members


  - Contributor propose to [add a committer](https://github.com/cubefs/cubefs/pull/3384) in line with the [Expectations from Committers](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md#expectations-from-committers) section and nominate candidates according to the guidelines in the [Becoming a Committer](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md#becoming-a-committer) section.

- [x] **Project maintainers from at least 2 organizations that demonstrates survivability.**

  <!-- (TOC Evaluation goes here) -->
  According to the [Maintainers list](https://github.com/cubefs/cubefs/blob/1536a544f2d9547647ad4e260edade60163e3585/MAINTAINERS.md), CubeFS currently has top level maintainers from OPPO, JD.com, BEIKE, Bytedance, LinkedIn, and additional committers from BIGO, VIVO.

  Definition of Maintainers and Committers can be found in the [GOVERNANCE.md](https://github.com/cubefs/cubefs/blob/1536a544f2d9547647ad4e260edade60163e3585/GOVERNANCE.md)
  Both Maintainers and Committers require diversed membership: `No single vendor can exceed 50% of the total number of personnel.`

- [x] **Code and Doc ownership in Github and elsewhere matches documented governance roles.**

  <!-- (TOC Evaluation goes here) -->
  CubeFS uses a github CODEOWNERS mechanism to manage the code access between different community roles. Ref: <https://github.com/cubefs/cubefs/tree/master/.github/CODEOWNERS>


- [x] **Document agreement that project will adopt CNCF Code of Conduct.**

  <!-- (TOC Evaluation goes here) -->
  Documented at [GOVERNANCE.md#code-of-conduct](https://github.com/cubefs/cubefs/blob/1536a544f2d9547647ad4e260edade60163e3585/GOVERNANCE.md#code-of-conduct)
  
- [x] **CNCF Code of Conduct is cross-linked from other governance documents.**

  <!-- (TOC Evaluation goes here) -->
  CNCF Code of conduct is cross-linked in the [Code of Conduct of CubeFS](https://github.com/cubefs/cubefs/blob/1536a544f2d9547647ad4e260edade60163e3585/CODE_OF_CONDUCT.md)

- [x] **All subprojects, if any, are listed.**

  <!-- (TOC Evaluation goes here) -->
  The following projects are associated with CubeFS and maintained as sub-projects.
  - [cubefs-helm](https://github.com/cubefs/cubefs-helm): CubeFS installation to helm in the Kubernetes ecosystem
  - [cubefs-csi](https://github.com/cubefs/cubefs-csi): CSI (Container Storage Interface) plugin for CubeFS
  - [cubefs-dashboard](https://github.com/cubefs/cubefs-dashboard): Dashboard for CubeFS

- [x] **If the project has subprojects: subproject leadership, contribution, maturity status documented, including add/remove process.**

  <!-- (TOC Evaluation goes here) -->
  According to [Governance.md#sub-projects](https://github.com/cubefs/cubefs/blob/3576d88889e94d7173401e389824dd61cc485718/GOVERNANCE.md#sub-projects), sub-projects can have their own repositories but follow the same governance mechanism as the main project

  Subprojects Goverance descriptions:
  - [cubefs-helm Governance](https://github.com/cubefs/cubefs-csi#governance)
  - [cubefs-csi Governance](https://github.com/cubefs/cubefs-csi#governance)
  - [cubefs-dashboard Governance](https://github.com/cubefs/cubefs-dashboard#governance)

## Contributors and Community

Note: this section may be augmented by the completion of a Governance Review from TAG Contributor Strategy.

### Suggested

- [x] **Contributor ladder with multiple roles for contributors.**

  <!-- (TOC Evaluation goes here) -->
  Cubefs have multiple roles for contributors
  - Steering committee member: [GOVERNANCE.md#expectations-from-the-steering-committee](https://github.com/cubefs/cubefs/blob/1536a544f2d9547647ad4e260edade60163e3585/GOVERNANCE.md#expectations-from-the-steering-committee)
  - Maintainer: [GOVERNANCE.md#expectations-from-maintainers](https://github.com/cubefs/cubefs/blob/1536a544f2d9547647ad4e260edade60163e3585/GOVERNANCE.md#expectations-from-maintainers)
  - Commiter: [GOVERNANCE.md#committer](https://github.com/cubefs/cubefs/blob/1536a544f2d9547647ad4e260edade60163e3585/GOVERNANCE.md#committer)

### Required

- [x] **Clearly defined and discoverable process to submit issues or changes.**

  <!-- (TOC Evaluation goes here) -->
  Defined in [CONTRIBUTING.md](https://github.com/cubefs/cubefs/blob/master/CONTRIBUTING.md), in the root path of CubeFS main repo.

- [x] **Project must have, and document, at least one public communications channel for users and/or contributors.**

  <!-- (TOC Evaluation goes here) -->
  CubeFS has the following public communications channel for users and contributors documented in the [Project README](https://github.com/cubefs/cubefs#community)
  - Website: <https://cubefs.io/>
  - Mailing list: <users@cubefs.groups.io>
  - Slack: <https://cubefs.slack.com>
  - WeChat: <https://github.com/cubefs/cubefs/issues/604>
  - X/Twitter: <https://x.com/cubefs_storage>

- [x] **List and document all project communication channels, including subprojects (mail list/slack/etc.).  List any non-public communications channels and what their special purpose is.**

  <!-- (TOC Evaluation goes here) -->
  - The communication channels for CubeFS documented at <https://github.com/cubefs/cubefs#community>
  - Besides public channels, CubeFS has a private mailing list <security@cubefs.groups.io> for users reporting security vulnerabilities. Ref: [SECURITY.md](https://github.com/cubefs/cubefs/blob/1536a544f2d9547647ad4e260edade60163e3585/SECURITY.md)

- [x] **Up-to-date public meeting schedulers and/or integration with CNCF calendar.**

  <!-- (TOC Evaluation goes here) -->
  CubeFS currently holds monthly community meeting, integrated with [CNCF calendar](https://www.cncf.io/calendar/)
  Meeting minutes and recordings listed at: [CubeFS meeting schedule](https://github.com/cubefs/cubefs-community/wiki/Meeting-Schedule)

- [x] **Documentation of how to contribute, with increasing detail as the project matures.**

  <!-- (TOC Evaluation goes here) -->
  CubeFS contribution workflow documented at: [CONTRIBUTING.md#workflow](https://github.com/cubefs/cubefs/blob/1536a544f2d9547647ad4e260edade60163e3585/CONTRIBUTING.md#workflow)

- [x] **Demonstrate contributor activity and recruitment.**

  <!-- (TOC Evaluation goes here) -->
  - Contributor activities measured by devstats: [chubaofs.devstats.cncf.io](https://chubaofs.devstats.cncf.io/d/66/developer-activity-counts-by-companies?orgId=1&var-period_name=Since%20joining%20CNCF&var-metric=contributions&var-repogroup_name=All&var-country_name=All&var-companies=All)  
  - Contributor activity measured by GitHub contributor dashboard: [The contributions of contributors](https://github.com/cubefs/cubefs/graphs/contributors)
  - Example of recruiting new committers according to contributor's contributions:
    - [shuqiang-zheng](https://github.com/shuqiang-zheng) :
    - [Contribution pr record](https://github.com/cubefs/cubefs/pulls?q=is%3Apr+is%3Amerged+author%3Ashuqiang-zheng)
    - [PR link](https://github.com/cubefs/cubefs/pull/3384) to add to Committers list
    - [zhangchuanqing](https://github.com/zhangchuanqing5658) : 
    - [Contribution main branch](https://github.com/cubefs/cubefs/tree/develop-v3.5.0-metanode_rocksdb)
    - [PR link](https://github.com/cubefs/cubefs/pull/3386) to add to Committers list

  - Recruiting new contributors by participating in developer events
    - [Summer of Open Source](https://www.we2shopping.com/blog/2829327/)
    - [Developer activity 2024](https://github.com/cubefs/cubefs/issues/3105)
    - [Developer activity 2023](https://github.com/cubefs/cubefs/issues/1920)

## Engineering Principles

- [x] **Document project goals and objectives that illustrate the project’s differentiation in the Cloud Native landscape as well as outlines how this project fulfills an outstanding need and/or solves a problem differently.**

  <!-- (TOC Evaluation goes here) -->
  Project goal from project [README.md#what-can-you-build-with-cubefs](https://github.com/cubefs/cubefs/blob/master/README.md#what-can-you-build-with-cubefs): 

  > As an open-source distributed storage, CubeFS can serve as your datacenter filesystem, data lake storage infra, and private or hybrid cloud storage. 
  > In particular, CubeFS enables the separation of storage/compute architecture for databases and AI/ML applications.
  > 
  > Some key features of CubeFS include:
  > 
  > - Multiple access protocols such as POSIX, HDFS, S3, and its own REST API
  > - Highly scalable metadata service with strong consistency  
  > - Performance optimization of large/small files and sequential/random writes
  > - Multi-tenancy support with better resource utilization and tenant isolation
  > - Hybrid cloud I/O acceleration through multi-level caching
  > - Flexible storage policies, high-performance replication or low-cost erasure coding

- [x] **Document what the project does, and why it does it - including viable cloud native use cases.**

  <!-- (TOC Evaluation goes here) -->
  CubeFS Introduction: [link](https://cubefs.io/docs/master/overview/introduction.html)

  According to [CubeFS doc](<https://cubefs.io/docs/master/overview/introduction.html#application-scenarios>), typical use cases are:
  - Big Data Analytics
  - Deep Learning/Machine Learning
  - Container Shared Storage
  - Database & Middleware
  - Online Services
  - Traditional NAS to Cloud

- [x] **Document and maintain a public roadmap or other forward looking planning document or tracking mechanism.**

  <!-- (TOC Evaluation goes here) -->
  CubeFS has a public roadmap doc at [ROADMAP.md](https://github.com/cubefs/cubefs/blob/master/ROADMAP.md)

- [x] **Roadmap change process is documented.**

  <!-- (TOC Evaluation goes here) -->
  CubeFS documentes its roadmap rules and changing process in [GOVERNANCE.md#roadmap](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md#roadmap)

- [x] **Document overview of project architecture and software design that demonstrates viable cloud native use cases, as part of the project's documentation.**

  <!-- (TOC Evaluation goes here) -->
  - CubeFS architecture overview: <https://cubefs.io/docs/master/overview/architecture.html#architecture>
  - Design details are documented under the "Design" section, an example is: <https://cubefs.io/docs/master/design/master.html>

- [x] **Document the project's release process and guidelines publicly in a RELEASES.md or equivalent file that defines:**

  - [x] Release expectations (scheduled or based on feature implementation)
  - [x] Tagging as stable, unstable, and security related releases
  - [x] Information on branch and tag strategies
  - [x] Branch and platform support and length of support
  - [x] Artifacts included in the release.
  - Additional information on topics such as LTS and edge releases are optional. Release expectations are a social contract between the project and its end users and hence changes to these should be well thought out, discussed, socialized and as necessary agreed upon by project leadership before getting rolled out.

    <!-- (TOC Evaluation goes here) -->

  According to [CubeFS RELEASES.md](https://github.com/cubefs/cubefs/blob/master/RELEASE.md#artifacts-included-in-the-release):
  - Cubefs documents their release frequency as needed (beta and official releases), which can be regarded as based on feature implementation.
  - Length of support clearly documented, support latest 3 minor releases.
  - No specific description of platform supported, according to the [artifacts-included-in-the-release](https://github.com/cubefs/cubefs/blob/cef58ab3db04857b05a69d9a132e37d4d92e79c7/RELEASE.md#artifacts-included-in-the-release), currently only amd64 binaries are maintained by the community.

  Security release process described at: <https://github.com/cubefs/cubefs/blob/master/security/security-release-process.md>

- [x] **History of regular, quality releases.**

  <!-- (TOC Evaluation goes here) -->
  History of CubeFS releases and changelogs: <https://github.com/cubefs/cubefs/releases>

## Security

Note: this section may be augemented by a joint-assessment performed by TAG Security.

### Suggested

- [x] **Achieving OpenSSF Best Practices silver or gold badge.**

  <!-- (TOC Evaluation goes here) -->
  CubeFS has achieved the OpenSSF Best Practices siler badge: <https://www.bestpractices.dev/projects/6232>
  [![OpenSSF Best Practices](https://www.bestpractices.dev/projects/6232/badge)](https://www.bestpractices.dev/projects/6232)

### Required

- [x] **Clearly defined and discoverable process to report security issues.**

  <!-- (TOC Evaluation goes here) -->
  CubeFS has a clear security vulnerability report guide at: [SECURITY.md](https://github.com/cubefs/cubefs/blob/1536a544f2d9547647ad4e260edade60163e3585/SECURITY.md#report-a-vulnerability)

- [x] **Enforcing Access Control Rules to secure the code base against attacks (Example: two factor authentication enforcement, and/or use of ACL tools.)**

  <!-- (TOC Evaluation goes here) -->
  - CubeFS commnity is currently WIP in the enforcement of two-factor authentication for all members: <https://github.com/cubefs/cubefs/issues/3487>.
  - DCO sign-off and review&approval by maintainers are required for all the incoming pull-request Ref: <https://github.com/cubefs/cubefs/blob/master/CONTRIBUTING.md#workflow>
    > Every pull request that merges code to the master branch needs to be approved by at least one core maintainer for code review and pass all checks (including the DCO check) before it can be merged.
  - CubeFS also enabled the following static and dynamic scanning, security scanning to help ensure the code quality:
    - [gofumpt](https://github.com/cubefs/cubefs/blob/master/docker/script/run_format.sh)
    - golint:In file [docker-compose.yml:469](https://github.com/cubefs/cubefs/blob/master/docker/docker-compose.yml#L469-L477)
    - gosec:In file [docker-compose.yuml:479](https://github.com/cubefs/cubefs/blob/master/docker/docker-compose.yml#L479-L487)
    - Fuzz testing [cubefs: add base fuzzers cncf/cncf-fuzzing#387](https://github.com/cncf/cncf-fuzzing/pull/387)
  - CI integration includes ci-test-unit, ci-test-s3 and ci-sast: [ci.yml](https://github.com/cubefs/cubefs/blob/master/.github/workflows/ci.yml)

- [x] **Document assignment of security response roles and how reports are handled.**

  The CubeFS [Security Release Process](https://github.com/cubefs/cubefs/blob/1536a544f2d9547647ad4e260edade60163e3585/security/security-release-process.md) documents response roles and process of handling reports.

- [x] **Document Security Self-Assessment.**
  
  <!-- (TOC Evaluation goes here) -->
  <https://github.com/cubefs/cubefs/blob/6617aa1eb7bf6b63bfacc2c266eeb711c650973f/security/CubeFS-self-assessment.md>

- [x] **Third Party Security Review.**

  - [x] Moderate and low findings from the Third Party Security Review are planned/tracked for resolution as well as overall thematic findings, such as: improving project contribution guide providing a PR review guide to look for memory leaks and other vulnerabilities the project may be susceptible to by design or language choice ensuring adequate test coverage on all PRs.

  <!-- (TOC Evaluation goes here) -->
  CubeFS has passed the Third Party Security Review, Ref: [CubeFS-Security-Audit-2023-report](https://github.com/cubefs/cubefs/blob/master/security/CubeFS-security-audit-2023-report.pdf).
  All found issues have been fixed, ref: page4 in the report "Executive summary".
  Security advisories of the fixes: [link](https://github.com/cubefs/cubefs/security/advisories?state=Triage)

- [x] **Achieve the Open Source Security Foundation (OpenSSF) Best Practices passing badge.**

  <!-- (TOC Evaluation goes here) -->
  CubeFS has achieved OpenSSF Best Practices passing badge: <https://www.bestpractices.dev/en/projects/6232>

## Ecosystem

### Suggested

N/A

### Required

- [x] **Publicly documented list of adopters, which may indicate their adoption level (dev/trialing, prod, etc.)**

  <!-- (TOC Evaluation goes here) -->
  The [ADOPTERS.md](https://github.com/cubefs/cubefs/blob/master/ADOPTERS.md) documentes adopters with adoption level and success stories.

- [x] **Used in appropriate capacity by at least 3 independent + indirect/direct adopters, (these are not required to be in the publicly documented list of adopters)**

  <!-- (TOC Evaluation goes here) -->
  The project provided the TOC with a list of adopters for verification of use of the project at the level expected, i.e. production use for graduation.
  CubeFS has been adopted by a large base of end users, most of which prefer to remain anonymous.

- [x] **TOC verification of adopters.**

  <!-- (TOC Evaluation goes here) -->
  CubeFS Maintainers provided the TOC sponsor with a list of 7 users who agreed to be interviewed for the Graduation Due Diligence process.
  Refer to the [Adoption portion of this document](#adoption) for details.

- [x] **Clearly documented integrations and/or compatibility with other CNCF projects as well as non-CNCF projects.**

  <!-- (TOC Evaluation goes here) -->
  - Integration with Hadoop: <https://cubefs.io/docs/master/ecology/hadoop.html>
  - Integration with Kubernetes: <https://cubefs.io/docs/master/ecology/k8s.html>
  - Integration with Prometheus: <https://cubefs.io/docs/master/ecology/prometheus.html>
  - Integration with Grafana: <https://cubefs.io/docs/master/ecology/grafana.html>



#### Adoption

##### Adopter 1 - $COMPANY/$INDUSTRY

_If the Adopting organization needs to remain anonymous, stating the industry vertical is sufficient._
MONTH YEAR

##### Adopter 2 - $COMPANY/$INDUSTRY

_If the Adopting organization needs to remain anonymous, stating the industry vertical is sufficient._
MONTH YEAR

##### Adopter 3 - $COMPANY/$INDUSTRY

_If the Adopting organization needs to remain anonymous, stating the industry vertical is sufficient._
MONTH YEAR
