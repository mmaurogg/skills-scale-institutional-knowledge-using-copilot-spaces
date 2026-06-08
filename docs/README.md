# OctoAcme Project Management Docs

Welcome! This README provides an entry point to all OctoAcme project management workflows, guidance, and responsibilities. Use this as your index for all things process.

## Overview of Project Management Processes

OctoAcme follows a structured, lifecycle-based project management approach that emphasizes customer value, iterative delivery, and clear ownership. The methodology is organized into five distinct phases:

1. **Initiation** — Validate business need, confirm stakeholder alignment, and create a lightweight project one-pager with success metrics, timelines, and resource needs.
2. **Planning** — Break work into shippable increments with clear acceptance criteria, estimate scope, identify dependencies, and define the Definition of Done.
3. **Execution** — Build and test through daily standups, weekly delivery syncs, and continuous quality assurance with unit tests, integration tests, and smoke tests.
4. **Release** — Deploy with standardized checklists, rollback plans, release notes, and post-deployment verification.
5. **Close & Retrospective** — Capture learnings and convert them into actionable improvements for continuous evolution of practices.

### Core Principles

- **Customer-first:** Prioritize customer value and usability in all decisions.
- **Iterative delivery:** Deliver small, testable increments to reduce risk and enable faster feedback.
- **Clear ownership:** Each project has named roles—Project Manager, Product Manager, and Development Team—with well-defined responsibilities.
- **Data-informed decisions:** Measure impact and iterate based on evidence.
- **Psychological safety:** Encourage feedback, learning, and blameless retrospectives.

### Key Roles

- **Project Manager (PM):** Coordinates delivery, schedules, risks, and communications. Ensures transparency and alignment across stakeholders.
- **Product Manager (PdM):** Defines outcomes, prioritizes the backlog, measures success, and collaborates on trade-offs.
- **Developers:** Implement features, collaborate on design and testability, assist in estimation and planning, and help identify technical risks.
- **QA/Testing:** Validate quality and acceptance criteria throughout the development lifecycle.

### Communication & Quality Assurance

OctoAcme operates on a structured communication cadence:
- **Daily standups** (15 min) — focus on progress, blockers, and dependencies
- **Weekly delivery syncs** — show progress, updates, and flagged risks
- **Sprint/milestone demos and reviews** — validate delivery and gather feedback
- **Weekly PM + PdM alignment** — ensure business and delivery are synchronized
- **Monthly stakeholder updates** — provide visibility and maintain buy-in

Quality is embedded at every stage:
- Unit tests, integration tests, and end-to-end smoke tests for critical flows
- Small pull requests (≤400 lines) with automated CI testing and linting
- At least one approval required before merging
- Security scanning in CI pipelines
- Pre-release checklists ensuring acceptance criteria, security, and rollback plans are in place

---

## Project Management Process Docs Index

Navigate to the process document that matches your current phase or need:

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, roles, artifacts, and lifecycle.
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate, authorize, and align stakeholders on new work.
- **[Project Planning Guide](octoacme-project-planning.md)** — Break work into shippable increments, estimate, define DoD, and create release plans.
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day guidance for standups, PRs, testing, reporting, and blocker escalation.
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, assess, and mitigate risks; manage stakeholder communication and escalation paths.
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardized release types, pre-release requirements, deployment checklists, and rollback procedures.
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Run effective retrospectives and convert learnings into actionable improvements.
- **[Roles and Personas Guide](octoacme-roles-and-personas.md)** — Detailed descriptions of typical OctoAcme roles, responsibilities, goals, and communication patterns.

---

## Getting Started

**New to OctoAcme?** Start here:
1. Read the [Project Management Overview](octoacme-project-management-overview.md) to understand the big picture.
2. Jump to the process doc that matches your current phase (Initiation → Planning → Execution → Release → Retrospective).
3. Refer to the [Roles and Personas Guide](octoacme-roles-and-personas.md) to understand your responsibilities and how you fit into the team.

**Updating or refining processes?** Use the issue template in `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` to propose changes, ensuring alignment and continuous improvement.

---

## Keep These Docs Fresh

As OctoAcme evolves, so should these guides. When you identify gaps, improvements, or new best practices:
- Open an issue using the **Process Doc Update** template.
- Collaborate with the team to refine and validate changes.
- Update the relevant doc and this README to maintain a single source of truth.

Together, we build institutional knowledge that scales with the team.
