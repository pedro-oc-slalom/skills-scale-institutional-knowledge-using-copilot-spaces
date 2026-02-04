# OctoAcme Project Management Docs — README

This README provides a summary of OctoAcme's project management workflow and quick access links to all main process documents.

## Project Management Processes Overview

OctoAcme uses an iterative, stakeholder-driven project management approach designed to deliver customer value efficiently while maintaining transparency and quality:

- **Project Initiation** begins with clarity around objectives, metrics, and stakeholders. We validate business need and create a lightweight project one-pager to ensure alignment before moving into planning.

- **Planning** breaks work into shippable increments, aligns resources and timelines, and documents acceptance criteria. We identify dependencies, risks, and create release plans with clear milestones.

- **Execution and Tracking** uses project boards and checklists to follow progress and resolve blockers. Daily standups and weekly syncs keep the team aligned, while PR workflows and automated CI ensure code quality.

- **Risks and Communication** are managed via a risk register and proactive stakeholder updates. We maintain weekly status reports and clear escalation paths to address issues quickly.

- **Release & Deployment** processes ensure standardized testing, verification, and incident response. Each release follows a checklist including smoke tests, rollback plans, and post-deployment verification.

- **Retrospectives** feed continuous improvement into team workflows. After each sprint or milestone, we capture learnings and convert them into actionable improvements.

- **Roles and Personas** are clearly defined for ownership and collaboration, including Project Managers, Product Managers, Developers, QA/Testing, and Stakeholders.

## Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named PM and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Roles & Responsibilities

- **Project Manager (PM)**: Coordinates delivery, schedules, risk, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

## Communication Cadence

- **Daily standups** (15 min) — focus on progress, blockers, dependencies
- **Weekly sync** between PM + PdM
- **Twice-weekly standups** for delivery team (or as agreed)
- **Weekly delivery sync** — show progress, updates, and flagged risks
- **Monthly stakeholder updates**
- **Demo/Review** at the end of each sprint or milestone
- **Ad-hoc escalations** as needed

## Quality Assurance Practices

- **Unit tests** for new logic
- **Integration tests** where applicable
- **End-to-end smoke tests** for critical flows before release
- **Security scanning** in CI pipelines
- **Code reviews** with at least one approval before merging
- **Manual QA** for feature acceptance when needed
- **Automated CI/CD** with tests and linting before deployment

## Key Workflows

### Pull Request Workflow
- Small PRs (<= 400 lines when possible)
- Include issue link and acceptance criteria in PR description
- Run automated tests and linting in CI before requesting review
- Require at least one approval before merging

### Project Board Workflow
Columns: **Backlog** → **Ready** → **In Progress** → **In Review** → **QA** → **Done**

## Links to Process Documentation

- [Project Management Overview](octoacme-project-management-overview.md) — Core principles, roles, artifacts, and lifecycle
- [Project Initiation Guide](octoacme-project-initiation.md) — How to validate and authorize new work
- [Project Planning](octoacme-project-planning.md) — Creating actionable plans and backlogs
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day execution and progress tracking
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Identifying, managing, and communicating risks
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Standardized release processes
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings and improvements
- [Roles & Personas](octoacme-roles-and-personas.md) — Detailed role definitions and responsibilities

## Getting Started

New to OctoAcme? Start here:

1. Read the [Project Management Overview](octoacme-project-management-overview.md) for core principles
2. Review [Roles & Personas](octoacme-roles-and-personas.md) to understand your responsibilities
3. Check [Execution & Tracking](octoacme-execution-and-tracking.md) for daily workflows
4. Keep the [Risk Management & Communication](octoacme-risks-and-communication.md) guide handy for updates

## How to Use These Docs

- Keep the Project Charter updated in the project repo
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context
- Refer to these docs during project kickoffs and retrospectives
- Update these docs as processes evolve

---

_For questions or suggestions about these processes, contact your Project Manager or Product Lead._
