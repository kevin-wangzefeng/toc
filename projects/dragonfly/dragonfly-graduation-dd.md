# Dragonfly Graduation Due Diligence

- Link to [Graduation application issue](https://github.com/cncf/toc/issues/1358)

<!-- This template provides the TOC with the outline for completing due diligence of a project to move levels. This universal template is designed to capture all criteria so the TOC may ensure prior level criteria do not regress. As part of completing the due diligence, the TOC member should update the template to convey the level the project applied for the criteria by bolding the level indicated where the criteria is relevant. -->

## Graduation Evaluation Summary for Dragonfly

### Criteria Evaluation

Kevin Wang conducted the due diligence of Dragonfly who applied for graduation. The project has completed the criteria that show its maturity at graduation.

- The following criteria implementations are noteworthy to call out.
  - NOTABLE1
  - NOTABLE2
  - NOTABLE3

- The following actions were provided to the project that were considered blocking but since resolved.
  - BLOCKER1
  - BLOCKER2
  - BLOCKER3

- The following recommendations were provided to the project that are non-blocking in the TOC's assessment but should be completed by the project to ensure continued viability of the project.
  - The temporary link used for joining Dingtalk has expired. The TOC Reviewer suggests to update the instructions with searching group number. Ref: <https://github.com/dragonflyoss/dragonfly/issues/4298>
  - TOC Reviewer suggests to add documentation explaining how the project handles requests to the CNCF, and changes to governance or project goals. Ref: <https://github.com/dragonflyoss/dragonfly/issues/4324>
  - There are duplicated definitions of "Adding New Member/Approver/Maintainer" in the community documents (in COMMUNITY_LADDER.md and COMMUNITY_MEMBERSHIP.md). TOC Reviewer suggests to consolidate these into a single source of truth. Ref: <https://github.com/dragonflyoss/dragonfly/issues/4325>
  - The TOC Reviewer suggests to document the responsibilities and focus areas for each maintainer (including community wide maintainers and subproject maintainer) in MAINTAINERS.md. Even if there is no differentiation among maintainers, it should be explicitly stated to provide clarity on maintainer roles within the project.


  - RECOMMENDATION1
  - RECOMMENDATION2
  - RECOMMENDATION3

### Adoption Evaluation

_The adopter interviews reflect a project [in use/too early] for the level which the project applied. They show ... $INTERVIEWSUMMARY._

### Final Assessment

_[The TOC has found the project to have satisfied the criteria for $LEVEL/ The TOC's evaluation of the project shows a needed focus to complete the outstanding blockers and reapply when the following conditions are met ... $CONDITIONS]._

### Criteria

## Application Process Principles

### Suggested

N/A

### Required

- [ ] **Engage with the domain specific TAG(s) to increase awareness through a presentation or completing a General Technical Review.**
  - This was completed and occurred on 09-28-2023, and can be discovered at [Tag Runtime Meeting Notes](https://docs.google.com/document/d/1k7VNetgbuDNyIs_87GLQRH2W5SLgjgOhB6pDyv89MYk/edit?tab=t.0#heading=h.r893yssi5g88).

  <!-- (TOC Evaluation goes here) -->

- [x]  **All project metadata and resources are [vendor-neutral](https://contribute.cncf.io/maintainers/community/vendor-neutrality/).**

  <!-- (TOC Evaluation goes here) -->
  Dragonfly has its own channels (community branded and managed), including:
  - Project Repo(s): <https://github.com/dragonflyoss/dragonfly> and other repos under <https://github.com/dragonflyoss>.
  - Project Site: <https://d7y.io/>
  - Slack: <https://cloud-native.slack.com/messages/dragonfly/>
  - Mailing Lists:
    - Developers: <dragonfly-developers@googlegroups.com>
    - Maintainers: <dragonfly-maintainers@googlegroups.com>
  - X: <https://x.com/dragonfly_oss>
  - Dingtalk: Group No. 22880028764
  
  **TODO for Dragonfly Team**: the link for joining Dingtalk group is out of date, needs fix. Ref: <https://github.com/dragonflyoss/dragonfly/issues/4298>

- [x] **Review and acknowledgement of expectations for [Sandbox](sandbox.cncf.io) projects and requirements for moving forward through the CNCF Maturity levels.**  
  - [x] Met during Project's application on 27-06-2024 as a kick-off meeting.

<!-- (TOC Evaluation goes here) -->

- [ ] **Due Diligence Review.**

  **TODO for TOC Reviewer**: update when main DD evaluation finished.

  Completion of this due diligence document, resolution of concerns raised, and presented for public comment satisfies the Due Diligence Review criteria.

- [x] **Additional documentation as appropriate for project type, e.g.: installation documentation, end user documentation, reference implementation and/or code samples.**

  <!-- (TOC Evaluation goes here) -->
  Dragonfly project documentation can be found in <https://d7y.io/docs/next/>.  
  The documentations include: Installation, Architecture, Best Practices, Advanced Guides, and Development Guides, etc.  
  Contributor documentation for the project can be found in <https://github.com/dragonflyoss/community/blob/master/CONTRIBUTING.md>.

## Governance and Maintainers

Note: this section may be augmented by the completion of a Governance Review from the Project Reviews subproject.

### Suggested

- [ ]  **Governance has continuously been iterated upon by the project as a result of their experience applying it, with the governance history demonstrating evolution of maturity alongside the project's maturity evolution.**

<!-- (TOC Evaluation goes here) --> 
Dragonfly has been continuously updating governance doc to reflect project growth, some examples are:

**TODO for Dragonfly team**: provide examples of updating community governance

<!-- (Project assertion goes here) -->  
Decisions are made through consensus among maintainers during regular community meetings or via mailing list discussions. Major decisions (e.g., roadmap changes, new maintainers) require a majority vote among maintainers and are documented in [GOVERNANCE.md](https://github.chttps://github.com/dragonflyoss/community/blob/master/GOVERNANCE.md). Community input is encouraged through GitHub issues and public meetings before final decisions are made.

Maintainer Role Division:
Maintainers share responsibilities across all project areas but often focus on specific sub-projects or components based on expertise (e.g., Nydus for image acceleration, console for UI). Specific roles include code review, release management, and community engagement. Detailed responsibilities and current maintainers are listed in [MAINTAINERS.md](https://github.com/dragonflyoss/dragonfly/blob/main/MAINTAINERS.md).

- 2018: Initial governance model established with a small group of core maintainers from Alibaba and Ant Group focusing on basic contribution and review processes.
- 2020: Post-incubation, governance updated to include more maintainers from diverse organizations (e.g., ByteDance, Intel) and formalized sub-project leadership for Nydus.
- 2021-2023: Introduced detailed contributor ladders and emeritus status for maintainers, alongside public documentation of decision-making processes to ensure transparency.


### Required

- [x] **Clear and discoverable project governance documentation.**

  <!-- (TOC Evaluation goes here) -->
  The Dragonfly project governance doc can be easily found at <https://github.com/dragonflyoss/community/blob/master/GOVERNANCE.md>, and cross linked by other relavent locations.

  Other community governance relevant content e.g. contributor ladder (COMMUNITY_LADDER.md) and contribution guide (CONTRIBUTING.md) are also cross-linked in the GOVERNANCE.md doc.

- [ ] **Governance is up to date with actual project activities, including any meetings, elections, leadership, or approval processes.**

  <!-- (TOC Evaluation goes here) --> 
  Dragonfly community has resolved the findings and suggestions raised during [Dragonfly governance Review](https://github.com/cncf/toc/issues/1599), some noteworthy updates are:
  - Unified and updated governance docs, fixing outdated links and redundancy between community and main repo. PRs: [dragonflyoss/community#25](https://github.com/dragonflyoss/community/pull/25), [dragonflyoss/dragonfly#4087](https://github.com/dragonflyoss/dragonfly/pull/4087)

  **TODO**: provide more highligths here

  Refer to <https://github.com/dragonflyoss/community/issues/27> for more details.

- [x] **Governance clearly documents [vendor-neutral](https://contribute.cncf.io/maintainers/community/vendor-neutrality/) of project direction.**

  <!-- (TOC Evaluation goes here) -->
  Dragonfly documents its commitemnt in the [GOVERNANCE.md](https://github.com/dragonflyoss/community/blob/master/GOVERNANCE.md).  
  And [COMMUNITY_MEBMERSHIP.md#maximum-representation](https://github.com/dragonflyoss/community/blob/master/COMMUNITY_MEMBERSHIP.md#maximum-representation) explicitly documents maximum representation of maintainers from the same company:
  > To ensure balanced representation, no more than four active Maintainers may be from the same company. If more than four candidates from one company are elected, only the top four vote-getters will serve, with additional slots filled by the next highest vote recipients from other organizations.

- [ ] **Document how the project makes decisions on leadership, contribution acceptance, requests to the CNCF, and changes to governance or project goals.**

  <!-- (TOC Evaluation goes here) -->
  Dragonfly documents detailed project leadership management rules at <https://github.com/dragonflyoss/community/blob/master/COMMUNITY_MEMBERSHIP.md#managing-membership>

  THe contribution acceptance is documented in the contributing guide at <https://github.com/dragonflyoss/community/blob/master/CONTRIBUTING.md#contributing-code-and-docs>.

  **TODO for Dragonfly team:** TOC Reviewer suggests to add documentation explaining how the project handles requests to the CNCF, and changes to governance or project goals.

- [x] **Document how role, function-based members, or sub-teams are assigned, onboarded, and removed for speci fic teams (example: Security Response Committee).**

  <!-- (TOC Evaluation goes here) -->
  Dragonfly describes the basic roles, responsibilies, and how to become on the role in the [community ladder](https://github.com/dragonflyoss/community/blob/master/COMMUNITY_LADDER.md).

  **TODO for Dragonfly Team:** There are duplicate definitions of "Adding New Member/Approver/Maintainer" in the community documents:
  - location 1: <https://github.com/dragonflyoss/community/blob/master/COMMUNITY_LADDER.md?plain=1#L164>
  - location 2: <https://github.com/dragonflyoss/community/blob/master/COMMUNITY_MEMBERSHIP.md#adding-new-memberapprovermaintainer>
  It's suggested to consolicate them, and implement a single source of truth.

- [ ] **Document a complete maintainer lifecycle process (including roles, onboarding, offboarding, and emeritus status).**

  <!-- (TOC Evaluation goes here) -->
  Repository maintainers are added by: <https://github.com/dragonflyoss/community/blob/master/COMMUNITY_MEMBERSHIP.md#adding-new-maintainers>

  Repository maintainers are removed by: <https://github.com/dragonflyoss/community/blob/master/COMMUNITY_MEMBERSHIP.md#removing-inactive-maintainers>

  **TODO for Dragonfly Team:** same as above, there's a redundant location of adding maintainers, at <https://github.com/dragonflyoss/community/blob/master/COMMUNITY_LADDER.md?plain=1#L199-L201>

- [x] **Demonstrate usage of the maintainer lifecycle with outcomes, either through the addition or replacement of maintainers as project events have required.**

  <!-- (TOC Evaluation goes here) -->
  The Dragonfly community added a new maintainer in July following the process defined in at [COMMUNITY_MEMBERSHIP.md#adding-new-memberapprovermaintainer](https://github.com/dragonflyoss/community/blob/master/COMMUNITY_MEMBERSHIP.md#adding-new-memberapprovermaintainer).

  Full record of the process that time can be found at: <https://github.com/dragonflyoss/community/issues/62>

- [ ] **Document complete list of current maintainers, including names, contact information, domain of responsibility, and affiliation.**

  <!-- (TOC Evaluation goes here) -->
  Dragonfly documents current maintainers and emeritus maintainers at <https://github.com/dragonflyoss/community/blob/master/MAINTAINERS.md>. All maintainers share all domains of responsbility.

  **TODO For Dragonfly Team:** The responsibilities and focus areas for each maintainer have not been documented. Even with no differentiation among maintainers, it should be explicitly stated in the MAINTAINERS.md.

- [x] **A number of active maintainers which is appropriate to the size and scope of the project.**

  <!-- (TOC Evaluation goes here) -->
  The project's activity level shows a reasonable distribution of maintainers. Of the top 10 contributors over the past 180 days, 5 are active maintainers.  
  Refer to the "Contributor Leaderboard" in [LFX insights - Dragonfly](https://insights.linuxfoundation.org/project/d7y/contributors?timeRange=past180days&start=2025-03-18&end=2025-09-14&widget=contributors-leaderboard) for more details.

- [x] **Project maintainers from at least 2 organizations that demonstrates survivability.**

  <!-- (TOC Evaluation goes here) -->
  According to <https://github.com/dragonflyoss/community/blob/master/MAINTAINERS.md>, Dragonfly currently has 13 maintainers from 7 different companies/organizations.

- [ ] **Code and Doc ownership in Github and elsewhere matches documented governance roles.**

  <!-- (TOC Evaluation goes here) -->
  Only find <https://github.com/dragonflyoss/dragonfly/blob/main/.github/CODEOWNERS> in Dragonlfy main repo.

  Need double check since the github teams `@dragonflyoss/dragonfly2-maintainers` and `@dragonflyoss/dragonfly2-reviewers` are not visibable.

  **TODO For Dragonfly Team:** provide links wherever `CODEOWNSERS` or `OWNERS` files located. also provide the members list of `@dragonflyoss/dragonfly2-maintainers` and `@dragonflyoss/dragonfly2-reviewers`


- [x] **Document adoption and adherence to the CNCF Code of Conduct or the project's CoC which is based off the CNCF CoC and not in conflict with it.**

  <!-- (TOC Evaluation goes here) -->
  According to <https://github.com/dragonflyoss/community/blob/master/CODE_OF_CONDUCT.md>, Dragonfly follows the CNCF Code of Conduct.

- [ ] **CNCF Code of Conduct is cross-linked from other governance documents.**

  <!-- (TOC Evaluation goes here) -->
  Yes, it's documented at <https://github.com/dragonflyoss/community/blob/master/CODE_OF_CONDUCT.md>.  
  And the CNCF Code of Conduct is also cross-linked by <https://github.com/dragonflyoss/community/blob/master/GOVERNANCE.md#code-of-conduct> and <https://github.com/dragonflyoss/community/blob/master/COMMUNITY_MEMBERSHIP.md>

  **TODO for Dragonfly team:** Missing reciever email address in case of any violation happens in the community. Suggested to add the following description:
  > Instances of abusive, harassing, or otherwise unacceptable behavior may be reported by contacting the project team at {email address here}.

- [ ] **All subprojects, if any, are listed.**

  <!-- (TOC Evaluation goes here) -->
  Dragonfly does not have formally defined "subprojects", but [all repositories](https://github.com/orgs/dragonflyoss/repositories?type=all) under the dragonflyoss adhere to the well defined governance.

  **TODO for Dragonfly team:** nydus looks like a subproject, if it isn't, it shall be stated as well what it is to the Dragonfly community.

- [ ] **If the project has subprojects: subproject leadership, contribution, maturity status documented, including add/remove process.**

  <!-- (TOC Evaluation goes here) -->
  **TODO for Dragonfly team:** Ref the issue above

## Contributors and Community

Note: this section may be augmented by the completion of a Governance Review from the Project Reviews subproject.

### Suggested

- [x] **Contributor ladder with multiple roles for contributors.**

  <!-- (TOC Evaluation goes here) -->
  Dragonfly has the following roles for contributors that are related to code and non-code contributions:
  - Contributor: <https://github.com/dragonflyoss/community/blob/master/COMMUNITY_LADDER.md#contributor>
  - Member: <https://github.com/dragonflyoss/community/blob/master/COMMUNITY_LADDER.md#member>
  - Approver: <https://github.com/dragonflyoss/community/blob/master/COMMUNITY_LADDER.md#approver>
  - Maintainer: <https://github.com/dragonflyoss/community/blob/master/COMMUNITY_LADDER.md#maintainer>

### Required

- [x] **Clearly defined and discoverable process to submit issues or changes.**

  <!-- (TOC Evaluation goes here) -->
  Dragonfly has a clear [CONTRIBUTING.md](https://github.com/dragonflyoss/community/blob/master/CONTRIBUTING.md), with details of the relevant process at:
  - Reporting General Issues: <https://github.com/dragonflyoss/community/blob/master/CONTRIBUTING.md#reporting-general-issues>
  - Reporting Security Issues: <https://github.com/dragonflyoss/community/blob/master/CONTRIBUTING.md#reporting-security-issues>
  - Contributing Code and Docs: <https://github.com/dragonflyoss/community/blob/master/CONTRIBUTING.md#contributing-code-and-docs>

- [x] **Project must have, and document, at least one public communications channel for users and/or contributors.**

<!-- (TOC Evaluation goes here) --> 
Dragonfly documents the communication channels at: <https://github.com/dragonflyoss/community/blob/master/README.md#community>.

- [ ] **List and document all project communication channels, including subprojects (mail list/slack/etc.).  List any non-public communications channels and what their special purpose is.**

  <!-- (TOC Evaluation goes here) -->
  The main community communication channels are documented at: <https://github.com/dragonflyoss/community/blob/master/README.md#community>.

  Communication channels of Nydus subproject are documented at: <https://github.com/dragonflyoss/nydus/blob/master/README.md#community>

  **TODO for Dragonfly Team:** The TOC reviewer suggests to document the list of subprojects and include subproject communication channels in the list.

- [x] **Up-to-date public meeting schedulers and/or integration with CNCF calendar.**

  <!-- (TOC Evaluation goes here) -->
  All meetings within the Dragonfly community and ecosystem are tracked in the [community calendar](https://calendar.google.com/calendar/embed?src=46bc5a3d67a81a55e0266b6c349a9d833de979922b1232a81bd6dd5ba571b00d%40group.calendar.google.com&ctz=Asia%2FShanghai).

- [x] **Documentation of how to contribute, with increasing detail as the project matures.**

<!-- (TOC Evaluation goes here) -->
The [Contributing guide](https://github.com/dragonflyoss/community/blob/master/CONTRIBUTING.md) describes the process of how to contribute to the project, what the maintainers are expecting, and guidance for how to make a successful contribution.

- [ ] **Demonstrate contributor activity and recruitment.**

<!-- (TOC Evaluation goes here) -->
**TODO for Dragonfly team:** provide record of recruiting contributors.

## Engineering Principles

### Suggested

N/A

### Required

- [x] **Document project goals and objectives that illustrate the project’s differentiation in the Cloud Native landscape as well as outlines how this project fulfills an outstanding need and/or solves a problem differently. _This requirement may also be satisfied by completing a General Technical Review._**

  <!-- (TOC Evaluation goes here) -->
  This is documented at the [project readme](https://github.com/dragonflyoss/dragonfly/blob/main/README.md#introduction):
  > Dragonfly is an open source P2P-based file distribution and image acceleration system. It is hosted by the Cloud Native Computing Foundation ([CNCF](https://cncf.io/)) as an Incubating Level Project.
  > Its goal is to tackle all distribution problems in cloud native architectures.
  > Currently Dragonfly focuses on being:
  > - **Simple**: Well-defined user-facing API (HTTP), non-invasive to all container engines;
  > - **Efficient**: Seed peer support, P2P based file distribution to save enterprise bandwidth;
  > - **Intelligent**: Host-level speed limit, intelligent flow control due to host detection;
  > - **Secure**: Block transmission encryption, HTTPS connection support.

  **TODO for Kevin:** The TOC Reviewer suggests the project maintainers to maintain a GTR file and complete Domain Technical Review after the graduation DD.

- [x] **Document what the project does, and why it does it - including viable cloud native use cases. _This requirement may also be satisfied by completing a General Technical Review._**

  As described in <https://d7y.io/docs/next/#features>, major features that Dragonfly offers are:
  > - **P2P technology**: Based on P2P technology, use the idle bandwidth of Peer to improve download speed.
  > - **Non-intrusive**: Non-intrusive support for multiple container runtimes, download tools, AI infrastructure, etc.
  > - **Peer configuration**: Load limit, concurrent limit, traffic limit, etc. can be configured.
  > - **Consistency**: Ensures downloaded files are consistent even if the user does not check for consistency.
  > - **Exception isolation**: Isolate exceptions based on Service level, Peer level and Task level to improve download stability.
  > - **Ecosystem**: Provides simple integration with AI infrastructure, container runtimes, container registry, download tools, etc.

- [x] **Document and maintain a public roadmap or other forward looking planning document or tracking mechanism.**

  <!-- (TOC Evaluation goes here) -->
  Dragonfly documents the community roadmap at: <https://github.com/dragonflyoss/community/blob/master/ROADMAP.md>

- [ ] **Roadmap change process is documented.**

  <!-- (TOC Evaluation goes here) -->
  The expectations and process for updating the public roadmap over time is outlined in <https://github.com/dragonflyoss/community/blob/master/ROADMAP.md>.

  **TODO for Dragonfly Team:** Need a clear definition about how will the decisions be made, e.g. an item added to a milestone or removed from a milestone.

- [x] **Document overview of project architecture and software design that demonstrates viable cloud native use cases, as part of the project's documentation.  *This requirement may also be satisfied by completing a General Technical Review and capturing the output in the project's documentation.***

  <!-- (TOC Evaluation goes here) -->
  Dragonfly clearly documents the relevant information in the following locations:
  - Architecture: <https://d7y.io/docs/next/operations/deployment/architecture/>
  - Components introduction:
    - manager: <https://d7y.io/docs/next/operations/deployment/applications/manager/>
    - scheduler: <https://d7y.io/docs/next/operations/deployment/applications/scheduler/>
    - client: <https://d7y.io/docs/next/operations/deployment/applications/client/>
  - Quick Start(Kubernetes): <https://d7y.io/docs/next/getting-started/quick-start/kubernetes/>
  - Integrations:
    - containerd: <https://d7y.io/docs/next/operations/integrations/container-runtime/containerd/>
    - cri-o: <https://d7y.io/docs/next/operations/integrations/container-runtime/cri-o/>
    - harbor: <https://d7y.io/docs/next/operations/integrations/harbor/>

- [ ] **Document the project's release process and guidelines publicly in a RELEASES.md or equivalent file that defines:** 

  - [ ] Release expectations (scheduled or based on feature implementation)
  - [ ] Tagging as stable, unstable, and security related releases
  - [ ] Information on branch and tag strategies
  - [ ] Branch and platform support and length of support
  - [ ] Artifacts included in the release.
  - Additional information on topics such as LTS and edge releases are optional. Release expectations are a social contract between the project and its end users and hence changes to these should be well thought out, discussed, socialized and as necessary agreed upon by project leadership before getting rolled out.

  <!-- (TOC Evaluation goes here) -->
  **TODO for Dragonfly Team:** need to provide supportable information for each checklist item.

- [x] **History of regular, quality releases.**

<!-- (TOC Evaluation goes here) -->
History of Dragonfly releases can be found at <https://github.com/dragonflyoss/dragonfly/releases>.

## Security

Note: this section may be augmented by a joint-assessment performed by TAG Security and Compliance.

### Suggested

- [ ] **Achieving OpenSSF Best Practices silver or gold badge.**

<!-- (TOC Evaluation goes here) --> 

### Required

- [x] **Clearly defined and discoverable process to report security issues.**

  <!-- (TOC Evaluation goes here) -->
  Dragonfly documents security policy at <https://github.com/dragonflyoss/community/blob/master/SECURITY.md>.

  **TODO for Dragonlfy TEAM:** This is not blocking, but the TOC reviewer suggests the security policy cross-linked by all the subproject repos.

- [x] **Enforcing Access Control Rules to secure the code base against attacks (Example: two factor authentication enforcement, and/or use of ACL tools.)**

  <!-- (TOC Evaluation goes here) -->
  The dragonflyoss organization has enabled the GitHub setting for "Require two-factor authentication for everyone in the dragonflyoss organization."

- [x] **Document assignment of security response roles and how reports are handled.**

  <!-- (TOC Evaluation goes here) -->
  The response process for security vulnerability disclosure reports is outlined in detail at <https://github.com/dragonflyoss/community/blob/master/SECURITY.md>.

- [x] **Document Security Self-Assessment.**

  <!-- (TOC Evaluation goes here) -->
  Dragonlfy's Security Self-Assessment can be found at: <https://github.com/cncf/tag-security/blob/main/community/assessments/projects/dragonfly/self-assessment.md>.

  The TOC reviewer suggests add a copy to [dragonflyoss/community](https://github.com/dragonflyoss/community)

- [ ] **Third Party Security Review.**

  - [ ] Moderate and low findings from the Third Party Security Review are planned/tracked for resolution as well as overall thematic findings, such as: improving project contribution guide providing a PR review guide to look for memory leaks and other vulnerabilities the project may be susceptible to by design or language choice ensuring adequate test coverage on all PRs.

  <!-- (TOC Evaluation goes here) -->
  A third party security audit was performed by Trail of Bits, ref: <https://github.com/dragonflyoss/dragonfly/blob/main/docs/security/dragonfly-comprehensive-report-2023.pdf>

  **TODO for Dragonfly Team:** need supportable evidence​ of tracking issues and fixes of the findings listed by the security audit report.

- [x] **Achieve the Open Source Security Foundation (OpenSSF) Best Practices passing badge.**

  <!-- (TOC Evaluation goes here) -->
  The passing badge is currently shown as 100%, ref: <https://www.bestpractices.dev/en/projects/10432>

## Ecosystem

### Suggested

N/A

### Required

- [x] **Publicly documented list of adopters, which may indicate their adoption level (dev/trialing, prod, etc.)**

  <!-- (TOC Evaluation goes here) -->
  Dragonlfy documents adopters at <https://github.com/dragonflyoss/dragonfly/blob/main/ADOPTERS.md>.

  **TODO for Dragonfly Team:** Not-blocking: The TOC reviewer suggests include the adoption level for each adopter, e.g. dev/trialing, prod, etc.

- [ ] **Used in appropriate capacity by at least 3 independent + indirect/direct adopters, (these are not required to be in the publicly documented list of adopters)**

  <!-- (TOC Evaluation goes here) -->
  The project provided the TOC with a list of adopters for verification of use of the project at the level expected, i.e. production use for graduation, dev/test for incubation.

- [ ] **TOC verification of adopters.**

  <!-- (TOC Evaluation goes here) -->
  **TODO for TOC Reviewer:** update this when adopters interview finished


Refer to the Adoption portion of this document.

- [x] **Clearly documented integrations and/or compatibility with other CNCF projects as well as non-CNCF projects.**

  <!-- (TOC Evaluation goes here) -->
  Dragonfly documents integrations with many CNCF projects:
  - [Kubernetes](https://d7y.io/docs/next/getting-started/quick-start/kubernetes/) as a hosting platform with the Dragonfly.
  - [Harbor](https://d7y.io/docs/next/operations/integrations/harbor/) preheats image and oci artifacts by Dragonfly.
  - [containerd](https://d7y.io/docs/next/operations/integrations/container-runtime/containerd/) distributes image by Dragonfly.
  - [cri-o](https://d7y.io/docs/next/operations/integrations/container-runtime/cri-o/) distributes image by Dragonfly.
  - [Prometheus](https://d7y.io/docs/next/operations/best-practices/observability/monitoring/) to collect metrics.
  - [Open Telemetry](https://d7y.io/docs/next/operations/best-practices/observability/tracing/) to generate, collect, and export telemetry data.
  - [ArtifactHub](https://artifacthub.io/packages/helm/dragonfly/dragonfly) indexes all versions of Dragonfly's main Helm chart for installation.
  - [gRPC](https://github.com/dragonflyoss/api) for high-performance remote procedure calls (RPC).
  - [Helm](https://d7y.io/docs/next/getting-started/installation/helm-charts/) used to deploy Dragonfly to Kubernetes.
  - [ModelPack](https://github.com/modelpack) distributes model artifacts by Dragonfly.

#### Adoption

##### Adopter 1 - Technology and Content Platform

The adopter started using Dragonfly in production around 2021-2022 when their organization's cloud platform launched it as an official product offering. The interviewee's team began using Dragonfly in 2023 as part of a multi-year cloud migration project. The primary motivation for adopting Dragonfly was to address critical bandwidth constraints on the dedicated network link between on-premise data centers and cloud environments. During the cloud migration, the container registry remained in the internal data center with limited bandwidth (less than 20 Gbps), which frequently became saturated when cloud-based applications pulled container images. Dragonfly was selected over an internal HTTP P2P system for two key reasons: enterprise support and maintenance guarantees from the organization's cloud platform official offering, and a cloud-native deployment model using Helm Charts that significantly reduced operational overhead compared to manual deployment scripts.

Dragonfly has delivered substantial and measurable business value for the adopter. Most critically, it ensured operational stability during the cloud migration project by effectively addressing the bandwidth constraint problem. Without Dragonfly, the migration would have faced significant delays and reliability issues. The deployment achieved remarkable cost savings, reducing bandwidth consumption on the dedicated link from 100% saturation (causing application performance degradation) to approximately 10% utilization. This reduction covered both container image and configuration file traffic. The adopter uses two key features: container registry integration with containerd for transparent image acceleration, and HTTP proxy-based file distribution for configuration files stored in object storage. The adoption experience was smooth, with minimal integration effort required. The team developed a custom SDK using environment variables to enable applications to download files through Dragonfly while maintaining minimal impact on application code.

Looking forward, the adopter plans to maintain active collaboration in the community, including participation in Rust version development. They have identified two key areas for improvement: enhanced observability with additional metrics for large-scale deployments (the team has already added custom metrics internally), and improved multi-cluster support to reduce operational overhead across the adopter's many small-to-medium clusters. The adopter values the community's openness, responsive maintainers, and strong governance under CNCF. They engage actively through GitHub issues, DingTalk, and Slack, with maintainers providing fixes within 2-3 business days for critical issues. The team suggests that Dragonfly could expand beyond container image distribution with richer use case documentation, including detailed case studies showing migration paths from pilot to production, AI/ML workflow integration patterns, and performance tuning guides.

The adopter views Dragonfly's clean architecture, cloud-native deployment model, seamless container registry integration, and strong Nydus ecosystem integration as key strengths. They believe graduating within CNCF would increase visibility and credibility, encouraging broader adoption across the industry.

September, 2025

Note: This adopter preferred to remain anonymous. The interview details are kept in a private file for CNCF TOC review.

##### Adopter 2 - Name / Industry

Adopter 2 was skipped due to scheduling issue.

##### Adopter 3 - Live Streaming and Short Video

The adopter has been using Dragonfly for approximately five years, since 2020. The large-scale production deployment also began in 2020, following extensive canary testing and validation. The primary motivations for adopting Dragonfly were its active community engagement, clear and well-structured architecture design, accessible documentation and codebase, and the strategic partnership with Alibaba Cloud as the primary maintainer. These factors positioned Dragonfly as the preferred P2P distribution solution over alternatives like Kraken, which had become unmaintained by late 2019.

Dragonfly has delivered substantial and measurable benefits across the adopter's infrastructure, deployed in full production to support over 80% of their internal services. The organization has publicly disclosed significant performance improvements in three key areas: reduced Harbor registry bandwidth pressure by approximately 70% on average (up to 80% during peak periods) through P2P distribution; lowered overall image pull costs by approximately 90%, including network, storage, bandwidth, and transfer resources; and accelerated instance startup times by an average of 50%. The system currently supports three primary use cases: general object storage acceleration for big data and multimedia distribution, cloud-native container image acceleration and distribution, and AI model file distribution introduced in 2025. Key features utilized include proactive image preheating, multi-tier caching from memory to SSD for enhanced P2P efficiency, and Nydus on-demand loading which has enabled approximately 60% of their services to achieve more than 50% reduction in startup time.

Regarding future community participation, the adopter has already achieved comprehensive deployment across its infrastructure and plans to focus on feature requests and potential community contributions. The team's approach is to first submit feature requests to understand the community's perspective and roadmap alignment, with readiness to invest engineering resources for significant implementations. A specific example includes their request for P2P distribution support for large model parameter files within Dragonfly, similar to vLLM's P2P store functionality, which would enable framework-agnostic integration and reduce development costs. The organization actively engages with the community through GitHub issues, DingTalk group discussions, and participation in community meetings. Team members have already contributed pull requests and documentation improvements, and they express preference for community collaboration over isolated internal maintenance. The adopter suggests two areas for project improvement: evolving capabilities to better address emerging AI workload requirements and adding multilingual documentation support to improve accessibility for non-English-speaking regions. They also recommend encouraging involvement from excellent international companies to broaden the community's perspective and conducting deeper academic research exploration to identify new enhancement opportunities.

September, 2025

Note: Adopter 3 need to double check if they prefer remain anonymous, currently the interview details are kept in a private file for CNCF TOC review.

##### Adopter 4 - Cloud Computing Platform

This adopter started using Dragonfly in production around early 2019, implementing Dragonfly v1.0 initially and has been using the project for approximately 6 years. The organization has since evolved to Dragonfly v2.x and currently runs v2.2.0 in production. The primary motivation for adopting Dragonfly was to resolve critical stability issues with their previous Java-based P2P solution, specifically eliminating back-to-source contention caused by randomized scheduling that created substantial load on origin servers during high concurrency periods.

Dragonfly has delivered significant business value across multiple dimensions. The system now supports millions of client machines with daily download volumes reaching petabyte scale, while consistently maintaining back-to-source traffic below 1% of total download volume. This translates to massive cost savings in OSS bandwidth consumption and associated cloud storage costs. Additionally, Dragonfly eliminated complex manual network configuration requirements, dramatically reducing operational staff time and labor costs. The solution has successfully supported critical peak traffic events, including multiple "Double 11" sales periods, demonstrating its enterprise-grade stability.

The adopter plans to maintain active collaboration in the community, focusing on issue triage and performance optimization discussions to ensure long-term stability. They have no new major feature requests as the core P2P distribution functionality fully meets their infrastructure needs. For future development, they suggest the project could benefit from expanding influence through comprehensive best practice case studies and exploring deeper integration with AI workflows, particularly for efficient distribution of large model binaries and datasets.

The adopter views Dragonfly as having significant growth potential, especially with the rise of multi-cloud, edge computing, and AI model distribution challenges. They praise the community's openness, strong governance, and timely maintainer responsiveness, while noting that enhanced security and access control mechanisms would help unlock the project's full potential across diverse enterprise environments.

September, 2025

Note: This adopter preferred to remain anonymous. The interview details are kept in a private file for CNCF TOC review.

##### Adopter 5 - AI/Large Language Model Infrastructure

This adopter started using Dragonfly approximately one and a half years ago, beginning with v1.x and recently upgrading to v2.3. The primary motivation for adopting Dragonfly was to address critical challenges in large-scale image distribution for AI model training infrastructure. During their research phase, they found limited alternatives that could effectively accelerate image distribution at scale. Dragonfly stood out due to its proven track record among large companies, CNCF project reliability, cloud-native deployment capabilities, and being written in Go for potential customization. The interviewee's prior successful experience with Dragonfly at their previous company further validated the adoption decision.

Dragonfly has delivered substantial business value across multiple dimensions for this AI-focused organization. The system is deployed in production as a key infrastructure component across all computing clusters, supporting large-scale model training operations. The P2P distribution capability has generated significant bandwidth savings and cost reductions. Most importantly, Dragonfly has dramatically improved training task startup success rates by alleviating pressure on upstream registries and reducing image pull failures and timeouts - critical factors for large-scale AI training workloads. Pod startup speeds have been significantly accelerated, and the solution has reduced operational burden for the infrastructure team. The organization considers Dragonfly essential to their operations, with deployment described as very large scale, though specific metrics remain confidential.

The adopter maintains active engagement with the Dragonfly community and plans to continue this collaboration. They consistently provide feedback on issues encountered, such as network file system compatibility problems that were quickly resolved by community developers. Looking forward, they are particularly interested in AI/ML-specific acceleration features, especially capabilities for large language model distribution and accelerating model weight distribution. The organization suggests the project could further strengthen its position in the AI infrastructure space by developing technical solutions tailored to large model distribution scenarios. They emphasize the value of timely Chinese documentation synchronization and improved support for legacy container runtime interfaces.

The adopter highly values the community's openness, mature governance, maintainer diversity, and responsive communication channels. They praise the fast response times and enthusiastic developer engagement through multiple channels including DingTalk, GitHub, and biweekly meetings. The organization relies on CNCF maturity levels as a strong reference point for adoption decisions, prioritizing Graduated projects for production deployments. They view Dragonfly's community and technical capabilities as well-aligned with the growing demands of AI infrastructure, particularly for efficient distribution in large-scale model training environments.

September, 2025

Note: This adopter preferred to remain anonymous. The interview details are kept in a private file for CNCF TOC review.
