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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas (NEW — to be added)

These roles are commonly involved in delivery and decision-making but are not explicitly defined in the original document. Adding them clarifies ownership, reduces handoff ambiguity, and improves execution speed.

### Delivery Lead
- Responsibilities:
  - Coordinate day-to-day delivery and sprint execution.
  - Manage the sprint/project board: ensure stories flow through Ready → In Progress → In Review → Done.
  - Track cross-team dependencies and unblock work.
  - Confirm acceptance criteria and DoD before items enter sprints.
- Interaction:
  - Works closely with PM (scheduling, risk update), PdM (priority alignment), Developers and QA (execution), and Stakeholders (status updates).
- Success signals:
  - Reduced blocked stories, predictable sprint outcomes, smoother handoffs.

### Technical Lead / Architect
- Responsibilities:
  - Define overall technical approach and major design patterns.
  - Lead technical design discussions, own architecture runway, and review significant PRs.
  - Maintain and prioritize technical debt items and non-functional requirements.
- Interaction:
  - Partners with Developers on design & code reviews, advises PM/PdM on technical trade-offs, and escalates resource/scope needs to PM.
- Success signals:
  - Stable architecture decisions, fewer rework cycles, and predictable performance/reliability metrics.

### Product Designer (UX)
- Responsibilities:
  - Drive user research, design solution options, and create UX deliverables (wireframes, prototypes).
  - Define design acceptance criteria and accessibility/usability checks.
- Interaction:
  - Works with PdM to shape requirements, Developers for implementation details, and QA for usability testing.
- Success signals:
  - Clear acceptance criteria for usability, fewer design-related change requests post-implementation.

### Data Analyst / Insights Partner
- Responsibilities:
  - Define measurement plans and success metrics.
  - Implement instrumentation plans or partner with Engineering to do so.
  - Analyze results and provide actionable insights.
- Interaction:
  - Works with PdM for success metrics, Developers/Platform for instrumentation, and PM for progress reporting.
- Success signals:
  - Reliable instrumentation, timely insights that influence product decisions, and measured improvements in target metrics.

### Security / Compliance Reviewer
- Responsibilities:
  - Conduct security and compliance reviews; identify risks and required controls.
  - Approve releases when applicable or escalate required mitigations.
- Interaction:
  - Engages during planning, design, and PR review stages; coordinates with PM and Product Lead for remediation and release gating.
- Success signals:
  - Security findings tracked and resolved before release; reduced security incidents.

### Release Coordinator
- Responsibilities:
  - Own deployment windows, release notes, rollback plans, and stakeholder communications for releases.
  - Coordinate post-release verifications and incident handoffs.
- Interaction:
  - Coordinates with PM, DevOps, QA, Support, and Stakeholders for release readiness and communications.
- Success signals:
  - Smooth releases, clear stakeholder communications, fast rollback or mitigation when needed.

### Interaction Map (summary)
- PdM: product vision, success metrics, acceptance criteria.
- PM: schedule, risk, coordination.
- Delivery Lead: sprint execution and flow.
- Technical Lead: architecture and major technical decisions.
- Developers: implementation and code quality.
- QA: validation & acceptance.
- Product Designer: usability and design acceptance.
- Data Analyst: measurement & insights.
- Security Reviewer: risk & compliance gating.
- Release Coordinator: release orchestration and stakeholder comms.
