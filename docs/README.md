# OctoAcme Project Management Docs

This directory contains the shared process guidance for OctoAcme projects. OctoAcme uses a customer-first, iterative, and data-informed approach with clear ownership, measurable outcomes, and continuous improvement. The documentation is intended to provide a consistent reference for project managers, product managers, developers, QA and testing, stakeholders, and other contributors throughout the project lifecycle.

## Project lifecycle

OctoAcme projects move through five connected stages: initiation, planning, execution and tracking, release, and retrospective/close. Initiation validates the problem, goals, stakeholders, success metrics, timeline, risks, and resources. Planning converts an approved initiative into a prioritized backlog with acceptance criteria, estimates, dependencies, milestones, and a Definition of Done. During execution, teams use a project board, small pull requests, regular reviews, automated checks, and recurring delivery ceremonies to track progress and surface blockers. Releases require acceptance criteria completion, passing CI and security checks, release notes, smoke tests, and a rollback or mitigation plan; retrospectives then capture learning and assign improvement actions.

## Roles, communication, and risk management

Project Managers coordinate schedules, delivery, risks, resources, and communications. Product Managers define customer and business outcomes, prioritize the backlog, and measure impact. Developers implement and test features, QA validates quality and acceptance criteria, and stakeholders provide context, feedback, and approvals. Communication uses standups, weekly delivery and PM/Product syncs, milestone demos or reviews, stakeholder updates, and ad-hoc escalation when needed. Teams maintain a risk register and a single source of truth for status, review risks and dependencies regularly, and escalate from team-level triage through the PM and Product Lead to the sponsor when business impact warrants it.

## Quality and continuous improvement

Quality is built into delivery through unit tests for new logic, integration tests where appropriate, end-to-end smoke tests for critical flows, security scanning in CI, manual QA when needed, and required review before merging. Teams are expected to keep work small and testable, verify deployments in staging and production, monitor key signals such as errors, latency, and usage, and communicate releases to stakeholders and support. After each sprint, release, milestone, or incident, a timeboxed retrospective identifies what went well, what could improve, and a small number of owned, time-bound actions that are tracked through the backlog or issues.

## Process documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution and Tracking](octoacme-execution-and-tracking.md)
- [Risks and Communication](octoacme-risks-and-communication.md)
- [Release and Deployment](octoacme-release-and-deployment.md)
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)
