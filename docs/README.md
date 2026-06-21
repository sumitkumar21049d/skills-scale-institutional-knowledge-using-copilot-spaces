# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation hub. This folder contains our standardized processes, templates, and guidance for running projects from initiation through delivery and retrospective.

## Overview

OctoAcme follows a structured, lifecycle-based approach to project management grounded in **customer-first principles** and **iterative delivery**. Our framework emphasizes:

- **Clear Ownership:** Each project has named Project Manager (PM) and Product Manager (PdM) roles, with clear responsibility areas
- **Data-Informed Decisions:** We measure impact and iterate based on evidence
- **Psychological Safety:** We encourage feedback, learning, and transparent communication
- **Quality Embedded Throughout:** Testing, security scanning, and continuous verification happen throughout execution, not just at release

### Project Lifecycle

1. **Initiation** — Validate business need, align stakeholders, and create a Project One-pager with success metrics
2. **Planning** — Break work into shippable increments, prioritize the backlog, identify dependencies and risks
3. **Execution** — Build, test, and review through daily standups, weekly syncs, and a structured PR workflow
4. **Release** — Deploy with confidence using pre-release checklists, smoke tests, and rollback plans
5. **Close & Retrospective** — Capture learnings and convert them into actionable improvements

### Core Processes & Team Rhythm

- **Daily Standups** (15 min) — Focus on progress, blockers, and dependencies
- **Weekly Delivery Sync** — Show progress, flag risks, review metrics
- **Demo/Review** — At the end of each sprint or milestone
- **Pull Request Workflow** — Small PRs (≤400 lines), automated tests & linting, at least one approval before merge
- **Quality Assurance** — Unit tests, integration tests, end-to-end smoke tests, security scanning, manual QA for features
- **Risk Management** — Risk Register maintained throughout project, escalation path: Team → PM → Product Lead → Sponsor
- **Retrospectives** — After each sprint/milestone to capture improvements and drive continuous improvement

---

## Documentation Files

### Project Lifecycle & Planning
- **[octoacme-project-management-overview.md](./octoacme-project-management-overview.md)** — High-level overview of OctoAcme project management, core roles, key artifacts, and lifecycle
- **[octoacme-project-initiation.md](./octoacme-project-initiation.md)** — Initiation guide with Project One-pager template; defines decision gates to move into planning
- **[octoacme-project-planning.md](./octoacme-project-planning.md)** — Planning activities, backlog templates, estimation, Definition of Done, and risk/dependency management

### Execution & Delivery
- **[octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md)** — Day-to-day execution workflows, PR expectations, quality & testing standards, metrics tracking, and blocker escalation
- **[octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md)** — Release types, pre-release requirements, deployment checklist, rollback playbook, and release notes template

### Risk, Communication & Improvement
- **[octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md)** — Risk Register maintenance, risk lifecycle, stakeholder communication templates, and escalation paths
- **[octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md)** — Retrospective structure, tracking improvements, and building a continuous improvement culture

### Roles & Personas
- **[octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md)** — Definitions of Developer, Product Manager, and Project Manager roles, responsibilities, goals, and communication patterns

---

## How to Use These Docs

- **Getting Started?** Begin with [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) for a concise introduction to our approach and roles.
- **Starting a New Project?** Follow the [Initiation Guide](./octoacme-project-initiation.md) to validate and authorize work.
- **In Execution?** Reference [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) for daily workflows and quality standards.
- **Preparing a Release?** Check [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) for deployment checklists and playbooks.
- **Retrospectives?** Use [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) to capture and act on learnings.

## Contributing & Updates

These processes are living documents. When you identify a gap, improvement, or best practice to incorporate:

1. Open an issue using the **[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** template
2. Describe the update, rationale, and proposed content
3. Submit a pull request with changes
4. Have the update reviewed by the Product Lead or team leads before merging

This ensures our processes remain accurate, current, and aligned with how we actually work.

---

**Last Updated:** June 2026 | **Maintained By:** OctoAcme Project Management Team
