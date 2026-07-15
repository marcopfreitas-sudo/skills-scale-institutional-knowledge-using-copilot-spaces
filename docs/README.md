# OctoAcme Project Management Documentation

## Welcome

This folder contains the comprehensive project management processes and best practices used by OctoAcme to deliver successful projects. Whether you're starting a new initiative, planning a release, or running a retrospective, you'll find guidance and templates here.

## OctoAcme Project Management Overview

OctoAcme follows a structured five-phase project lifecycle: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During initiation, teams validate business needs and align stakeholders around a lightweight Project One-pager that defines the problem statement, objectives, success metrics, and initial resource requirements. Once approved, the planning phase breaks work into shippable increments with prioritized backlogs, clear acceptance criteria, and a Definition of Done. Execution emphasizes iterative delivery through daily standups, weekly delivery syncs, and a disciplined Pull Request workflow (keeping PRs to ≤400 lines, requiring one approval, and running automated tests before merge). Finally, release and retrospective phases standardize deployment practices and capture learnings to drive continuous improvement.

OctoAcme defines three core personas—**Developers** who implement features while maintaining code quality and identifying technical risks; **Product Managers** who own the vision, prioritize the backlog, and measure outcomes through success metrics; and **Project Managers** who coordinate delivery, manage schedules, risks, and stakeholder communication. The communication cadence includes daily standups focused on blockers and dependencies, weekly PM/PdM synchronization, twice-weekly team standups, monthly stakeholder updates, and ad-hoc escalations as needed. Clear ownership is assigned to each project, with named Project Managers and Product Leads responsible for driving alignment and removing obstacles.

Quality is embedded throughout execution via unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release, and security scanning in CI pipelines. The team uses a risk register to track identified issues by impact, likelihood, owner, and mitigation status, with risks reviewed weekly during syncs. Blocker escalation follows a three-level framework: team-level triage in standups, PM escalation to Product Leadership and dependent teams, and sponsor-level escalation for business-impacting issues. Additionally, OctoAcme tracks velocity, burndown, and key metrics identified in the Project One-pager to inform data-driven decisions and iterate based on evidence.

## Quick Start

- **New to OctoAcme projects?** Start with [Project Management Overview](./octoacme-project-management-overview.md)
- **Launching a new project?** Follow [Project Initiation Guide](./octoacme-project-initiation.md)
- **Ready to execute?** Refer to [Execution & Tracking](./octoacme-execution-and-tracking.md)

## Process Documents

### Strategy & Planning

- [**Project Management Overview**](./octoacme-project-management-overview.md) — Foundational principles, roles, and lifecycle
- [**Project Initiation**](./octoacme-project-initiation.md) — Validate business need and get stakeholder alignment
- [**Project Planning**](./octoacme-project-planning.md) — Break work into backlog, identify dependencies

### Delivery & Operations

- [**Execution & Tracking**](./octoacme-execution-and-tracking.md) — Daily standups, sprint workflows, quality standards
- [**Risk Management & Communication**](./octoacme-risks-and-communication.md) — Risk registers, stakeholder updates, escalation
- [**Release & Deployment**](./octoacme-release-and-deployment.md) — Pre-release checklist, deployment workflow, rollback

### Learning & Improvement

- [**Retrospective & Continuous Improvement**](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and improve processes

### Reference

- [**Roles & Personas**](./octoacme-roles-and-personas.md) — Understand team roles and responsibilities

## Project Lifecycle at a Glance

1. **Initiation** → Validate problem, align stakeholders, create one-pager
2. **Planning** → Break work into backlog, estimate, define DoD, identify risks
3. **Execution** → Daily standups, PR workflow, testing, tracking progress
4. **Release** → Pre-release checks, deploy, verify, communicate
5. **Retrospective** → Capture learnings, create action items, improve

## Key Principles

- 🎯 **Customer-first**: Prioritize customer value and usability
- 📈 **Iterative delivery**: Ship small, testable increments
- 👥 **Clear ownership**: Named PM and Product Lead per project
- 📊 **Data-informed**: Measure impact and iterate based on evidence
- 🤝 **Psychological safety**: Encourage feedback and learning

## How to Use These Docs

- Keep your Project Charter updated in your project repo
- Reference relevant docs during each project phase
- Add process-specific guidance to `.copilot/` if you want Copilot Spaces to use it
- Update docs when you discover process improvements or gaps

## Questions?

Refer to the relevant process doc or reach out to your Project Manager or Product Lead.
