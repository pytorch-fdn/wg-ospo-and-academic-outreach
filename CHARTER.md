# PyTorch Foundation OSPO & Academic Outreach Program Charter

## 1) Background and Context

The PyTorch Foundation is part of the Linux Foundation and operates with formal member governance (Governing Board) and a Technical Advisory Council (TAC) that coordinates technical collaboration across Foundation technical projects.

The Foundation’s portfolio includes PyTorch and additional foundation-hosted projects spanning key parts of the AI lifecycle:

- vLLM (inference/serving)
- DeepSpeed (training/orchestration)
- Ray (distributed execution)

## 2) Program Purposes

Establish an OSPO and Academic Outreach function within the PyTorch Foundation to:

- Educate academia on open source AI best practices (governance, licensing, security, community operations, and sustainable maintainer practices) for students, researchers, and faculty to release their projects to open source, and for academia to educate foundations about the obligations under which academic researchers work.
- Train academia on how to use and contribute to PyTorch Foundation-hosted projects—PyTorch, vLLM, Ray, and DeepSpeed—with a focus on reproducible research-to-production workflows.
- Create a fast track for academic open source projects to enter the PyTorch Ecosystem and, where appropriate, progress to foundation-hosted status via a transparent intake and governance path aligned with existing Foundation processes.

## 3) Program Goals

### G1: Open source AI capability uplift in academia

- Advocate for open source, and empower researchers to publish, govern, and maintain open source AI projects responsibly and sustainably.
- Increase the number of academic contributors who can participate effectively in PyTorch Foundation technical communities.

### G2: Adoption and contribution to Foundation-hosted projects

- Increase academic usage of PyTorch Foundation-hosted projects in research and teaching.
- Increase upstream contributions from academia (PRs, issues, discussions, working group participation).

### G3: Ecosystem and hosting pipeline (“academic fast track”)

Build a consistent, well-supported pathway for academic projects to:

- meet baseline open source readiness (docs, license, governance, security basics, etc.),
- become part of PyTorch Ecosystem projects, and
- advance toward being a foundation-hosted project candidate with TAC sponsorship and review.

_See [Foundation Hosted Project documentation](https://github.com/pytorch-fdn/foundation-hosted) to learn more about foundation-hosted project requirements._

## 4) Scope

### In scope

- Curriculum, workshops, office hours, and reference materials for open source AI operations and the benefits of a project being accepted by the Foundation.
- Technical enablement content and hands-on labs for PyTorch, vLLM, Ray, and DeepSpeed.
- Academic project intake, readiness assessment, mentorship, and pipeline management aligned to Foundation processes (Foundation Hosted Project).
- A “labs & OSPO directory” database (opt-in) with contact details and PyTorch-hosted project focus areas.

### Out of scope (initially)

- Direct funding commitments for academic projects (unless separately authorized by Foundation budget).
- Managing lab internal IP policies (program provides guidance/templates; institutions retain policy control).
- Acting as the sole maintainer for academic projects (program supports, mentors, and connects).

## 5) Strategy and Operating Model

This section describes how goals will be achieved by outlining the key tracks (themes), the modules within each track, and the delivery mechanisms that will be used to produce and distribute the work.

### A. Academic Open Source AI Readiness Track

A modular curriculum designed for academic realities (students rotate, grants end, maintainers graduate).

#### Core modules

- Open source project design: problem framing, scope boundaries, roadmap hygiene
- Licensing & IP basics for academia; inbound/outbound licensing, contributor agreements (CLA vs DCO), alignment with academic licensing policies
- Governance: roles, decision-making, maintainer succession, codes of conduct (aligned to OpenMVG)
- Community operations: issue triage, PR review, release notes, contributor onboarding
- Software supply chain security: vulnerability intake, coordinated disclosure, dependency policy
- Reproducibility and benchmarking: datasets, evaluation harnesses, artifacts, and documentation norms

#### Delivery mechanisms

- Quarterly virtual “Open Source AI in Academia” online workshops / webinars
- Quarterly OSPO/lab lead roundtables for peer exchange
- Maintainer office hours (triage, governance reviews, release planning)
- Reusable templates: `GOVERNANCE.md`, `MAINTAINERS`, `SECURITY.md`, `CONTRIBUTING.md`, release checklist (provided by OpenMVG)

**Note:** Build on the PyTorch Foundation’s community programming infrastructure and templates where possible (from events, training, program scaffolding, etc).

### B. PyTorch Foundation Projects Enablement Track (PyTorch, vLLM, Ray, DeepSpeed)

A technical enablement series that emphasizes interoperability across the hosted stack.

#### Core modules

##### PyTorch (model development)

- Core training patterns, distributed basics, compiler/runtime considerations, packaging and deployment
- Contribution pathways: RFC/design discussion norms, testing/CI expectations, documentation standards

##### vLLM (inference and serving)

- High-throughput inference patterns, serving architecture, benchmarking, backend considerations
- Academic use cases: releasing reproducible inference pipelines, evaluation harnesses

##### DeepSpeed (optimization and orchestration)

- Efficient distributed training/inference, memory optimization patterns, cost/performance framing
- “Research → scale” labs: taking experimental models to multi-node or large batch regimes

##### Ray (distributed execution and orchestration)

- Distributed data/compute patterns, scalable experimentation, cluster execution models
- “End-to-end stack” lab: PyTorch training + Ray distributed execution + vLLM inference integration concepts

#### Delivery mechanisms

- A standardized workshop kit per project (slides, notebooks, reference repos, assignments)
- University guest lecture program (train-the-trainer for faculty and teaching staff)
- Academic calendar-friendly project/feature work that may culminate in upstream contributions to the upstream project

### C. PyTorch Ecosystem Academic Fast Track

A step-by-step on-ramp for academic projects to join the PyTorch Ecosystem, and eventually become foundation-hosted under the PyTorch Foundation.

#### Delivery mechanisms

A pipeline that aligns with existing Foundation intake expectations:

##### Stage 0 — Discovery & triage

- Light intake form with project description, repo, maintainers, license, dependency graph, user base, fit to PyTorch ecosystem

##### Stage 1 — Open Source Readiness Review (OSRR)

Checklist review to raise the project to a “ready to open source” baseline level:

- OS docs in place (`README`, `CONTRIBUTING`, governance, security)
- CI/release basics
- Minimum maintainer continuity plan
- Community channels and issue hygiene

##### Stage 2 — Ecosystem entry

- Support the project in applying to become a PyTorch Ecosystem project (positioning, compatibility story, docs, community readiness)

##### Stage 3 — Foundation-hosted candidacy

Support for projects with demonstrated impact, maturity, and strategic alignment to:

- Identify a TAC sponsor and prep review materials
- Follow the Foundation-hosted intake path (including the requirement that the project is already an approved ecosystem project)

##### Stage 4 — Post-acceptance scaling

- Once hosted, onboard the project to Foundation norms: reporting, release governance, security handling, comms, community growth support

### D. Labs & OSPO Directory Database

Create an actionable, up-to-date directory to support outreach, collaboration, and rapid matching between:

- academic capabilities (labs),
- institutional open source governance (university OSPOs / research software engineering groups),
- PyTorch Foundation projects and mentorship needs

#### Recommended data schema

##### Institution

- University/Institute name
- Country/region
- Primary website

##### Lab / Group

- Lab name
- Department
- PI/Director
- Lab site
- Research themes (controlled vocabulary)

##### OSPO / Research Software org

- Org name
- Remit (policy vs engineering vs community)
- Supported license policies
- Onboarding requirements

##### Contacts (opt-in)

- Name
- Role
- Email
- Preferred contact channel
- Consent flag
- Last-validated date

##### Project portfolio

- Project names
- Repo URLs
- Domains (LLM, CV, robotics, compilers, distributed, inference, etc.)
- Maturity signals: license, governance, CI, release cadence, security policy

##### Engagement history

- Attended events
- Mentorship interactions
- Pipeline stage (if participating)
- Notes with retention policy

#### Collection and maintenance

##### Sources

- opt-in submissions via a public form,
- curated outreach from conferences and workshops,
- periodic validation emails (“confirm or update your entry”)

##### Data stewardship

- explicit consent for storing personal contact info,
- role-based access controls (staff vs volunteer mentors),
- retention policy (e.g., purge unvalidated contacts after N months),
- compliance alignment with applicable privacy regulations (e.g., GDPR where relevant)

#### Outputs

- Quarterly “target list” for outreach campaigns (by domain, region, maturity)
- Partner matching for contributor sprints and capstone projects
- Funnel analytics (directory → event → contribution → ecosystem/hosting)

## 6) Governance and Stakeholders

### Program oversight

- Align with PyTorch Foundation governance structures (Governing Board strategic direction; TAC technical coordination)

### Core roles

- **Program Director (OSPO & Academic Outreach):** strategy, partnerships, reporting, budget alignment
- **Curriculum Lead:** open source AI and project-specific training assets
- **Ecosystem Pipeline Lead:** intake, readiness reviews, mentorship coordination, TAC interfacing
- **Community & Events Lead:** workshops, office hours, campus engagements
- **Data Steward:** labs/OSPO directory database operations, privacy and compliance

### Operating cadence

- Monthly internal program review (delivery, pipeline, risks)
- Quarterly TAC-facing update (pipeline status, curriculum alignment)
- Biannual Governing Board summary (outcomes and next-half priorities)

## 7) Key Deliverables

### Within the first 6 months

- “Open Source AI in Academia” curriculum v1 + templates bundle
- Four project enablement workshop kits (PyTorch, vLLM, Ray, DeepSpeed)
- Academic Fast Track: intake form, OSRR checklist, reviewer rubric, mentorship pool
- Labs & OSPO directory database v1 (schema, collection process, opt-in workflow)

### Within 12 months

- Repeatable university engagement playbook (guest lectures, capstones, contributor sprints, educator’s packet)
- Published “Academic Project Readiness” guide mapped to ecosystem/hosting requirements
- Annual Academic Open Source AI report (aggregated metrics, anonymized insights, case studies)

These deliverables are expected to be supported by Linux Foundation staff and primarily driven by Working Group contributors / participants.

## 8) Metrics and Measurement

The metrics below are intended as examples and a starting point for the working group, not as a final list of measures to be tracked. 
The specific metrics used should depend on the working group’s priorities, deliverable focus, and measurement capacity. 
As the working group progresses, these metrics may be refined, prioritized, expanded, or replaced.

### A. Academic OSAI Readiness Track (Objective 1)

- number of workshops delivered
- number of universities reached
- number of attendees and completions
- Pre/post self-assessments of OSPO competency (governance, licensing, security, CI, releases)
- number of labs adopting standard open source governance artifacts (`SECURITY.md`, `GOVERNANCE.md`, release process)
- Satisfaction/NPS-style scores from faculty, students, and OSPO staff

### B. Hosted Project Enablement Track (Objective 2)

- number of academic users trained per project track (PyTorch/vLLM/Ray/DeepSpeed)
- number of academic-origin PRs/issues merged/closed across hosted repos (and median time-to-merge)
- number of academic participants in public TAC meetings / working groups (where applicable)

### C. PyTorch Ecosystem Fast Track (Objective 3)

- number of projects entering Stage 0
- number completing OSRR
- number accepted as ecosystem projects
- number of projects progressing to foundation-hosted application
- number accepted

### D. Community sustainability and diversity

- Number of academic institutions contributing
- Maintainer distribution across institutions (elephant factor)

## 9) Success Definition

The program is considered successful when it demonstrates, year-over-year:

- **Capability:** A measurable improvement in academic open source project hygiene and sustainability (readiness checklist pass rates, adoption of governance/security/release practices).
- **Adoption & contribution:** Material growth in academic usage and upstream contribution to PyTorch Foundation-hosted projects, with reduced friction (faster PR cycle times, higher repeat contributor rates).
- **Pipeline throughput with quality:** A predictable flow of academic projects entering the ecosystem and a smaller, high-quality subset progressing to hosting candidacy aligned with TAC expectations and Foundation processes.
- **Network effects:** A durable network of labs and OSPOs that sustains collaboration beyond individual grants and student cohorts.

## 11) Risks and Mitigations

- **Academic maintainer churn:** mitigate with maintainer rotation plans, institutional OSPO involvement, and contributor pipeline.
- **Misaligned incentives (papers vs maintenance):** mitigate by recognizing maintainer work (badges, showcases), and promoting citation-friendly artifact practices.
- **Project quality variance:** mitigate with OSRR gating and mentorship before ecosystem/hosting steps.
- **Privacy and stale contacts:** mitigate via opt-in + periodic validation + retention policy.

---

## Appendix A. Labs & OSPO Directory Database (Design and Operating Policy)

### A. Purpose

Create an actionable, up-to-date directory to support outreach, collaboration, and rapid matching between:

- academic capabilities (labs),
- institutional open source governance (university OSPOs / research software engineering groups),
- PyTorch Foundation projects and mentorship needs

### B. Data fields (recommended schema)

#### Institution

- University/Institute name
- Country/region
- Primary website

#### Lab / Group

- Lab name
- Department
- PI/Director
- Lab site
- Research themes (controlled vocabulary)

#### OSPO / Research Software org

- Org name
- Remit (policy vs engineering vs community)
- Supported license policies
- Onboarding requirements

#### Contacts (opt-in)

- Name
- Role
- Email
- Preferred contact channel
- Consent flag
- Last-validated date

#### Project portfolio

- Project names
- Repo URLs
- Domains (LLM, CV, robotics, compilers, distributed, inference, etc.)
- Maturity signals: license, governance, CI, release cadence, security policy

#### Engagement history

- Attended events
- Mentorship interactions
- Pipeline stage (if participating)
- Notes with retention policy

### C. Collection and maintenance

#### Sources

- opt-in submissions via a public form,
- curated outreach from conferences and workshops,
- periodic validation emails (“confirm or update your entry”)

#### Data stewardship

- explicit consent for storing personal contact info,
- role-based access controls (staff vs volunteer mentors),
- retention policy (e.g., purge unvalidated contacts after N months),
- compliance alignment with applicable privacy regulations (e.g., GDPR where relevant)

### D. Outputs

- Quarterly “target list” for outreach campaigns (by domain, region, maturity)
- Partner matching for contributor sprints and capstone projects
- Funnel analytics (directory → event → contribution → ecosystem/hosting)

---

## Appendix B. Initial Implementation Plan (Practical Sequencing)

- Stand up OSRR checklist + templates bundle; launch first bootcamp cohort.
- Publish the four hosted-project workshop kits and run one multi-project “stack” workshop.
- Build/source/deploy platform for directory and program management.
- Launch directory v1 (opt-in form + validation workflow) and begin targeted outreach by domain.
- Start the Academic Fast Track with a small pilot (5–10 labs), then scale after refining gates and mentorship capacity.
