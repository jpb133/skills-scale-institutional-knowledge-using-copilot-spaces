# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## New: QA / Test Engineer

### Role Summary
QA/Test Engineers define and validate product quality through testing strategy, test design, execution, and defect validation. They help ensure releases meet acceptance criteria and quality expectations.

### Responsibilities
- Define test strategy and test plans for features/milestones
- Write and execute test cases (unit, integration, e2e as applicable)
- Own defect tracking and verification of fixes
- Validate acceptance criteria and sign off on release readiness
- Contribute to automation and CI test suites

### Goals
- Prevent regressions and reduce production incidents
- Increase confidence in release quality through repeatable tests
- Reduce manual test overhead via automation

### Typical Communication
- Test reports in weekly syncs
- Issues and defect tickets with clear reproduction and severity
- Test-focused comments on PRs and feature specs

### Interaction with existing roles
- Developers: Collaborate on testability, provide failing cases and reproduce steps, and review fixes.
- Product Managers: Verify acceptance criteria; request clarifications to ensure tests cover product intent.
- Project Managers: Communicate testing timelines and sign-off status; escalate test blockers.
- Release Manager: Provide go/no-go test results and validation notes for releases.

---

## New: UX / UI Designer

### Role Summary
UX/UI Designers own user experience and interface design, ensuring solutions are intuitive, accessible, and aligned with user needs and product goals.

### Responsibilities
- Produce wireframes, mockups, and interaction specs
- Drive usability testing and synthesize results
- Define user journeys and acceptance criteria related to UX
- Provide design assets and annotations for engineering
- Advocate for accessibility and usability best practices

### Goals
- Deliver usable, delightful user experiences that meet acceptance criteria
- Reduce rework by validating assumptions early
- Improve product adoption through clear UX

### Typical Communication
- Design artifacts in design reviews and PRs
- Usability findings in planning and retrospective sessions
- Acceptance-criteria input for product stories

### Interaction with existing roles
- Product Managers: Collaborate closely during discovery to translate user needs into designs.
- Developers: Provide assets and clarify behaviors; review implementations for fidelity.
- QA/Test Engineers: Share usability testing outcomes and acceptance criteria focused on UX.
- Project Managers: Align on timelines for design iterations and handoff readiness.

---

## New: Business Analyst (BA)

### Role Summary
Business Analysts bridge business stakeholders and the delivery team, shaping accurate requirements, use cases, and acceptance criteria.

### Responsibilities
- Elicit and document requirements and user stories
- Map workflows and data flows; produce user scenarios
- Create acceptance criteria and validation scenarios
- Support product discovery and clarify ambiguous requirements
- Help prioritize requirements based on impact and feasibility

### Goals
- Reduce ambiguous requirements and rework caused by unclear scope
- Improve traceability from stakeholder need to delivered functionality
- Ensure features satisfy business and compliance needs

### Typical Communication
- Requirements and use-case documents
- Clarifications during backlog grooming and planning
- Participating in demos and acceptance validation

### Interaction with existing roles
- Product Managers: Partner on requirement definition and prioritization.
- Developers: Provide clarifications and acceptance criteria; help reproduce business flows.
- Project Managers: Communicate requirement changes and impacts on schedule.

---

## New: Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide strategic direction, resource support, and priority decisions for the project.

### Responsibilities
- Approve major milestones and business decisions
- Provide strategic context and goals
- Help resolve cross-organizational impediments
- Allocate funding or resources when required

### Goals
- Ensure the project aligns with business objectives and receives necessary support
- Reduce external blockers that impede progress

### Typical Communication
- Milestone approvals and periodic executive briefings
- Participation in key decision meetings (e.g., gate reviews)

### Interaction with existing roles
- Product Managers: Review and approve product direction and success metrics.
- Project Managers: Receive status updates for escalations and decisions.
- Release Manager / PMs: Be informed for high-impact releases or schedule changes.

---

## New: Release Manager

### Role Summary
Release Managers coordinate deploys and ensure production launches are safe, timed, and well-communicated.

### Responsibilities
- Create and maintain release windows and schedules
- Maintain release checklist and rollback plans
- Coordinate cross-team dependencies for releases
- Ensure release notes and stakeholder communications are prepared
- Run post-release verification and capture rollback/incident actions if needed

### Goals
- Reduce release-related incidents and shorten mean time to recovery
- Ensure smooth, repeatable release operations

### Typical Communication
- Release readiness reports
- Pre/post-release communications with stakeholders and support
- Coordination with Dev, QA, and Ops channels

### Interaction with existing roles
- Developers & QA: Coordinate final validations, run smoke tests, and confirm readiness.
- Project Managers: Align on release timing and scope.
- Support Lead: Ensure runbooks and handoff steps are completed prior to release.
- Stakeholders: Notify for major releases or when rollback decisions are needed.

---

## New: Support Lead

### Role Summary
Support Leads manage operational support and the early lifecycle of incidents, connecting product/engineering and customers.

### Responsibilities
- Manage on-call rotations and incident triage (initial)
- Maintain runbooks and documentation for common incidents
- Coordinate post-incident follow-up and handoff to engineering
- Track recurring issues and ensure they are prioritized appropriately

### Goals
- Reduce time-to-detect and time-to-recover for production issues
- Improve continuity between engineering and customer-facing teams

### Typical Communication
- Incident notifications and triage updates
- Post-incident reports and retrospective action items
- Handoff notes during releases

### Interaction with existing roles
- Developers: Escalate and collaborate on root cause analysis and fixes.
- Release Manager: Coordinate on release timing and risk mitigation.
- Project Managers: Communicate high-impact operational issues and resource needs.
- Product Managers: Provide customer feedback and severity context for prioritization.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Template for adding/editing personas
See docs/templates/role-responsibility-template.md for a standard template to add or update persona definitions.
</contents>
