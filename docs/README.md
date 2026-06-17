# OctoAcme Project Management Docs

Welcome to the OctoAcme project management process documentation. This README provides a brief overview of our project management approach and direct links to the detailed process documents stored in this folder.

## Overview of OctoAcme Project Management

OctoAcme operates a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The organization follows a five-stage lifecycle: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. Each stage is gated by decision points and supported by lightweight, purpose-driven artifacts. In the Initiation phase, teams create a Project One-pager that defines the business problem, measurable success metrics, stakeholder alignment, and resource needs—with a go/no-go decision made once success criteria are clear. Once approved, the Planning phase breaks work into shippable increments with prioritized backlogs, acceptance criteria, and a release timeline.

Execution and delivery are governed by a **team rhythm and project board workflow** that balances daily communication with sustainable pace. OctoAcme uses daily 15-minute standups, weekly delivery syncs, and regular demos to track progress and surface blockers early. Work flows through a GitHub Projects board with columns spanning Backlog, Ready, In Progress, In Review, QA, and Done. Pull requests are kept small (≤400 lines when possible) and must include issue links and acceptance criteria. Quality is enforced through CI-driven testing (unit, integration, and end-to-end smoke tests), security scanning, and manual QA for feature acceptance. A three-level escalation path—team triage → PM/Product Lead → Sponsor—ensures blockers are addressed swiftly without bottlenecks.

**Core roles** are clearly defined to enable accountability and cross-functional collaboration. **Developers** implement features, own testing and documentation, and help identify technical risks. **Product Managers** define what to build, prioritize the backlog, and measure outcomes through success metrics. **Project Managers** coordinate timelines, manage risks and dependencies, and ensure transparent stakeholder communication. This division of responsibility is reinforced through a **communication cadence** that includes weekly syncs between PM and Product Manager, twice-weekly standups for delivery teams, and monthly stakeholder updates. Risk and dependency management is continuous—teams maintain a Risk Register updated weekly and use the same project board to flag cross-team dependencies during weekly syncs.

**Release, retrospectives, and continuous improvement** close the feedback loop and build institutional learning. Before any production deployment, teams ensure all acceptance criteria are met, CI/security scans pass, release notes are drafted, and rollback plans are documented. After each sprint, release, or milestone, the team runs a 45–75 minute retrospective to capture what went well, what could improve, and to prioritize 2–3 actionable improvements with clear owners and due dates. These action items are tracked in the project backlog, reviewed in weekly PM syncs, and measured for impact. This emphasis on retrospectives and continuous improvement reflects OctoAcme's commitment to psychological safety, data-informed decisions, and iterative refinement of both product and process.

## Key Artifacts & Activities

- **Project One-pager**: Problem statement, goals, success metrics, stakeholders, timeline, risks, and proposed team
- **Roadmap & Release Plan**: High-level timeline with milestones and release cadence
- **Prioritized Backlog**: Work items with acceptance criteria, estimates, and ownership
- **Definition of Done (DoD)**: Shared acceptance criteria for all completed work
- **Risk Register**: Tracked risks with impact, likelihood, mitigation plans, and status
- **Retrospective Notes**: Learnings and action items from sprints and releases

## Core Roles

- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, measures success
- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications
- **Developers**: Implement features, write tests, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and business context

## Communication Cadence

- **Daily**: 15-minute standups (team focus on progress, blockers, dependencies)
- **Weekly**: PM/PdM sync, delivery team standups, risk register review
- **Bi-weekly/Sprint-based**: Sprint planning and demo/review
- **Monthly**: Stakeholder updates
- **Ad-hoc**: Escalations and incident communications

## Process Documents

- [**Project Management Overview**](octoacme-project-management-overview.md) — High-level introduction to roles, principles, lifecycle, and key artifacts
- [**Project Initiation Guide**](octoacme-project-initiation.md) — Steps to validate, authorize, and kick off a new project
- [**Project Planning**](octoacme-project-planning.md) — Breaking work into shippable increments, backlog prioritization, and release planning
- [**Execution & Tracking**](octoacme-execution-and-tracking.md) — Day-to-day delivery, team rhythm, quality standards, and blocker escalation
- [**Release & Deployment Guide**](octoacme-release-and-deployment.md) — Pre-release requirements, deployment checklist, rollback procedures, and release notes
- [**Risk Management & Communication**](octoacme-risks-and-communication.md) — Identifying, tracking, and communicating risks, dependencies, and escalations
- [**Retrospective & Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) — Running effective retrospectives and converting learnings into actionable improvements
- [**Roles & Personas**](octoacme-roles-and-personas.md) — Detailed descriptions of typical roles and responsibilities in OctoAcme projects

## How to Use These Docs

- **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md) to understand our principles and lifecycle
- **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md) and use the templates provided
- **In execution?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for team rhythm and quality standards
- **Preparing a release?** Use the checklist and procedures in [Release & Deployment Guide](octoacme-release-and-deployment.md)
- **Running a retrospective?** See [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) for structure and templates

## Contributing to Process Docs

To propose updates or additions to these documents, create an issue using the [**Add Content to Project Management Process Docs**](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template. Include:
- Which document(s) you want to update
- A summary of the new content
- Why the update is needed
- Suggested wording (optional)

All updates should be reviewed by the Product Lead and relevant stakeholders before merging.
