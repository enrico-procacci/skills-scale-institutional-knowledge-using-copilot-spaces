# OctoAcme Project Management Documentation

This README serves as the entry point and directory for all OctoAcme project management process documentation.

## About OctoAcme Project Management Processes

OctoAcme uses an iterative, customer-first approach to project management built on clear roles, lightweight planning, cross-team collaboration, and continuous improvement. Our processes emphasize:

- **Clear ownership and accountability** — Each project has a named Project Manager (PM) and Product Lead responsible for delivery and outcomes
- **Aligning stakeholders and defining success upfront** — We validate business needs, identify stakeholders, and establish measurable success criteria before planning begins
- **Breaking work into shippable increments with risk management** — We deliver small, testable features iteratively while actively identifying and mitigating risks
- **Regular tracking, reporting, and retrospectives** — We maintain consistent communication cadences, measure progress, and capture learnings to drive continuous improvement

## Project Lifecycle at OctoAcme

OctoAcme projects follow a five-phase lifecycle:

1. **Initiation** — Validate business need, align stakeholders, and create a Project One-pager with problem statement, goals, success metrics, and initial timeline
2. **Planning** — Break work into prioritized backlog items with acceptance criteria, estimate scope, identify dependencies, and establish a release plan
3. **Execution** — Build, test, and iterate using daily standups, weekly syncs, and a standardized project board workflow (Backlog → Ready → In Progress → In Review → QA → Done)
4. **Release** — Deploy features to production following pre-release checks (CI/security pass, release notes, smoke tests) with documented rollback procedures
5. **Close & Retrospective** — Capture learnings, celebrate wins, and convert action items into the backlog for continuous improvement

## Core Roles & Communication

**Three primary personas** drive OctoAcme projects:

- **Project Managers** — Coordinate delivery, manage schedules, risks, and stakeholder communications
- **Product Managers** — Define outcomes, prioritize backlogs, and measure success
- **Developers (+ QA/Testing)** — Implement features and validate quality against acceptance criteria

**Communication cadence** ensures alignment and rapid issue resolution:

- Daily standups (15 minutes) — focus on progress and blockers
- Weekly delivery sync — PM and Product Manager review progress and risks
- Twice-weekly team standups — full delivery team coordination
- Monthly stakeholder updates — executive visibility and strategic alignment
- Clear escalation paths — team-level → PM → Product Lead → Sponsor

## Execution & Quality Standards

- **Small pull requests** (≤400 lines) with automated CI testing, linting, and security scanning
- **Quality assurance** — Unit tests, integration tests, end-to-end smoke tests, and manual QA as needed
- **Risk management** — Maintain a Risk Register tracking ID, description, impact, likelihood, owner, and mitigation plan; review weekly
- **Project board workflow** — Standardized columns ensure transparency and enable accurate burndown tracking
- **Pre-release requirements** — All acceptance criteria met, CI/security scans passing, release notes drafted, smoke tests prepared

## OctoAcme Process Docs Index

Use the following documents to dive deeper into specific phases and practices:

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme principles, roles, and lifecycle
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate need, align stakeholders, and create a Project One-pager
- **[Project Planning](octoacme-project-planning.md)** — How to break work into shippable increments and create a prioritized backlog
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day workflows, team rhythm, and progress tracking
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Managing risks and dependencies with consistent stakeholder updates
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardized process for releasing features to production
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capturing learnings and converting action items into improvements
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed responsibilities and goals for Project Managers, Product Managers, and Developers

## Quick Start for New Projects

1. **Initiation** — Start with the [Project Initiation Guide](octoacme-project-initiation.md) to create your Project One-pager
2. **Planning** — Use the [Project Planning](octoacme-project-planning.md) guide to structure your backlog and timeline
3. **Execution** — Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for day-to-day workflows
4. **Risk Management** — Use the [Risk Management & Communication](octoacme-risks-and-communication.md) template to track and escalate risks
5. **Release** — Follow the [Release & Deployment Guide](octoacme-release-and-deployment.md) for production deployments
6. **Close** — Run a retrospective using the [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) guide

## Using These Docs with Copilot Spaces

To enable context-aware assistance for your project, add this README and relevant process docs to a Copilot Space. This grounds Copilot in OctoAcme's specific practices and enables role-specific guidance tailored to your team's needs.

## Contributing to Process Documentation

If you'd like to suggest improvements, additions, or clarifications to our project management processes:

1. Open an issue using the ["Add Content to Project Management Process Docs"](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
2. Provide a summary of the proposed content and rationale
3. Include suggested text or examples if available
4. Ensure your update aligns with existing docs and improves clarity

---

**Last updated:** 2026-04-14  
**Owner:** OctoAcme Program Management Team
