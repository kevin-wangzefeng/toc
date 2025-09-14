# Dragonfly Graduation Due Diligence

- Link to [Graduation application issue](https://github.com/cncf/toc/issues/1358)

<!-- This template provides the TOC with the outline for completing due diligence of a project to move levels. This universal template is designed to capture all criteria so the TOC may ensure prior level criteria do not regress. As part of completing the due diligence, the TOC member should update the template to convey the level the project applied for the criteria by bolding the level indicated where the criteria is relevant. -->

## Graduation Evaluation Summary for Dragonfly

### Criteria Evaluation

_$TOCMEMBER conducted the due diligence of Dragonfly who applied for $LEVEL. The project [has/has not] completed the criteria that show its maturity at $LEVEL. The following criteria implementations are noteworthy to call out... $NOTABLES. The following actions were provided to the project that were considered blocking but since resolved... $BLOCKERS. The following recommendations were provided to the project that are non-blocking in the TOC's assessment but should be completed by the project to ensure continued viability of the project... $RECOMMENDATIONS._

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

  **TODO for Dragonfly team:** "requests to the CNCF, and changes to governance or project goals" not found.

- [x] **Document how role, function-based members, or sub-teams are assigned, onboarded, and removed for specific teams (example: Security Response Committee).**

  <!-- (TOC Evaluation goes here) -->
  Dragonfly describes the basic roles, responsibilies, and how to become on the role in the [community ladder](https://github.com/dragonflyoss/community/blob/master/COMMUNITY_LADDER.md).

  **TODO for Dragonfly Team:** there's duplicated definitions of "Adding New Member/Approver/Maintainer" in the community documents:
  - location 1: <https://github.com/dragonflyoss/community/blob/master/COMMUNITY_LADDER.md?plain=1#L164>
  - location 2: <https://github.com/dragonflyoss/community/blob/master/COMMUNITY_MEMBERSHIP.md#adding-new-memberapprovermaintainer>
  It's suggested to consolicate, and implement single source of truth.

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

  **TODO for Dragonfly team:** nydas looks like a subproject, if it isn't, it shall be stated as well what it is to the Dragonfly community.

- [ ] **If the project has subprojects: subproject leadership, contribution, maturity status documented, including add/remove process.**

  <!-- (TOC Evaluation goes here) -->
  **TODO for Dragonfly team:** Ref the question above

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

- [ ] **Document project goals and objectives that illustrate the project’s differentiation in the Cloud Native landscape as well as outlines how this project fulfills an outstanding need and/or solves a problem differently. _This requirement may also be satisfied by completing a General Technical Review._**
  - _If applicable_ A General Technical Review was completed/updated on DD-MMM-YYYY, and can be discovered at $LINK.

<!-- (TOC Evaluation goes here) --> 

- [ ] **Document what the project does, and why it does it - including viable cloud native use cases. _This requirement may also be satisfied by completing a General Technical Review._**
  - _If applicable_ a General Technical Review was completed/updated on DD-MMM-YYYY, and can be discovered at $LINK.

- [ ] **Document and maintain a public roadmap or other forward looking planning document or tracking mechanism.**

<!-- (TOC Evaluation goes here) --> 

- [ ] **Roadmap change process is documented.**

<!-- (TOC Evaluation goes here) --> 

- [ ] **Document overview of project architecture and software design that demonstrates viable cloud native use cases, as part of the project's documentation.  *This requirement may also be satisfied by completing a General Technical Review and capturing the output in the project's documentation.***
  -  _If applicable_ a general Technical Review was completed/updated on DD-MMM-YYYY, and can be discovered at $LINK.

<!-- (TOC Evaluation goes here) --> 

- [ ] **Document the project's release process and guidelines publicly in a RELEASES.md or equivalent file that defines:** 

  - [ ] Release expectations (scheduled or based on feature implementation)
  - [ ] Tagging as stable, unstable, and security related releases
  - [ ] Information on branch and tag strategies
  - [ ] Branch and platform support and length of support
  - [ ] Artifacts included in the release.
  - Additional information on topics such as LTS and edge releases are optional. Release expectations are a social contract between the project and its end users and hence changes to these should be well thought out, discussed, socialized and as necessary agreed upon by project leadership before getting rolled out.

<!-- (TOC Evaluation goes here) --> 

- [ ] **History of regular, quality releases.**

<!-- (TOC Evaluation goes here) --> 

## Security

Note: this section may be augmented by a joint-assessment performed by TAG Security and Compliance.

### Suggested

- [ ] **Achieving OpenSSF Best Practices silver or gold badge.**

<!-- (TOC Evaluation goes here) --> 

### Required

- [ ] **Clearly defined and discoverable process to report security issues.**

<!-- (TOC Evaluation goes here) --> 

- [ ] **Enforcing Access Control Rules to secure the code base against attacks (Example: two factor authentication enforcement, and/or use of ACL tools.)**

<!-- (TOC Evaluation goes here) --> 

- [ ] **Document assignment of security response roles and how reports are handled.**

<!-- (TOC Evaluation goes here) --> 

- [ ] **Document Security Self-Assessment.**

<!-- (TOC Evaluation goes here) --> 

- [ ] **Third Party Security Review.**

  - [ ] Moderate and low findings from the Third Party Security Review are planned/tracked for resolution as well as overall thematic findings, such as: improving project contribution guide providing a PR review guide to look for memory leaks and other vulnerabilities the project may be susceptible to by design or language choice ensuring adequate test coverage on all PRs.

<!-- (TOC Evaluation goes here) --> 

- [ ] **Achieve the Open Source Security Foundation (OpenSSF) Best Practices passing badge.**

<!-- (TOC Evaluation goes here) --> 

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
