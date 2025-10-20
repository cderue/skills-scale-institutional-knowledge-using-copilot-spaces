# OctoAcme Project Management Docs

This README provides a brief overview of OctoAcme's project management processes and direct links to the detailed process documents in this folder. It is intended as a single, discoverable entry point for team members to find practices, templates, and checklists used across the project lifecycle.

OctoAcme follows an iterative, customer-first approach that moves work through clear, timeboxed phases: initiation, planning, execution, release, and continuous improvement. Work is organized into small, shippable increments with explicit acceptance criteria and a Definition of Done. Backlog items follow a standard template and are pulled into sprints only when they meet the DoD. The Pull Request workflow enforces small, focused changes that include links to issues and acceptance criteria, require CI checks, and at least one approval before merging.

Roles and responsibilities are clearly defined so ownership is visible throughout the lifecycle. The Project Manager coordinates delivery, risk, and stakeholder communication; the Product Manager defines outcomes and prioritizes the backlog; Developers implement and test features; and QA validates acceptance criteria and critical flows. These personas are documented in the roles file and used to set expectations for communications and responsibilities.

Communication and quality assurance are integrated into the team rhythm: daily standups and weekly delivery syncs surface progress and blockers, regular demos and sprint reviews validate outcomes, and a maintained Risk Register with escalation paths ensures issues are managed promptly. QA uses layered practices—unit and integration tests, CI security scans, end-to-end smoke tests for critical flows, and manual validation when required—combined with dashboards (velocity, burndown, error and usage signals) to monitor health and quality.

Links to detailed process documents:

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

Acceptance criteria (to validate before merge):
- README added to docs/ with content above or equivalent that aligns with existing docs
- README improves discoverability by linking to all process documents
- PR references "Related to #2" in description and requests review from `cderue`
