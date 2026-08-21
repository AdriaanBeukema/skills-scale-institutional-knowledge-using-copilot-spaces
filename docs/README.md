# OctoAcme Project Management Documentation

## Executive Overview

OctoAcme operates projects through a structured lifecycle that progresses from initiation through planning, execution, release, and retrospective phases. The approach is grounded in clear stakeholder alignment and measurable outcomes. Three core delivery roles drive every project: **Project Managers** who coordinate schedules, risks, and communications; **Product Managers** who define what should be built and prioritize the backlog; and **Developers** who implement features and collaborate on quality.

Teams maintain a consistent communication cadence of daily standups (15 minutes), weekly delivery syncs, and end-of-sprint demos, supplemented by monthly stakeholder updates and ad-hoc incident communication when needed. Quality assurance is embedded throughout delivery with unit tests, integration tests, and end-to-end smoke tests before release, alongside continuous security scanning in CI/CD. Risk management is continuous: risks are captured in a register, reviewed weekly, and escalated through defined levels from team triage to sponsor escalation. Every sprint, release, or milestone closes with a retrospective that captures learnings and assigns 2–3 prioritized action items, fostering a culture of psychological safety and continuous improvement.

---

## Process Lifecycle Navigation

| Phase | Document |
|---|---|
| Initiation | [Project Initiation](./octoacme-project-initiation.md) |
| Planning | [Project Planning](./octoacme-project-planning.md) |
| Execution & Tracking | [Execution and Tracking](./octoacme-execution-and-tracking.md) |
| Risk Management & Communication | [Risks and Communication](./octoacme-risks-and-communication.md) |
| Release & Deployment | [Release and Deployment](./octoacme-release-and-deployment.md) |
| Retrospective & Continuous Improvement | [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) |

---

## Reference Documents

- [Project Management Overview](./octoacme-project-management-overview.md) — High-level summary of OctoAcme's end-to-end project management approach.
- [Roles & Personas](./octoacme-roles-and-personas.md) — Detailed descriptions of each role and their responsibilities.

---

## Key Artifacts

- **Project One-pager** — Problem statement, objectives, success metrics, and key stakeholders used for go/no-go decisions.
- **Prioritized Backlog** — Backlog items with acceptance criteria and T-shirt sizing or story point estimates.
- **Dependency & Release Timeline Map** — Visual map of work dependencies and target release milestones.
- **GitHub Projects Board** — Workflow board with columns: Backlog → Ready → In Progress → In Review → QA → Done.
- **Risk Register** — Log of risks with impact, likelihood, owner, and mitigation plan; reviewed weekly.
- **Weekly Status Update** — Structured template covering progress, next steps, risks, and decisions needed.
- **Retrospective Action Items** — 2–3 prioritized improvement actions with owners and due dates from each retrospective.

---

## How to Use This Documentation

**Starting a new project?**
Begin with the [Project Management Overview](./octoacme-project-management-overview.md) to understand the full lifecycle, then work through [Project Initiation](./octoacme-project-initiation.md) to align stakeholders and create your Project One-pager.

**Mid-project?**
Navigate directly to the phase document that matches your current stage in the [Process Lifecycle Navigation](#process-lifecycle-navigation) table above.

**New to the team?**
Review [Roles & Personas](./octoacme-roles-and-personas.md) to understand your responsibilities, then read the [Project Management Overview](./octoacme-project-management-overview.md) for context.

**Preparing for release?**
See [Release and Deployment](./octoacme-release-and-deployment.md) for release criteria, rollback planning, and smoke test requirements.

**After a sprint or milestone?**
Follow the [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) guide to run a structured retrospective and capture action items.

---

## Contributing

To propose updates to any process documentation:

1. Open a GitHub Issue describing the proposed change and the reason for it.
2. Create a feature branch from `main` (e.g., `docs/update-release-process`).
3. Make your changes to the relevant file(s) in the `docs/` folder.
4. Open a Pull Request with a clear description and link to the issue (e.g., `Closes #<issue-number>`).
5. Request a review from at least one team member familiar with the affected process.
6. Address review feedback, then merge once approved.

All documentation changes should maintain consistent Markdown formatting and ensure all internal links remain valid.
