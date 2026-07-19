# OctoAcme Project Management Docs

This README aggregates OctoAcme's project management process documents and provides a concise summary of the processes so team members and newcomers can quickly find guidance.

## Summary of Project Management Processes

OctoAcme follows an **iterative, outcome-driven approach** with clear roles and lightweight artifacts designed to maximize transparency and deliver customer value.

### Core Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead (PdM)
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

### Key Elements
- **Iterative delivery** with small, testable increments
- **Clear ownership**: Project Manager (PM) and Product Lead (PdM) per project
- **Regular cadence**: Daily standups, weekly delivery syncs, sprint demos/reviews
- **Key artifacts**: Project one-pager, backlog, release plan, risk register, Definition of Done, acceptance criteria
- **Workflows**: Project board with columns (Backlog → Ready → In Progress → In Review → QA → Done); PRs with acceptance criteria and CI checks; testing and security scans before release
- **Risk & escalation**: Documented risk register and defined escalation paths (Team → PM → Product Lead → Sponsor)

### Project Lifecycle (High-Level)
1. **Initiation**: Problem statement, stakeholders, high-level timeline
2. **Planning**: Scope, resources, milestones, dependencies
3. **Execution**: Build, test, review, iterate
4. **Release**: Deploy, verify, announce
5. **Close & Retrospective**: Capture learnings and next steps

---

## Process Documentation

- [**Project Management Overview**](octoacme-project-management-overview.md) — Introduction to roles, artifacts, and lifecycle
- [**Project Initiation Guide**](octoacme-project-initiation.md) — Steps to validate and authorize new work
- [**Project Planning**](octoacme-project-planning.md) — Turn an approved initiative into an actionable plan and backlog
- [**Execution & Tracking**](octoacme-execution-and-tracking.md) — Guidance for day-to-day execution and progress tracking
- [**Risk Management & Communication**](octoacme-risks-and-communication.md) — How to identify, manage, and communicate risks
- [**Release & Deployment**](octoacme-release-and-deployment.md) — Standardize releases to production
- [**Retrospective & Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and drive improvements
- [**Roles & Personas**](octoacme-roles-and-personas.md) — Definitions of core roles and responsibilities

---

## How to Use These Docs

### For Team Members
- **Getting started?** Start with the [Project Management Overview](octoacme-project-management-overview.md)
- **Starting a new project?** Follow the [Initiation Guide](octoacme-project-initiation.md) and [Planning](octoacme-project-planning.md) documents
- **Managing day-to-day work?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md)
- **Preparing a release?** Use the [Release & Deployment](octoacme-release-and-deployment.md) guide
- **Learning your role?** See [Roles & Personas](octoacme-roles-and-personas.md)

### For Project Repositories
- Keep the **Project One-pager** updated in your project repo
- Add process-specific docs into `.copilot/` if you want [Copilot Spaces](https://github.com/features/copilot-spaces) to use them as context
- Link to this README from your project README

### Proposing Updates
- Use the issue template [`.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose updates or new content
- Updates should be reviewed and aligned with the Product Lead before merging

---

## Quick Reference: Key Artifacts

| Artifact | Purpose | Owner | Cadence |
|----------|---------|-------|----------|
| Project One-pager | Define problem, goal, success metrics | PM / PdM | Initiation |
| Risk Register | Track and monitor identified risks | PM | Weekly |
| Project Board | Visualize work flow and status | PM / Team | Ongoing |
| Sprint Backlog | Define work for current sprint | PdM / Team | Sprint cycle |
| Release Plan | Map milestones and release schedule | PM / PdM | Planning |
| Retrospective Notes | Capture learnings and action items | PM | Post-sprint/release |

---

## Communication Cadence

- **Daily**: Team standups (15 min) — progress, blockers, dependencies
- **Twice-weekly**: Team standups for delivery (or as agreed)
- **Weekly**: PM + PdM sync; weekly delivery sync with stakeholders
- **Monthly**: Stakeholder updates and reviews
- **Ad-hoc**: Escalations and incident communications

---

## Questions or Feedback?

For suggestions on improving these docs, [open an issue](../../issues/new?template=add-update-content-to-process-docs.yml) using the process documentation update template.
