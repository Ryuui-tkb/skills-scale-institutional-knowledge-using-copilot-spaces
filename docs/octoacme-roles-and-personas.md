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

## Technical Leads / Architects

### Role Summary
Technical Leads and Architects set technical direction and help the team make sound, maintainable design decisions. They provide technical leadership without replacing the delivery accountability of the Project Manager or the product ownership of the Product Manager.

### Responsibilities
- Define and communicate technical direction and architecture decisions
- Review designs and identify technical risks, constraints, and trade-offs
- Guide implementation approaches and promote maintainability, reliability, and observability
- Support technical estimation and dependency planning
- Coach Developers and coordinate technical decision records when needed

### Interactions with Existing Roles
- Work with Product Managers to translate product outcomes into feasible technical approaches and explain engineering trade-offs
- Work with Project Managers to surface technical dependencies, risks, and capacity impacts for plans and escalation paths
- Partner with Developers through design reviews, implementation guidance, and technical problem-solving
- Consult QA Leads and Security / Compliance Leads to include quality and security requirements in the design

---

## QA Leads / Quality Managers

### Role Summary
QA Leads and Quality Managers establish the validation approach and help ensure that deliverables meet acceptance criteria and the Definition of Done.

### Responsibilities
- Define the test strategy, coverage expectations, and quality gates
- Confirm that acceptance criteria are testable and sufficiently covered
- Coordinate integration, end-to-end, regression, and manual testing as appropriate
- Facilitate defect triage and communicate quality risks and release readiness
- Improve feedback loops and advocate for prevention of recurring defects

### Interactions with Existing Roles
- Work with Product Managers and Stakeholders to clarify acceptance criteria and confirm feature behavior
- Partner with Developers and Technical Leads on testability, automation, defect resolution, and technical quality risks
- Provide Project Managers with quality status, blockers, and release-readiness information for reporting and decisions
- Coordinate with Release Managers / Change Coordinators on smoke tests and post-deployment verification

---

## Security / Compliance Leads

### Role Summary
Security / Compliance Leads identify security, privacy, regulatory, and policy requirements and ensure that they are addressed throughout delivery.

### Responsibilities
- Review security, privacy, and compliance requirements during initiation and planning
- Identify security risks and recommend mitigations or required controls
- Advise on secure implementation patterns, threat considerations, and data handling
- Coordinate security reviews, compliance checkpoints, and exception documentation
- Support incident escalation and lessons learned when security concerns arise

### Interactions with Existing Roles
- Work with Product Managers to incorporate security and compliance requirements into outcomes and acceptance criteria
- Partner with Technical Leads and Developers on architecture, implementation, and remediation decisions
- Keep Project Managers informed of security risks, dependencies, approvals, and schedule impacts
- Coordinate with Release Managers / Change Coordinators to verify required checks before deployment
- Escalate material risks through the Project Manager to the Product Lead or Sponsor, while following the security incident runbook for active incidents

---

## Release Managers / Change Coordinators

### Role Summary
Release Managers and Change Coordinators organize the transition from completed work to a controlled release, ensuring readiness, communication, and rollback planning.

### Responsibilities
- Coordinate release scope, readiness reviews, deployment windows, and change records
- Confirm that acceptance criteria, CI, security scans, smoke tests, release notes, and rollback plans are complete
- Coordinate deployment execution and post-deployment verification
- Track release issues and ensure mitigations or rollback decisions are communicated
- Capture release outcomes and follow-up actions for retrospectives

### Interactions with Existing Roles
- Work with Project Managers to align release timing, dependencies, risks, and stakeholder communications
- Work with Product Managers to confirm scope, business readiness, and release messaging
- Coordinate with Technical Leads, Developers, and QA Leads on deployment plans, validation, and rollback readiness
- Partner with Security / Compliance Leads when approvals or security checks are required
- Communicate status and issues to Stakeholders and support teams before and after release

---

## Customer Success / Stakeholder Liaisons

### Role Summary
Customer Success and Stakeholder Liaisons represent customer, user, and operational perspectives so that delivery decisions account for adoption, enablement, and business impact.

### Responsibilities
- Gather and communicate customer or stakeholder needs, feedback, and adoption risks
- Support rollout planning, enablement, and change-management activities
- Explain project progress, expected impact, and known limitations to affected groups
- Track feedback after delivery and connect it to product or process improvements
- Identify stakeholder concerns that require a decision, mitigation, or escalation

### Interactions with Existing Roles
- Work with Product Managers to connect customer evidence to prioritization, success metrics, and acceptance criteria
- Work with Project Managers to plan communications, stakeholder checkpoints, dependencies, and escalations
- Partner with Developers, Technical Leads, and QA Leads to communicate user impact and validate that solutions address the intended need
- Coordinate with Release Managers / Change Coordinators on announcements, training, rollout support, and feedback collection
- Escalate unresolved business-impacting concerns through the Project Manager to the Product Lead or Sponsor

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Assign a clear owner for each responsibility while recognizing that one person may perform multiple personas on a small team.
- Use the interaction sections to clarify handoffs, decision rights, and escalation paths during initiation, planning, execution, release, and retrospectives.
