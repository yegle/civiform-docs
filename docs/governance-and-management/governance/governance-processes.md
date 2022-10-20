# Governance Processes
The following processes describe how project plans and decisions are made. The Stewarding Organization is responsible for facilitating these processes.
* Product planning and prioritization
* Product design decisions
* Technical design decisions

## Product Planning and Prioritization
Project-wide planning and prioritization is managed by the Product Design Committee and is dictated by the needs of Users and Member Organizations. Quarterly [product roadmap](https://github.com/orgs/civiform/projects/1/views/11) decisions are planned and prioritized as follows:

1. **Feature requests are submitted** as [new issues via GitHub](https://github.com/civiform/civiform/issues/new/choose). 
    * Ideas and proposals for new features may initially be shared ad-hoc in meetings or via other communication channels, but a Maintainer from the Product Design Committee is responsible for consolidating them into the [GitHub issue tracker](https://github.com/civiform/civiform/issues?q=is%3Aopen+is%3Aissue+label%3Afeature).
2. **Initial prioritization and consolidation** against the current product roadmap is done weekly by the Product Design committee.
3. **Final prioritization** is informed by feedback from key sources:
    * **Member Organizations**: Product needs and relative importance of features.
    * **Governance Committee**: Collective prioritization of features.
    * **Technical Design Committee**: Technical feasibility and level-of-effort of features.
    * **Users**: Detailed needs and requirements for a given feature.
    * Broader observed trends across the government and technical landscape.
 
    Mechanisms for feedback include:
    * Direct consultation with Member Organizations.
    * Discussion or polls via [email lists and Slack](https://docs.civiform.us/governance-and-management/governance/communication). 
    * Demos, reviews, and discussions in [Governance Committee meetings](https://docs.google.com/document/d/1MQikQy2I77IOEh_FCIG0pH6IDPC_nNtiJphAOychY0Q/edit#heading=h.u8srcsjo65zj).
    * Remaining ambiguities should be resolved by [agreed-upon prioritization criteria](https://docs.google.com/document/d/1I47tNPSylU2MtABXJfRQfXPApM3LH5vDXv2uSUhRj8M/edit). 

4. **Approval of product roadmap** on a quarterly basis through simple majority vote by Member Organizations in the Governance Committee.

    ### RACI for Product Planning & Prioritization
    |Committee|Initial Prioritization|Final Prioritization|Approval|
    |------------|-------|-----------|-----------|
    |**Governance**|Informed|Consulted|Accountable|
    |**Product Design**|Responsible|Responsible|Responsible|
    |**Technical Design**|Informed|Consulted|Informed|


## Product Design Decisions
The design of major product features must be developed publicly and collaboratively across the project. The following process describes how new features should be designed, reviewed, and approved:

1. **Product Requirements Documents** (PRDs) are developed and authored by members of the Product Design Committee. Initial authorship is informed by research among Users and Member Organizations.
2. **PRDs are reviewed** for a period of up to X weeks by the Governance and Technical Design Committees.
3. **PRDs are finalized** after incorporating feedback from reviewers. Finalized PRDs are saved in the Public Drive and added as links in the [public product roadmap](https://github.com/orgs/civiform/projects/1/views/11).
4. **PRDs are approved** by simple majority vote from Member Organizations in the Governance Committee.


    ### RACI for Product Design Decisions
    |Committee|Author PRDs|Review|Finalize|Approve|
    |------------|-------|-----------|-----------|------|
    |**Governance**|Informed|Responsible|Consulted|Accountable|
    |**Product Design**|Responsible|Responsible|Responsible|Responsible|
    |**Technical Design**|Informed|Responsible|Consulted|Informed|
    
## Technical Design Decisions
Major technical design decisions are reviewed and approved by a majority of the Technical Design Committee. The committee holds ad hoc forums for maintainers to advise contributors on technical decisions and will determine what constitutes a major technical design decision by majority vote if necessary. 

Types of technical design decisions that require approval:
* Authentication & authorization (e.g. User Account identification)
* Technical aspects of new features (e.g. program discovery or automated eligibility screening system)
* Major changes to existing features (e.g. Admin UX overhaul)
* Major changes to technical approach (e.g. introducing a new library, tool, or major software design pattern)
* How new infrastructure will connect with existing infrastructure (e.g. API design)

    ### RACI for Technical Design Decisions
    |Committee|Author PRDs|Review|Finalize|Approve|
    |------------|-------|-----------|-----------|------|
    |**Governance**|Informed|Consulted|Consulted|Informed|
    |**Product Design**|Consulted|Consulted|Consulted|Consulted|
    |**Technical Design**|Responsible|Responsible|Responsible|Accountable|
