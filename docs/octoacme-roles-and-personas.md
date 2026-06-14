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

## Program Coordinator

### Role Summary
Program Coordinators maintain cross-project visibility and operational continuity. They manage schedules, coordinate status communications, and ensure action items are tracked and escalated appropriately.

### Responsibilities
- Maintain consolidated cross-project schedules and timelines
- Coordinate status meetings and action item tracking
- Escalate schedule risks and dependencies to Project Managers and Program Sponsors
- Ensure meeting notes, decisions, and follow-ups are documented
- Support retrospectives and process improvement tracking

### Goals
- Increase schedule visibility and predictability across programs
- Reduce communication delays and missed handoffs
- Enable rapid escalation of risks before they impact delivery

### Typical Interactions
- Works with **Project Managers** to consolidate updates and identify cross-project dependencies
- Partners with **Delivery Leads** to collect status and flag impediments
- Reports to **Project Sponsor** and **Program Managers** on program health
- Maintains shared artifacts (roadmaps, dashboards, decision logs)

---

## Delivery Lead

### Role Summary
Delivery Leads oversee day-to-day execution across engineering teams. They remove impediments, maintain iteration cadence, and ensure teams have clarity on priorities and dependencies.

### Responsibilities
- Manage sprint/iteration planning and execution
- Remove blockers and impediments quickly
- Align team priorities with Product Owner and Project Manager
- Track velocity, burndown, and delivery metrics
- Facilitate daily standups and retros for engineering teams
- Report delivery status and forecast completion

### Goals
- Maintain consistent team velocity and iteration cadence
- Minimize cycle time from issue to production
- Ensure transparency on progress and risks

### Typical Interactions
- Collaborates with **Project Manager** for overall delivery status reporting
- Works with **Product Owner** to refine and prioritize backlog
- Partners with **Engineering Leads** to resolve technical blockers
- Provides daily visibility to **Program Coordinator**
- Reports rollup metrics to **Delivery Directors** or **Release Coordinator**

---

## Release Coordinator

### Role Summary
Release Coordinators own the end-to-end release process. They manage release checklists, coordinate release windows, communicate release timelines to stakeholders, and ensure rollback plans are in place.

### Responsibilities
- Own release checklists and readiness validation
- Coordinate release windows and deployment schedules
- Manage release communication to stakeholders
- Validate feature completeness, documentation, and testing
- Plan and document rollback procedures
- Track release metrics (deployment frequency, lead time, MTTR)

### Goals
- Deliver releases on schedule with zero unplanned outages
- Reduce deployment risk through rigorous checklists
- Improve time-to-market while maintaining stability

### Typical Interactions
- Works with **Technical Liaisons** to validate technical readiness
- Coordinates with **QA / Testers** to confirm quality gates are met
- Collaborates with **Project Manager** on release approval and communication
- Partners with **Documentation Owner** to ensure release notes are complete
- Engages **Compliance / Legal Reviewer** if release contains compliance-sensitive changes

---

## Technical Liaison

### Role Summary
Technical Liaisons bridge product and engineering by translating requirements into technical tasks, validating architectural decisions, and representing engineering in cross-functional forums.

### Responsibilities
- Translate product requirements and acceptance criteria into technical tasks
- Validate solution architecture and identify technical trade-offs
- Represent engineering perspective in product and business discussions
- Own technical design documentation and design reviews
- Escalate technical risks and dependencies early
- Mentor junior engineers on technical excellence

### Goals
- Ensure product decisions are technically sound and feasible
- Reduce rework and technical debt
- Build sustainable, scalable systems

### Typical Interactions
- Paired with **Product Manager** and **Stakeholder Representative** to understand business context
- Works with **Engineering Leads** to design and validate solutions
- Collaborates with **Release Coordinator** to validate technical readiness
- Engages with **Change / Configuration Manager** on deployment readiness

---

## Documentation Owner

### Role Summary
Documentation Owners ensure process and product documentation remains current, accurate, and discoverable. They manage documentation review cycles and coordinate with knowledge stakeholders.

### Responsibilities
- Maintain current process documentation (procedures, checklists, playbooks)
- Manage documentation review and approval workflows
- Coordinate with teams to capture release notes and product changes
- Organize documentation by audience and purpose
- Track documentation debt and improvement backlog
- Support onboarding with up-to-date process guides

### Goals
- Reduce onboarding time through clear documentation
- Minimize tribal knowledge and single points of failure
- Ensure compliance documentation is audit-ready

### Typical Interactions
- Works with **Program Coordinator** to schedule and track documentation updates
- Partners with **Release Coordinator** for release notes and deployment guides
- Collaborates with **QA / Testers** to capture test procedures and known issues
- Engages **Developers** to document technical decisions and architecture
- Reports documentation gaps to **Project Manager**

---

## Change / Configuration Manager

### Role Summary
Change/Configuration Managers oversee change control processes, approval gates, and configuration management for environments and deployments. They ensure changes are traceable, approved, and properly documented.

### Responsibilities
- Own change control board processes and approval gates
- Maintain change log and configuration item registry
- Validate that changes follow approval processes
- Coordinate environment setup, migrations, and configurations
- Track configuration versions and approvals
- Support audit and compliance requirements for change records

### Goals
- Reduce unplanned outages due to unauthorized or poorly coordinated changes
- Maintain audit trail and compliance records
- Improve change predictability and approval consistency

### Typical Interactions
- Coordinates with **Release Coordinator** to approve deployment changes
- Works with **Technical Liaisons** to validate configuration items and dependencies
- Partners with **Compliance / Legal Reviewer** to ensure changes meet compliance requirements
- Reports to **Project Manager** on change approval metrics

---

## Compliance / Legal Reviewer

### Role Summary
Compliance/Legal Reviewers assess deliverables for regulatory, contractual, and legal compliance. They flag compliance risks early and work with teams to resolve issues before delivery.

### Responsibilities
- Review deliverables for regulatory and contractual requirements
- Flag compliance gaps and propose mitigations
- Maintain compliance checklist and approval workflows
- Advise on data privacy, security, and legal risks
- Document compliance decisions and exceptions
- Support audit preparation and evidence collection

### Goals
- Prevent compliance violations and legal risks
- Reduce audit findings and remediation costs
- Build compliance into delivery process early

### Typical Interactions
- Engages with **Project Manager** and **Project Sponsor** when compliance risk is detected
- Reviews work with **Release Coordinator** before production deployments
- Collaborates with **Change / Configuration Manager** on change approval
- Partners with **Documentation Owner** to ensure compliance documentation is complete

---

## Stakeholder Representative (Business SME)

### Role Summary
Stakeholder Representatives provide domain expertise, validate acceptance criteria, and prioritize business risks. They ensure delivered solutions meet business needs and stakeholder expectations.

### Responsibilities
- Provide business and domain expertise
- Validate acceptance criteria and user requirements
- Prioritize business risks and mitigation strategies
- Represent stakeholder interests in trade-off decisions
- Sign off on completed work and acceptance
- Communicate project status and business impact to leadership

### Goals
- Ensure delivered solutions meet business objectives
- Reduce scope creep and rework through clear acceptance criteria
- Build stakeholder confidence and alignment

### Typical Interactions
- Works directly with **Product Manager** on scope, priorities, and business context
- Collaborates with **Project Manager** on acceptance decisions and sign-off
- Engages with **Technical Liaisons** to understand feasibility and trade-offs
- Reviews work with **Release Coordinator** for business readiness
- Reports project status and business impact to **Project Sponsor**

---

## Persona Interaction Map: Example Handoff Scenario

### Feature Delivery to Production Handoff

```
Development Complete (Developers)
         ↓
Code Review & Technical Validation (Technical Liaison)
         ↓
QA Sign-off (QA / Testers)
         ↓
Release Readiness Review (Release Coordinator)
         │
         ├→ Validate with Technical Liaison
         ├→ Collect Release Notes from Documentation Owner
         ├→ Confirm Compliance with Compliance/Legal Reviewer
         └→ Approve with Project Manager
         ↓
Change Approval (Change / Configuration Manager)
         ↓
Deployment to Production (Release Coordinator coordinates)
         ↓
Business Acceptance Sign-off (Stakeholder Representative)
         ↓
Post-Release Monitoring (Delivery Lead & Release Coordinator)
         ↓
Document Lessons Learned (Documentation Owner & Program Coordinator)
```

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interaction patterns when designing cross-functional workflows and handoffs.
