# OctoAcme Project Management Docs

Purpose
This folder centralizes OctoAcme’s project management processes, templates, and working agreements. Keeping these artifacts together helps onboard new teammates, preserve institutional knowledge, and ensure consistent, repeatable execution across projects and releases.

Project management process summary
OctoAcme follows a structured lifecycle: initiation, planning, execution, release, and retrospective. Initiation captures the problem, stakeholders, success metrics, and a lightweight one‑pager that authorizes planning. Planning breaks approved initiatives into a prioritized backlog with acceptance criteria, estimates (T‑shirt/story sizes), a Definition of Done, and a release/milestone plan that highlights dependencies and risks.

Execution emphasizes small, shippable increments, disciplined pull request practices, and automated checks. Teams manage work on a project board (Backlog → Ready → In Progress → In Review → QA → Done), keep PRs small, and require CI (tests, linting, security scans) before review. Releases follow a type‑based checklist (patch/minor/major) and include staging smoke tests, rollback plans, and post‑deploy verifications to reduce production risk.

Roles, communication, and quality assurance
Roles are explicit: Product Managers define outcomes and prioritize, Project Managers coordinate delivery and communications, Developers implement and test, QA validates acceptance criteria, and Stakeholders provide input and approvals. Communication cadence includes daily standups, weekly delivery syncs, PM–PdM alignment meetings, regular demos, and milestone or monthly stakeholder updates. Risks and incidents are tracked in a risk register with clear escalation paths, and retrospectives convert learnings into actionable backlog items to support continuous improvement.

Docs index
- [Overview](octoacme-project-management-overview.md)
- [Initiation](octoacme-project-initiation.md)
- [Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

How to use this folder
- Keep the Project One‑pager, release notes, and key artifacts in this folder or link them from project repos so the docs remain the single source of truth.
- When starting a project, copy relevant templates (one‑pager, risk register, release checklist) into the project repo and update them in place.
- Use the .github issue templates to propose doc additions or corrections and include reviewers for process changes.
