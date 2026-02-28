# Role Responsibilities, Interaction Templates & RACI

This file contains templates and checklists to make role responsibilities explicit, reduce ambiguity, and improve handoffs.

---

## 1) Role Responsibilities Template

Use this template to document role responsibilities for a specific project or program.

- Role:
- Primary responsibilities (3–6 bullets):
- Typical deliverables:
- Key interactions (who they hand off to / who they consult):
- RACI for major milestones:
- Notes / Project-specific exceptions:

Example (Release Manager)
- Role: Release Manager
- Primary responsibilities:
  - Maintain release timeline and checklist
  - Validate pre-release sign-offs (QA, security, docs)
  - Coordinate deployment and post-release verification
- Typical deliverables: Release checklist, rollback plan, release notes
- Key interactions: PM (schedule), QA (readiness), Devs (deploy), Support (post-release)
- RACI: Responsible: Release Manager; Accountable: PM; Consulted: QA, Devs; Informed: Stakeholders

---

## 2) RACI Matrix Template (simple table)

Create a short RACI for a given milestone or deliverable. Columns are role names; rows are major activities.

Activity | PM | PdM | Dev | QA | UX | BA | Release Manager
--- | ---: | ---: | ---: | ---: | ---: | ---: | ---:
Define success metrics | A | R | - | - | - | C | -
Backlog refinement | C | R | C | C | C | C | -
Development & unit testing | I | C | R | I | I | I | -
Release validation & deploy | I | C | I | R | I | I | A

Legend: R = Responsible, A = Accountable, C = Consulted, I = Informed

---

## 3) Role Handoff / Readiness Checklist (example)

When moving work from one stage to another (e.g., Sprint → Release), use this checklist:

- Backlog item has clear acceptance criteria (PdM, BA)
- UX artifacts attached and accessible (UX)
- Automated tests for new logic in place (Dev)
- Manual QA test plan created (QA)
- Performance/security scans passed (Dev, Sec)
- Release checklist prepared (Release Manager)
- Stakeholders informed of release window (PM)

---

## 4) How to use these templates

- Add a filled Role Responsibilities Template to the Project One-pager for each named role.
- Include a RACI snapshot for major milestones in planning docs.
- Use the Handoff checklist as a required step in the release checklist (docs/release-and-deployment or project-specific release docs).

---

## 5) Acceptance criteria for adding/updating roles

- Roles are named and responsibilities are actionable
- Interaction points are documented and applied in project artifacts (one-pager, backlog)
- Teams use the handoff and RACI templates during planning and releases
