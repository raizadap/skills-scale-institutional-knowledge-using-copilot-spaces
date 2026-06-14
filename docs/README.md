# OctoAcme Project Management Docs

This README provides quick links to the canonical project management process documents used by OctoAcme and a short summary of the core processes. Add or update documents in the docs/ folder as processes evolve.

## Core Documents

- [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) — High-level principles, roles, artifacts, and communication cadence
- [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) — Detailed responsibilities and goals for Developers, Product Managers, and Project Managers
- [octoacme-project-initiation.md](./octoacme-project-initiation.md) — Initial steps to validate, authorize, and align stakeholders on new work
- [octoacme-project-planning.md](./octoacme-project-planning.md) — How to translate outcomes into detailed plans and milestones
- [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) — Day-to-day execution, team rhythm, workflows, and quality practices
- [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) — Risk management lifecycle and stakeholder communication strategies
- [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) — Release types, pre-release requirements, deployment checklists, and rollback procedures
- [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) — How to run retrospectives and feed learnings back into processes

## OctoAcme Project Management Overview

OctoAcme operates with a **multi-disciplinary team model** centered on clear roles and responsibilities. **Project Managers** coordinate delivery, schedules, risks, and communications to keep teams aligned. **Product Managers** define what to build by focusing on customer value, prioritizing backlogs, and measuring success through data-driven metrics. **Developers and QA/Testing teams** implement features that meet acceptance criteria while maintaining high quality standards. This structure ensures clear ownership and is supported by structured communication cadences: weekly syncs between PM and Product Manager, twice-weekly team standups, and monthly stakeholder updates.

### Core Workflows & Execution Model

OctoAcme follows a **structured five-phase project lifecycle**: Initiation (validating need and aligning stakeholders), Planning (defining scope, resources, and milestones), Execution (building and testing in iterative cycles), Release (deploying to production with verification), and Close & Retrospective (capturing learnings). Execution is driven by sprint-based rhythms with daily standups focused on blockers and dependencies, weekly delivery syncs to review progress, and demos at sprint endpoints. The team uses GitHub Projects-style workflows with boards moving work through Backlog → Ready → In Progress → In Review → QA → Done, enforcing disciplined practices like small pull requests (≤400 lines), mandatory code review approvals, and automated CI validation before merge.

### Risk Management & Communication Strategy

OctoAcme maintains **systematic risk oversight** through a Risk Register that documents each risk's ID, description, impact, likelihood, owner, mitigation plan, and status—reviewed weekly alongside project metrics. Communication is proactive and multi-layered: stakeholder groups receive regular updates (weekly or milestone-based) using a standardized status template. The organization defines clear escalation paths (Team-level → PM → Product Lead → Sponsor) to ensure issues surface quickly and are addressed at the appropriate level.

### Quality Assurance & Release Excellence

Quality is embedded throughout the OctoAcme workflow through **multi-layered testing**: unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and security scanning in CI. Releases follow standardized types (Patch, Minor, Major) with pre-release requirements including passing CI/security scans, drafted release notes, and documented rollback plans. This rigorous approach reduces deployment risk while maintaining observability and enabling rapid incident response.

## How to Use These Docs

- **New to OctoAcme?** Start with [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) for a concise introduction to principles and roles.
- **Starting a new project?** Follow the checklist in [octoacme-project-initiation.md](./octoacme-project-initiation.md) to validate and authorize work.
- **Executing on a project?** Reference [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) for day-to-day workflows and quality practices.
- **Managing risks?** See [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) for escalation paths and communication templates.
- **Preparing a release?** Use the checklists and templates in [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md).

## Updating These Docs

As OctoAcme's processes evolve, keep these docs current:

1. Create an issue using the **"Add Content to Project Management Process Docs"** template in `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`
2. Propose changes or new content in the issue
3. Review with stakeholders (if needed) and incorporate feedback
4. Update the relevant markdown file(s) in this folder
5. Link the PR to the issue to close it

These documents are a living resource—continuous improvement ensures they stay relevant and useful for all team members.
