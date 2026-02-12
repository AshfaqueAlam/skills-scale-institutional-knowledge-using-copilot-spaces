# OctoAcme Project Management Docs

## Overview

This repository centralizes all OctoAcme project management process documents. These documents detail our approach for project initiation, planning, execution, risk management, release, retrospectives, and roles.

## Quick Start

The OctoAcme methodology is built on these core principles:

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments rather than large releases
- **Clear ownership**: Each project has named roles with defined responsibilities
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

## Project Lifecycle

OctoAcme projects follow a structured five-phase lifecycle:

1. **Initiation** — Validate business need, identify stakeholders, define success metrics
2. **Planning** — Break work into shippable increments, identify dependencies and risks
3. **Execution** — Build, test, and review work using iterative delivery
4. **Release** — Deploy to production with proper verification and rollback planning
5. **Close & Retrospective** — Capture learnings and drive continuous improvement

## Core Roles

- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design, and ensure quality
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and strategic direction

For detailed role definitions, see [Roles & Personas](octoacme-roles-and-personas.md).

## Communication Cadence

OctoAcme maintains consistent communication to ensure alignment and visibility:

- **Daily standups** (15 min) — focus on progress, blockers, and dependencies
- **Weekly PM sync** — PM and PdM alignment on priorities and risks
- **Twice-weekly team standups** — delivery team progress and blockers
- **Monthly stakeholder updates** — high-level status and strategic updates
- **Ad-hoc escalations** — as needed for critical issues

## Process Docs Index

### Core Process Documents

- **[Project Management Overview](octoacme-project-management-overview.md)** — Introduction to OctoAcme principles, roles, artifacts, and lifecycle
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate and authorize new work, align stakeholders, and create initial plans
- **[Project Planning](octoacme-project-planning.md)** — Turning approved initiatives into actionable backlog and delivery plan
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Managing day-to-day execution, team rhythm, quality standards, and progress tracking
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identifying, assessing, mitigating, and communicating risks and dependencies
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardizing release processes to reduce risk and improve observability
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capturing learnings and converting them into actionable improvements
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed definitions of typical roles used in OctoAcme projects

## Key Artifacts

- **Project Charter / One-pager** — Problem statement, goals, success metrics, stakeholders, timeline
- **Roadmap and Release Plan** — High-level direction and milestone targets
- **Sprint/Iteration Backlog** — Detailed, prioritized work items with acceptance criteria
- **Risk Register** — Tracked risks with impact, likelihood, mitigation, and owner
- **Retrospective Notes** — Learnings and action items for continuous improvement
- **Release Notes** — Changes, migrations, and known issues for each release

## Definition of Done

Work is considered complete when it meets these criteria:

- ✅ All acceptance criteria are met and verified
- ✅ Code is reviewed and approved by at least one peer
- ✅ Unit tests are written and passing (new logic)
- ✅ Integration tests added where applicable
- ✅ CI/CD pipeline passes (tests, linting, security scanning)
- ✅ Manual QA completed for acceptance criteria
- ✅ Documentation updated (code comments, process docs as needed)
- ✅ Issue link included in PR description

## Quick Reference: When to Use Each Doc

| Situation | Document |
|-----------|----------|
| Starting a new project or feature | [Project Initiation Guide](octoacme-project-initiation.md) |
| Planning sprint work and backlog | [Project Planning](octoacme-project-planning.md) |
| Daily team coordination | [Execution & Tracking](octoacme-execution-and-tracking.md) |
| Managing project risks | [Risk Management & Communication](octoacme-risks-and-communication.md) |
| Deploying to production | [Release & Deployment Guide](octoacme-release-and-deployment.md) |
| Learning from sprint results | [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) |
| Understanding team roles | [Roles & Personas](octoacme-roles-and-personas.md) |

## Contributing to Process Docs

To suggest updates or new content for OctoAcme process documentation:

1. Open a new issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
2. Include a summary of the new content, rationale, and (if available) suggested wording
3. Link the issue to this project board for tracking
4. A process owner will review and merge the update

## Questions?

If you have questions about OctoAcme project management processes:

- **For process clarification**: Review the relevant document and open a discussion issue
- **For project-specific guidance**: Contact your Project Manager
- **For strategic alignment**: Contact your Product Manager or team lead

---

**Last Updated**: 2026-02-12  
**Maintained by**: OctoAcme Project Management Community
