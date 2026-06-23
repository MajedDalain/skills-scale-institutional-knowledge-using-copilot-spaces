# OctoAcme Project Management Docs

This README collects links to the OctoAcme project management process documents and provides a comprehensive summary of the key processes used across projects.

## Overview of OctoAcme Project Management Processes

OctoAcme operates a structured, lifecycle-based project management approach designed to deliver customer value through iterative, cross-functional collaboration. The organization follows five key phases: **Initiation** (validating business need and stakeholder alignment through a Project One-pager), **Planning** (breaking work into shippable increments with clear acceptance criteria), **Execution** (day-to-day delivery with daily standups and weekly syncs), **Release** (standardized deployment with pre-release checklists and rollback plans), and **Retrospective** (continuous improvement through structured learning). This end-to-end lifecycle is grounded in core principles of customer-first delivery, iterative progress, clear ownership, data-informed decisions, and psychological safety—ensuring accountability while encouraging team feedback.

The organization employs a well-defined role structure to ensure smooth execution and clear decision-making. **Project Managers** coordinate delivery activities, manage schedules, risks, and communications; **Product Managers** define what should be built, prioritize the backlog, and measure outcomes; **Developers** implement features, collaborate on design, and identify technical risks; and **QA/Testing** validates quality and acceptance criteria. This distributed ownership model is supported by a regular communication cadence: daily standups (15 min), weekly delivery syncs between PM and Product Manager, twice-weekly standups for delivery teams, and monthly stakeholder updates. Risk escalation follows a structured path from team-level triage → PM → Product Lead → Sponsor, ensuring blockers are addressed at the appropriate level.

Quality assurance and execution rigor are central to OctoAcme's delivery model. Teams use GitHub Projects for workflow management (Backlog → Ready → In Progress → In Review → QA → Done), follow small PR conventions (≤400 lines), require CI checks (tests, linting, security scanning) before review, and demand at least one approval before merging. Work is tracked through velocity and burndown metrics, with acceptance criteria and a Definition of Done documented upfront. Pre-release requirements include passing CI and security scans, drafted release notes, and prepared smoke tests. This combination of lightweight process discipline, automated quality gates, and regular retrospectives enables OctoAcme teams to ship reliably while continuously improving their execution and learning culture.

## Quick Reference: Key Processes

- **Initiation**: Capture problem, stakeholders, success metrics, and decide whether to move forward (see Project Initiation Guide).
- **Planning**: Create prioritized backlog, define Definition of Done, estimate work, identify risks and dependencies (see Project Planning).
- **Execution & Tracking**: Use project boards, small PRs, CI checks, daily standups, and weekly syncs to deliver and monitor progress (see Execution & Tracking).
- **Risks & Communication**: Maintain a risk register, communicate status to stakeholders, and follow escalation paths for issues (see Risks & Communication).
- **Release & Deployment**: Follow pre-release checks, deployment checklist, and rollback playbook for production releases (see Release & Deployment).
- **Retrospective & Continuous Improvement**: Run retrospectives, create action items, and track follow-up in the backlog (see Retrospective & Continuous Improvement).
- **Roles & Personas**: Definitions of common roles (PM, PdM, Developers, QA) and their responsibilities.

## Links to Process Documentation

- [Project Management Overview](./octoacme-project-management-overview.md) — High-level introduction to OctoAcme's project management approach, roles, and key artifacts.
- [Project Initiation Guide](./octoacme-project-initiation.md) — Steps to validate business need, align stakeholders, and authorize work.
- [Project Planning](./octoacme-project-planning.md) — How to break work into shippable increments with clear acceptance criteria and timelines.
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day delivery, standups, PR workflows, quality, and blocker escalation.
- [Risks & Communication](./octoacme-risks-and-communication.md) — Risk register management, stakeholder communication, and escalation paths.
- [Release & Deployment](./octoacme-release-and-deployment.md) — Pre-release requirements, deployment checklists, and rollback playbooks.
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Running retrospectives and converting learnings into action items.
- [Roles & Personas](./octoacme-roles-and-personas.md) — Definitions of common roles and their responsibilities.

## How to Use These Documents

- Start with **Project Management Overview** for a concise introduction to OctoAcme's approach.
- Use the process-specific docs to guide your project from initiation through close.
- Add process-specific details or examples to the corresponding file in the `docs/` folder.
- To propose changes to a process doc, use the [`.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template and select the document to update (or choose '<new document>' to add a new file).

## Contributing

If you have suggestions, clarifications, or improvements to these process documents, please open an issue using the [Process Doc Update template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).
