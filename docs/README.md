# OctoAcme Project Management Docs

Use this README as the onboarding entry point to how OctoAcme plans and delivers work. For full process details, follow the linked guides below.

## 1) Lifecycle at a glance

OctoAcme runs projects through a consistent lifecycle: **initiation → planning → execution → release → retrospective improvement**.

## 2) Core workflows

- Start with a one-pager/charter that defines the problem, goals, success metrics, and initial risks.
- Convert approved work into a prioritized backlog with acceptance criteria, estimates, dependencies, and milestones.
- Move delivery work through the project board: **Backlog → Ready → In Progress → In Review → QA → Done**.
- Keep PRs small, link them to issues/acceptance criteria, and require CI checks before review.
- Use release checklists before deployment.

## 3) Roles and ownership

- **Project Managers** coordinate delivery, timelines, dependencies, and risk.
- **Product Managers** define desired outcomes and prioritize backlog work.
- **Developers** implement, test, and document changes.
- **QA** validates acceptance criteria and release readiness.
- **Stakeholders** provide domain input, decisions, and approvals.

## 4) Communication and risk management

- Use regular standups, weekly delivery syncs, demos, and status templates.
- Follow a clear escalation path: **team triage → PM/Product Lead → sponsor**.
- Maintain a living risk register with owners and mitigation plans.

## 5) Quality and release readiness

- Validate with unit and integration tests, plus smoke tests for critical flows.
- Run CI quality gates including security scanning before merge/release.
- Include manual QA where needed, documented rollback plans, and post-deploy checks.
- Run post-release retrospectives and track action items to completion.

## 6) Detailed process docs

- [OctoAcme Project Management Overview](octoacme-project-management-overview.md)
- [OctoAcme — Project Initiation Guide](octoacme-project-initiation.md)
- [OctoAcme — Project Planning](octoacme-project-planning.md)
- [OctoAcme — Execution & Tracking](octoacme-execution-and-tracking.md)
- [OctoAcme — Risk Management & Communication](octoacme-risks-and-communication.md)
- [OctoAcme — Release & Deployment Guide](octoacme-release-and-deployment.md)
- [OctoAcme — Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [OctoAcme Personas](octoacme-roles-and-personas.md)
