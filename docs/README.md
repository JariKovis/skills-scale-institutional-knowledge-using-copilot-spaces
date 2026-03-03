# OctoAcme Project Management — Documentation Overview

This directory contains OctoAcme's project management process documentation. The guides below describe how cross-functional teams at OctoAcme initiate, plan, execute, release, and continuously improve product work. Together they form a lightweight, repeatable framework applicable to any feature, service, or integration project.

## Key Workflows

OctoAcme follows a five-phase lifecycle: **Initiation → Planning → Execution & Tracking → Release & Deployment → Retrospective & Continuous Improvement**.

- **Initiation** confirms the business need, defines success metrics, and produces a Project One-pager before a go/no-go decision is made.
- **Planning** converts the approved initiative into a prioritized backlog with acceptance criteria, a Definition of Done, a risk register, and a milestone map.
- **Execution & Tracking** moves work through a GitHub Projects board (Backlog → Ready → In Progress → In Review → QA → Done), with twice-weekly standups and a weekly delivery sync to surface blockers early.
- **Release & Deployment** classifies releases as patch, minor, or major; each requires passing CI and security scans, merged PRs, drafted release notes, and a rollback plan before deployment proceeds.
- **Retrospective & Continuous Improvement** captures what went well, what to improve, and 2–3 prioritized action items after every sprint, release, or incident, feeding improvements back into the backlog.

## Personas and Roles

Five core roles collaborate on every project:

- **Project Manager (PM):** coordinates delivery, maintains the project plan and risk register, facilitates meetings (kickoff, planning, retrospectives), and drives cross-team communication.
- **Product Manager (PdM):** owns the product vision, prioritizes the roadmap and backlog, defines problem statements and success metrics, and validates solutions with user research and data.
- **Developers:** implement features and fixes against acceptance criteria, write and maintain tests and documentation, and participate in design and code reviews.
- **QA/Testing:** validates quality and verifies that acceptance criteria are met before release.
- **Stakeholders:** provide inputs, approvals, and business context throughout the lifecycle.

Detailed responsibilities and communication patterns for each role are documented in [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md).

## Communication Strategies

OctoAcme maintains a predictable communication cadence:

- **Weekly PM + PdM sync** for alignment on priorities and risks
- **Twice-weekly team standups** to surface blockers and track progress
- **Monthly stakeholder updates** plus ad-hoc escalations when needed

The project README or release document serves as the **single source of truth** for current status. Structured templates keep updates consistent:

- **Weekly Status:** progress, next steps, risks/blockers, decisions needed
- **Incident Communication:** triage summary, actions in flight, expected timeline, and a scheduled post-incident blameless retrospective

Escalation follows a clear path: team-level triage → PM → Product Lead → Sponsor, with security incidents routed directly to the security on-call runbook. Full details are in [`octoacme-risks-and-communication.md`](octoacme-risks-and-communication.md).

## Quality Assurance Practices

Quality is built into every phase. Pull requests should be small (≤ 400 lines when possible), must include a linked issue and acceptance criteria in the description, and require at least one approval after automated tests and linting pass in CI. The test strategy layers **unit tests** for new logic, **integration tests** where applicable, and **end-to-end smoke tests** for critical flows. **Security scanning** runs in CI on every PR, and passing security scans is a hard pre-release requirement. Before any production deployment, the full deployment checklist is completed: staging smoke tests, post-deploy verifications, and a stakeholder announcement. Rollback and incident playbooks are prepared in advance so the team can respond quickly if a release causes issues. See [`octoacme-execution-and-tracking.md`](octoacme-execution-and-tracking.md) and [`octoacme-release-and-deployment.md`](octoacme-release-and-deployment.md) for the complete checklists.

---

## Document Index

| Document | Description |
|---|---|
| [`octoacme-project-management-overview.md`](octoacme-project-management-overview.md) | High-level introduction to OctoAcme's project management approach |
| [`octoacme-project-initiation.md`](octoacme-project-initiation.md) | Initiation guide: one-pager template, stakeholder alignment, decision gate |
| [`octoacme-project-planning.md`](octoacme-project-planning.md) | Planning guide: backlog creation, sprint planning, risk register |
| [`octoacme-execution-and-tracking.md`](octoacme-execution-and-tracking.md) | Execution guide: team rhythm, PR workflow, quality & testing, escalation |
| [`octoacme-risks-and-communication.md`](octoacme-risks-and-communication.md) | Risk management and communication templates |
| [`octoacme-release-and-deployment.md`](octoacme-release-and-deployment.md) | Release types, deployment checklist, rollback playbook |
| [`octoacme-retrospective-and-continuous-improvement.md`](octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure and continuous improvement tracking |
| [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md) | Role definitions: Developers, Product Managers, Project Managers |
