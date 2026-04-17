# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation hub. This README provides a concise overview of how OctoAcme runs projects and links to the detailed process documents stored in this folder.

OctoAcme runs projects through a clear, stage-driven lifecycle: Initiation, Planning, Execution, Release, and Retrospective. Work begins with a lightweight Project One-pager to define the problem, success metrics, stakeholders, and a high-level timeline; this is the gate to decide whether to move into planning. Planning breaks approved initiatives into a prioritized, estimated backlog, defines a Definition of Done, identifies dependencies and risks, and maps a release plan with milestones. Execution uses a project board (Backlog → Ready → In Progress → In Review → QA → Done) and small, focused pull requests to keep changes reviewable and traceable. Releases follow a checklist-driven process (pre-release requirements, staging smoke tests, automated pipelines when possible, and post-deploy verification), and every project closes with retrospectives that surface learnings and convert them into actionable improvements.

Roles and responsibilities are explicitly defined to reduce ambiguity: Project Managers coordinate delivery, schedules, risks, and stakeholder communications; Product Managers own outcomes, prioritize the backlog, and define acceptance criteria; Developers implement features and tests; QA validates quality and acceptance; and Stakeholders provide input and approvals. This separation of responsibilities supports clear ownership for artifacts (Project Charter/One-pager, Backlog, Release Plan, Risk Register, Retrospective notes) and ensures decisions and trade-offs have named owners who can act or escalate.

Communication follows a predictable cadence to keep work transparent and risks visible. The rhythm includes daily standups for immediate progress and blocker triage, weekly delivery syncs for cross-team alignment and risk discussion, demos or reviews at the end of sprints or milestones, and monthly or milestone-based stakeholder updates. Risk and incident communication use templates—regular status summaries for ongoing work and structured incident triage plus post-incident retrospectives for failures—with escalation paths moving from team-level to PM → Product Lead → Sponsor (and Security on-call for security incidents).

Quality assurance is integrated across the lifecycle: teams are expected to include unit tests, integration tests, and targeted end-to-end smoke tests for critical flows; CI enforces automated tests and security scanning before merges; and manual QA is used where needed for feature acceptance. The PR workflow mandates links to issues and acceptance criteria, small PR sizes, and at least one approval before merging. Risk management and checklists (branching/PR conventions, CI, demos, and weekly risk register updates) are built into the process to reduce regressions and increase predictability of delivery.

## Process Docs Index
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

## Acceptance Criteria
- [ ] README is added to docs/
- [ ] README contains a 3–4 paragraph summary of OctoAcme project management processes
- [ ] README contains working links to all docs in the docs/ folder
