# OctoAcme Project Management Docs

Welcome to the OctoAcme project management process documentation. This repository centralizes our core workflows, best practices, and templates used to manage projects within OctoAcme.

## Overview

OctoAcme runs projects with a lightweight but consistent lifecycle: **Initiation → Planning → Execution → Release → Close/Retrospective**. Work begins when a new idea is ready to explore, using a **Project One-pager** to define the problem, SMART objective, success metrics, stakeholders, timeline/milestones, and initial risks/dependencies. A clear decision gate is used to move forward only once success metrics and priority are aligned and team availability is confirmed, ensuring projects start with explicit authorization and shared expectations.

Roles are intentionally explicit to keep ownership clear. A **Project Manager (PM)** coordinates delivery (schedule, risks, dependencies, communications), while a **Product Manager (PdM/Product Lead)** defines outcomes, prioritizes the backlog, and measures success. **Developers** implement features with attention to testability and maintainability, and **QA/Testing** validates quality and acceptance criteria. These roles collaborate via standard artifacts—backlog items with acceptance criteria, Definition of Done, release plans, and risk registers—so decisions and progress remain transparent and reproducible.

Execution emphasizes predictable day-to-day workflows and clear status tracking. Teams use a project board (e.g., **Backlog → Ready → In Progress → In Review → QA → Done**) and maintain a steady cadence: short standups for blockers and dependencies, weekly delivery syncs for progress and risks, and demos at the end of sprints or milestones. Risk and dependency management is formalized through a **risk register** (impact/likelihood/owner/mitigation/status) and an escalation path that starts with team triage and can move from PM to Product Lead to Sponsor when business impact warrants it.

Quality and release practices are built into the workflow rather than treated as a final step. PRs are expected to be small when possible, include issue links and acceptance criteria, and pass CI (tests, lint, and security scanning) before review, with at least one approval required prior to merge. Releases follow a checklist mindset: confirm acceptance criteria and scans, draft release notes, plan rollback/mitigation, validate in staging with smoke tests, verify post-deploy, and communicate outcomes to stakeholders and support. OctoAcme reinforces continuous improvement through regular retrospectives (including after incidents) and tracks action items as backlog work with clear owners, timelines, and success criteria.

## Key Workflows at a Glance

- **Lifecycle stages:** Initiation → Planning → Execution & Tracking → Risk Management & Communication → Release & Deployment → Retrospective & Continuous Improvement
- **Project board flow:** Backlog → Ready → In Progress → In Review → QA → Done
- **PR flow:** Small PRs with issue links and acceptance criteria → CI (tests, lint, security scan) → at least one approval → merge
- **Communication cadences:** Daily standups (blockers/dependencies), weekly delivery syncs (progress/risks), end-of-sprint demos
- **Escalation path:** Team triage → PM → Product Lead → Sponsor

## Docs Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level overview of OctoAcme's end-to-end project management approach |
| [Project Initiation](octoacme-project-initiation.md) | How to kick off a project: one-pager, success metrics, stakeholder alignment |
| [Project Planning](octoacme-project-planning.md) | Backlog creation, milestone planning, scope estimation, and dependency mapping |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day workflows, project board usage, standups, and status reporting |
| [Risks & Communication](octoacme-risks-and-communication.md) | Risk register, communication templates, escalation paths, and stakeholder updates |
| [Release & Deployment](octoacme-release-and-deployment.md) | Release checklist, staging validation, rollback planning, and post-deploy verification |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retro formats, action item tracking, and feeding improvements back into the process |
| [Roles & Personas](octoacme-roles-and-personas.md) | Definitions and responsibilities for PM, Product Lead, Developers, QA, UX, DevOps, BA, and Stakeholders |
| [Role Handoff Checklist](octoacme-role-handoff-checklist.md) | Lightweight checklist for explicit, low-friction handoffs between roles at each lifecycle stage |
| [Definition of Ready / Definition of Done](octoacme-definition-of-ready-done.md) | Shared quality gates (DoR and DoD) and a RACI-lite matrix for key delivery checkpoints |

## How to Use These Docs

- **Onboarding?** Start with the [Project Management Overview](octoacme-project-management-overview.md) and [Roles & Personas](octoacme-roles-and-personas.md) to orient yourself.
- **Starting a new project?** Follow the [Project Initiation](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md) guides.
- **During delivery?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risks & Communication](octoacme-risks-and-communication.md) as needed.
- **Preparing a release?** Use the [Release & Deployment](octoacme-release-and-deployment.md) checklist.
- **After a project or incident?** Run a retro using the [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) guide.

## Contributing Updates

Found an error or want to suggest an improvement to any of these docs? Please submit an issue using the [process docs issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) in `.github/ISSUE_TEMPLATE/`. All contributions are welcome—clear ownership of process knowledge helps the whole team.
