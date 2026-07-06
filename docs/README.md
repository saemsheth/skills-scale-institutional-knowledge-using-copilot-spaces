# OctoAcme Project Management Docs

This README is the central entry point to OctoAcme's project management process documentation. It provides a concise overview of how projects are run at OctoAcme and links to each detailed process document for deeper reference.

## Process Overview

OctoAcme follows a structured, iterative project management lifecycle across five phases:

- **Initiation** – Validate business need, define goals and success metrics, confirm stakeholder alignment, surface initial risks, and verify team availability before committing to delivery.
- **Planning** – Translate approved goals into a prioritized, estimated backlog with clear acceptance criteria, mapped dependencies, defined milestones, and a documented Definition of Done.
- **Execution & Tracking** – Deliver in small increments guided by daily or twice-weekly standups, weekly PM/Product alignment syncs, end-of-sprint demos, and structured progress reports. A single source of truth for status is maintained throughout.
- **Release & Deployment** – Apply pre-release checklists, staged deployment, post-deploy verification, and rollback readiness to reduce deployment risk and ensure operational safety.
- **Retrospective & Improvement** – Capture lessons learned after each cycle and convert them into owned action items, reinforcing a continuous improvement loop for future projects.

## Key Roles

| Role | Responsibilities |
|---|---|
| **Project Manager** | Coordinates schedules, risks, dependencies, and stakeholder communications |
| **Product Manager** | Defines outcomes, prioritizes the roadmap, and validates value through metrics |
| **Developer** | Designs and implements solutions with testing and maintainability in mind |
| **QA / Tester** | Verifies acceptance criteria and overall product quality |
| **Stakeholder / Sponsor** | Provides strategic direction and approvals |

All roles share ownership of key delivery artifacts: one-pagers, backlog items, risk registers, release notes, and retrospective outputs.

## Communication Strategies

- **Recurring cadences**: daily or twice-weekly standups, weekly PM/PdM alignment, weekly delivery syncs, end-of-sprint demos, and monthly stakeholder updates.
- **Single source of truth**: status and decisions are documented in one place and kept current.
- **Structured templates**: weekly status updates and incident communications follow consistent formats.
- **Escalation path**: team triage → PM/Product Lead → Sponsor for business-critical issues; separate security escalation track when needed.

## Quality Assurance Practices

- Unit tests for all new logic; integration coverage where applicable.
- End-to-end smoke tests for critical user flows.
- CI-based linting and automated security scanning on every change.
- Manual QA for final acceptance checks as needed.
- PR standards: small, focused PRs linked to issues with acceptance criteria and required review approval before merge.

## Documentation Index

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)
