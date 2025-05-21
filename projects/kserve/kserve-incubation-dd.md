# KServe Incubation Due Diligence

- Link to [Incubation application issue](https://github.com/cncf/toc/issues/1367)

<!-- This template provides the TOC with the outline for completing due diligence of a project to move levels. This universal template is designed to capture all criteria so the TOC may ensure prior level criteria do not regress. As part of completing the due diligence, the TOC member should update the template to convey the level the project applied for the criteria by bolding the level indicated where the criteria is relevant. -->

## Incubation Evaluation Summary for KServe

### Criteria Evaluation

_$TOCMEMBER conducted the due diligence of KServe who applied for $LEVEL. The project [has/has not] completed the criteria that show its maturity at $LEVEL. The following criteria implementations are noteworthy to call out... $NOTABLES. The following actions were provided to the project that were considered blocking but since resolved... $BLOCKERS. The following recommendations were provided to the project that are non-blocking in the TOC's assessment but should be completed by the project to ensure continued viability of the project... $RECOMMENDATIONS._

### Adoption Evaluation

_The adopter interviews reflect a project [in use/too early] for the level which the project applied. They show ... $INTERVIEWSUMMARY._

### Final Assessment

_[The TOC has found the project to have satisfied the criteria for $LEVEL/ The TOC's evaluation of the project shows a needed focus to complete the outstanding blockers and reapply when the following conditions are met ... $CONDITIONS]._

## Application Process Principles

### Suggested

N/A

### Required

- [ ] **Give a presentation and engage with the domain specific TAG(s) to increase awareness**
  - This was completed and occurred on DD-MMM-YYYY, and can be discovered at $LINK.

  <!-- (TOC Evaluation goes here) -->  

  **TODO for KServe team**: Provide GTR/DTR files

- [ ] **TAG provides insight/recommendation of the project in the context of the landscape**

  <!-- (TOC Evaluation goes here) -->  
  **TODO for KServe team**: fill GTR/DTR

  **TODO for Kevin**: check with TAG runtime to provide recommendation

- [ ] **All project metadata and resources are [vendor-neutral](https://contribute.cncf.io/maintainers/community/vendor-neutrality/).**

  <!-- (TOC Evaluation goes here) -->  
  Yes. KServe is utilizing vendor neutral resources for communication, testing, hosting and governance.

  **TODO for KServe team**: provide links do prove this.

- [ ] **Review and acknowledgement of expectations for [Sandbox](sandbox.cncf.io) projects and requirements for moving forward through the CNCF Maturity levels.**  

  <!-- (TOC Evaluation goes here) -->  
  - The project contacts and TOC Reviewers had a kick-off meeting on Feb. 18th, set expectations and discussed general steps & timelines.
  - **TODO for Kevin**: summarize and describe the meetings hold during application process

- [ ] **Due Diligence Review.**

  Completion of this due diligence document, resolution of concerns raised, and presented for public comment satisifies the Due Diligence Review criteria.

- [x] **Additional documentation as appropriate for project type, e.g.: installation documentation, end user documentation, reference implementation and/or code samples.**

  <!-- (TOC Evaluation goes here) -->
  Refer to the following links:
  - Installation: https://kserve.github.io/website/latest/admin
  - End user documentation: https://kserve.github.io/website/master/modelserving/control_plane/
  - Blog posts: https://kserve.github.io/website/master/blog/articles/2024-05-15-KServe-0.13-release/

## Governance and Maintainers

Note: this section may be augmented by the completion of a Governance Review from TAG Contributor Strategy.

### Suggested

- [x] **Clear and discoverable project governance documentation.**

  <!-- (TOC Evaluation goes here) --> 
  KServe project documents its open govermance at [KSERVE-TECHICAL-CHARTER.md](https://github.com/kserve/community/blob/main/KSERVE-TECHICAL-CHARTER.md)

- [ ] **Governance has continuously been iterated upon by the project as a result of their experience applying it, with the governance history demonstrating evolution of maturity alongside the project's maturity evolution.**

  KServe project Governance has iterated organically as it has gained experienced over the years. Contributor Roles and contributor ladder processes are streamlined over the past years as well as team member onboarding/offboarding process is well defined. The Project has currently 15 active committers and maintainers and it has received contributions from 267 contributors who come from different companies.

  <!-- (TOC Evaluation goes here) --> 
  KServe Technical Steering Committee was established in Apr. 2025. <https://github.com/kserve/community/pull/18>

  **TODO for KServe team**: provide links as references.

- [ ] **Governance is up to date with actual project activities, including any meetings, elections, leadership, or approval processes.**

  <!-- (TOC Evaluation goes here) --> 
  Governance is up to date and KServe project has been running [bi-weekly community meeting](https://github.com/kserve/community/tree/main?tab=readme-ov-file#community-meeting) for 5 years now. KServe also regularly promote contributors with the established voting and approval process.

  **TODO for KServe team**: provide links that show how KServe promote contributors.

- [ ] **Governance clearly documents [vendor-neutral](https://contribute.cncf.io/maintainers/community/vendor-neutrality/) of project direction.**

  <!-- (TOC Evaluation goes here) --> 
  [KSERVE-TECHNICAL-CHARTER.md](https://github.com/kserve/community/blob/main/KSERVE-TECHNICAL-CHARTER.md) doesn't document vendor neutrality of project direction.

  **TODO for KServe team**: need update this

- [ ] **Document how the project makes decisions on leadership, contribution acceptance, requests to the CNCF, and changes to governance or project goals.**

  <!-- (TOC Evaluation goes here) --> 
  - The project decisions are discussed in open issues and we use gitvote process to make the final decision. 
     For example: [requests to the CNCF](https://github.com/kserve/community/issues/10)

- [ ] **Document how role, function-based members, or sub-teams are assigned, onboarded, and removed for specific teams (example: Security Response Committee).**

  <!-- (TOC Evaluation goes here) --> 
  KServe uses the GitHub team to manage the roles and remembers, for example `kserve-security` team  responses to the security issues.

  **TODO for KServe team**: Provide more information, not just security

- [ ] **Document a complete maintainer lifecycle process (including roles, onboarding, offboarding, and emeritus status).**

  <!-- (TOC Evaluation goes here) --> 

  The role promotion process is documented [here](https://github.com/kserve/community/blob/main/CONTRIBUTING.md#becoming-a-committer)

  **TODO for Kevin**: review the doc content

- [x] **Demonstrate usage of the maintainer lifecycle with outcomes, either through the addition or replacement of maintainers as project events have required.**

  <!-- (TOC Evaluation goes here) -->
  - Updates to the KServe OWNER file can be found at: <https://github.com/kserve/kserve/commits/master/OWNERS>
  
  - Some of the good examples are:
    - Add new PR reviewers and approvers: <https://github.com/kserve/kserve/pull/3213>
    - Update list of reviewers according to activities: <https://github.com/kserve/kserve/pull/3484>
    - PR that adds the promoted maintainers: <https://github.com/kserve/kserve/pull/3966>

- [ ] **If the project has subprojects: subproject leadership, contribution, maturity status documented, including add/remove process.**

  <!-- (TOC Evaluation goes here) -->
  The mainatiners listed the following 2 subprojects, however no descriptions or rules about subprojects found in the [KSERVE-TECHNICAL-CHARTER.md]:
  - KServe ModelMesh:  Yuan Tang, [terrytangyuan@gmail.com](mailto:terrytangyuan@gmail.com)
  - KServe Open Inference Protocol: Dan Sun [dsun20@bloomberg.net](mailto:dsun20@bloomberg.net)

  **TODO for KServe team**: this is not blocking but suggested to document subproject leadership, contribution, maturity status, including add/remove process.

### Required

- [x] **Document complete list of current maintainers, including names, contact information, domain of responsibility, and affiliation.**

  <!-- (TOC Evaluation goes here) -->
  KServe has a clear [KServe maintainers.md](https://github.com/kserve/community/blob/main/MAINTAINERS.md) file for all the maintainer relevant information.

- [x] **A number of active maintainers which is appropriate to the size and scope of the project.**

  <!-- (TOC Evaluation goes here) -->
  The "Contributor Leaderboard" in [LFX insights - KServe](https://insights.lfx.linuxfoundation.org/foundation/lf-ai-foundation/overview/github?project=kserve&routedFrom=Github&bestPractice=false&repository=all&dateFilters=2024-05-01%20to%202025-05-01&dateRange=2024-05-01%20to%202025-05-01&compare=PP&granularity=month&hideBots=true) shows that the current maintainers are active.

- [x] **Code and Doc ownership in Github and elsewhere matches documented governance roles.**

  <!-- (TOC Evaluation goes here) --> 
  KServe uses the OWNERS file to manage code and doc approval access among approvers and reviewers, and clearly matches documented governance roles.
  - Code owners:
    - KServe: https://github.com/kserve/kserve/blob/master/OWNERS
    - modelmesh serving: https://github.com/kserve/modelmesh-serving/blob/main/OWNERS
    - models web apphttps://github.com/kserve/models-web-app/blob/master/OWNERS
  - Doc owners:
    - website: https://github.com/kserve/website/blob/main/OWNERS

- [ ] **Document agreement that project will adopt CNCF Code of Conduct.**

  <!-- (TOC Evaluation goes here) -->
  KServe has documented their adoption of CNCF Code of Conduct, in [CONTRIBUTING.md#code-of-conduct](https://github.com/kserve/community/blob/main/CONTRIBUTING.md#code-of-conduct).

  The TOC reviewer suggests adding this description to [KSERVE-TECHNICAL-CHARTER.md](https://github.com/kserve/community/blob/main/KSERVE-TECHNICAL-CHARTER.md)

  **TODO for KServe team**: create a `CODE_OF_CONDUCT.md` file at the root level of each repository

- [ ] **CNCF Code of Conduct is cross-linked from other governance documents.**

  <!-- (TOC Evaluation goes here) -->
  The TOC reviewer suggests placing a `CODE_OF_CONDUCT.md` file at the root level of each repository, for accessibility and clarity consideration.
  
  **TODO for KServe team**: create a `CODE_OF_CONDUCT.md` file at the root level of each repository

- [ ] **All subprojects, if any, are listed.**

  <!-- (TOC Evaluation goes here) -->
  KServe has the following subprojects:
  - ModelMesh: https://github.com/kserve/modelmesh-serving
  - Open Inference Protocol: https://github.com/kserve/open-inference-protocol

  **TODO for KServe team**: find a place to document the list of subprojects.

## Contributors and Community

Note: this section may be augmented by the completion of a Governance Review from TAG Contributor Strategy.

### Suggested

- [x] **Contributor ladder with multiple roles for contributors.**

  <!-- (TOC Evaluation goes here) -->  
  The project describes its contributor ladder in [membership.md](https://github.com/kserve/community/blob/main/membership.md). Contributor roles include "member", "reviewer", "approver" and "leader".
  Requirements and recruiting/retiring process are clearly documented.

### Required

- [x] **Clearly defined and discoverable process to submit issues or changes.**

  <!-- (TOC Evaluation goes here) -->  
  The project describes issue and PR process in its [Contribution Guide](https://github.com/kserve/community/blob/main/CONTRIBUTING.md).

- [x] **Project must have, and document, at least one public communications channel for users and/or contributors.**

  <!-- (TOC Evaluation goes here) -->  
  Communication channels are documented at <https://github.com/kserve/community?tab=readme-ov-file#questions-and-issues>

- [ ] **List and document all project communication channels, including subprojects (mail list/slack/etc.).  List any non-public communications channels and what their special purpose is.**

  <!-- (TOC Evaluation goes here) --> 
  **TODO for KServe Team:** KServe doesn't have a unified place listing and documenting all project communication channels, suggested to provide if there is, or determin a file for this purpose.

- [x] **Up-to-date public meeting schedulers and/or integration with CNCF calendar.**

 <!-- (TOC Evaluation goes here) -->  
  KServe uses [LFX calendar](https://zoom-lfx.platform.linuxfoundation.org/meetings/kserve?view=month) for running community meeting.
  The [readme of kserve/community repo](https://github.com/kserve/community#community-meeting) clearly documents meeting time, meeting link, community calendar, and meeting notes:

  > You can also find these meetings on [the community calendar](https://zoom-lfx.platform.linuxfoundation.org/meetings/kserve?view=month), along with other major community events.
  >
  > Meeting agendas and notes can be accessed in the [working group document](https://docs.google.com/document/d/1KZUURwr9MnHXqHA08TFbfVbM8EAJSJjmaMhnvstvi-k).
  >
  > You can access the meeting recordings on [the community calendar](https://zoom-lfx.platform.linuxfoundation.org/meetings/kserve?view=month) by clicking on the respective date's event details.

- [x] **Documentation of how to contribute, with increasing detail as the project matures.**

  <!-- (TOC Evaluation goes here) -->  
  KServe has a cleary contribute guide at <https://github.com/kserve/community/blob/main/CONTRIBUTING.md>

- [x] **Demonstrate contributor activity and recruitment.**

  <!-- (TOC Evaluation goes here) --> 
  The project [contributor guide](https://github.com/kserve/community/blob/main/CONTRIBUTING.md#project-membership) describes an activity based project membership recruitment.  
  Two examples of using the contributor activity data are:  
  - Update list of reviewers according to activities: <https://github.com/kserve/kserve/pull/3484>
  - PR that adds the promoted maintainers: <https://github.com/kserve/kserve/pull/3966>

## Engineering Principles

### Suggested

- [ ] **Roadmap change process is documented.**

  <!-- (TOC Evaluation goes here) --> 
  KServe 2024-2025 roadmap is captured at https://github.com/kserve/kserve/blob/master/ROADMAP.md, the [Governance document](https://github.com/kserve/community/blob/main/KSERVE-TECHNICAL-CHARTER.md) does not seem to cover how the Roadmap is created or how changes to project roadmap is handled.

  **TODO for KServe Team:** It is not mandatory, but recommended to document the Roadmap change process.

- [x] **History of regular, quality releases.**

  <!-- (TOC Evaluation goes here) --> 
  KServe follows quarterly releases as per https://github.com/kserve/kserve/releases and https://github.com/kserve/kserve/tags. Even though the release process from a development perspective is captured under : https://github.com/kserve/kserve/blob/master/release/RELEASE_PROCESS_v2.md, it is recommended to document at a high level the frequency/type of releases and support windows also.

### Required 

- [x] **Document project goals and objectives that illustrate the project’s differentiation in the Cloud Native landscape as well as outlines how this project fulfills an outstanding need and/or solves a problem differently.**

  <!-- (TOC Evaluation goes here) --> 
  KServe project goals, objectives and how it fits in the Cloud Native landscape are well captured under https://github.com/kserve/kserve?tab=readme-ov-file#why-kserve  

- [x] **Document what the project does, and why it does it - including viable cloud native use cases.**

  <!-- (TOC Evaluation goes here) --> 
  The high level usage of the project is captured at https://github.com/kserve/kserve?tab=readme-ov-file#kserve . The project website also contains good documentation : https://kserve.github.io/website/latest/ on usage, and administration. The project also has done a good job in capturing various KServe usages, demos and presentations at https://kserve.github.io/website/master/community/presentations/ . The project also lists adopters at https://kserve.github.io/website/latest/community/adopters.

- [x] **Document and maintain a public roadmap or other forward looking planning document or tracking mechanism.**

  <!-- (TOC Evaluation goes here) --> 
  KServe has documented their 2024-2025 roadmap in https://github.com/kserve/kserve/blob/master/ROADMAP.md and the major highlights include:

  1.	Support GenAI inference
  2.	Graduate core inference capability to stable/GA
  3.	Graduate KServe Python SDK to 1.0
  4.	Graduate InferenceGraph
  5.	Secure InferenceService
  6.	Improve KServe 1.0 documentation

  Feature Request process is also documented clearly at : [community/CONTRIBUTING.md at main · kserve/community](https://github.com/kserve/community/blob/main/CONTRIBUTING.md#contributing-a-feature). However roadmap document is present only for 2024-2025 and not previous years. Hoping that 2024-2025 trend continues, and roadmaps are similarly published for upcoming years too to indicate a healthy project.Similarly, it is recommended to mention the roadmap change process in the Governance document.

- [x] **Document overview of project architecture and software design that demonstrates viable cloud native use cases, as part of the project's documentation.**

  <!-- (TOC Evaluation goes here) --> 
  KServe website has detailed information on the project architecture and design at the User Guide section. For eg: https://kserve.github.io/website/latest/modelserving/control_plane/ and https://kserve.github.io/website/latest/modelserving/data_plane/data_plane.

- [ ] **Document the project's release process.**

  <!-- (TOC Evaluation goes here) --> 
  The release process for KServe is documented here: https://github.com/kserve/kserve/blob/master/release/RELEASE_PROCESS_v2.md. It is recommended to rename this to RELEASE.md, as there are no references to v1 release process in the repo, and hence the current name might be misleading. Also in the release process, it would be nice to have an initial section which is easy to follow for KServe users on – frequency of the releases, supported releases, support policy, types of releases(in case Beta support), eol announcements etc. It would be also nice to mention that the whole process outlined in the release document is performed by authorized people - ie, release managers who are chosen per release (preferably in a step outlined in the governance document). There seems to be detailed blogs about the release process upto v0.14: https://kserve.github.io/website/0.14/blog/articles/2024-12-13-KServe-0.14-release/. The same for v0.15 is missing, however assuming that to be in place soon.

  **TODO for KServe Team:** Add information about release frequency, supported releases, support policy etc to the release process document.

## Security

Note: this section may be augemented by a joint-assessment performed by TAG Security.

### Suggested

N/A

### Required

- [ ] **Clearly defined and discoverable process to report security issues.**

<!-- (TOC Evaluation goes here) --> 
KServe’s security vulnerability reporting process is outlined at [kserve/SECURITY.md at master · kserve/kserve](https://github.com/kserve/kserve/blob/master/SECURITY.md). The mail id is currently under lfaidata foundation, it is recommended to move to a CNCF domain at the appropriate time.

**TODO for KServe Team:**
1. Add SECURITY.md to all relevant repos and not just kserve/kserve.
2. Link SECURITY.md from all contributor guides across github and the KServe website. For eg: https://github.com/kserve/community?tab=readme-ov-file#questions-and-issues, https://kserve.github.io/website/0.15/developer/developer/ and https://github.com/kserve/community/blob/main/CONTRIBUTING.md#issues. All of them does not seem to have uniform information and how to report security vulnerabilty should be part of them.

- [ ] **Enforcing Access Control Rules to secure the code base against attacks (Example: two factor authentication enforcement, and/or use of ACL tools.)**

<!-- (TOC Evaluation goes here) --> 
Access control is enforced via OWNERS file [kserve/OWNERS at master · kserve/kserve](https://github.com/kserve/kserve/blob/master/OWNERS) for Kserve repo and most of the other repos. (would have been better to name this CODEOWNERS), and the respective roles are specified in https://github.com/kserve/community/blob/main/membership.md#community-membership.

Members of KServe organization are required to enable two factor authentication [community/membership.md at main · kserve/community](https://github.com/kserve/community/blob/main/membership.md#requirements) in their Github account.

**TODO for KServe Team:**
1. Add OWNERS file to kserve/community repo.

- [ ] **Document assignment of security response roles and how reports are handled.**

<!-- (TOC Evaluation goes here) --> 

https://github.com/kserve/kserve/blob/master/SECURITY.md specifies that only active maintainers of the project has access to reported security vulnerabilities. However the SECURITY.md is very minimal without much information on Supported versions, Prevention Mechanisms, Private/Public Disclosure Process and time taken for mitigation, and Communication channels used for the disclosure.

**TODO for KServe Team:**

1. Enhance SECURITY.md with more information as suggested above.

- [ ] **Document Security Self-Assessment.**

<!-- (TOC Evaluation goes here) --> 

KServe Security Self Assessment is available at https://github.com/kserve/community/blob/main/security/self-assessment.md.

**TODO for KServe Team:**

1. Link to the CI/CD generated SBOMs at https://github.com/kserve/community/blob/main/security/self-assessment.md#software-bill-of-materials
2. Clarify if the generated docker images are scanned for security vulnerabilities at https://github.com/kserve/community/blob/main/security/self-assessment.md#development-pipeline
3. CONTRIBUTING.md should also include information about how to report security vulnerabilties at https://github.com/kserve/community/blob/main/security/self-assessment.md#development-pipeline
   
- [x] **Achieve the Open Source Security Foundation (OpenSSF) Best Practices passing badge.**

<!-- (TOC Evaluation goes here) --> 

KServe has obtained OpenSSF Best Practicess passing badge: https://www.bestpractices.dev/en/projects/6643

## Ecosystem

### Suggested

N/A

### Required

- [ ] **Publicly documented list of adopters, which may indicate their adoption level (dev/trialing, prod, etc.)**

<!-- (TOC Evaluation goes here) --> 

- [ ] **Used in appropriate capacity by at least 3 independent + indirect/direct adopters, (these are not required to be in the publicly documented list of adopters)**

<!-- (TOC Evaluation goes here) --> 

The project provided the TOC with a list of adopters for verification of use of the project at the level expected, i.e. production use for graduation, dev/test for incubation.

- [ ] **TOC verification of adopters.**

<!-- (TOC Evaluation goes here) --> 

Refer to the Adoption portion of this document.

- [ ] **Clearly documented integrations and/or compatibility with other CNCF projects as well as non-CNCF projects.**

<!-- (TOC Evaluation goes here) --> 

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
