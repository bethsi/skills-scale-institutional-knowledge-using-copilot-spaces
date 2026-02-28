# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA / Testing

(Previously "QA/Testing" referenced in other docs—kept as the team's testing function.)

### Role Summary
QA/Testing validates quality and acceptance criteria; performs exploratory and manual testing when needed and verifies automated test coverage.

### Responsibilities
- Create and execute test plans for features
- Maintain and improve automated test suites
- Validate acceptance criteria and perform regression checks
- Report and track quality-related risks and issues

### Typical Communication
- Release readiness checks with PM and Release Manager
- Test reports and bug triage notes

---

## Stakeholders

### Role Summary
Stakeholders provide business context, input, and approvals. They include sponsor(s), business owners, and key partners.

### Typical Communication
- Monthly stakeholder updates
- Decision meetings and sign-offs as needed

---

## New / Expanded Personas

To close gaps and improve clarity we add the following personas. For each persona we provide role summary, responsibilities, and how they typically interact with existing roles.

---

### Scrum Master

Role Summary
- Facilitates the team's agile ceremonies, removes impediments, and helps the team follow agreed agile practices.

Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Help the team remove blockers and escalate impediments appropriately
- Coach the delivery team and stakeholders on agile practices and team health
- Track action items from retrospectives to closure

Interactions
- Works closely with Project Manager to align cadence and escalations
- Supports Developers and QA by clearing operational obstacles
- Partners with Product Manager on backlog readiness and sprint commitments

---

### Business Analyst (BA)

Role Summary
- Bridges product and delivery by clarifying requirements, documenting business rules, and validating acceptance criteria.

Responsibilities
- Elicit and document requirements and user stories
- Maintain clear acceptance criteria and example scenarios
- Coordinate stakeholder interviews and clarify edge cases
- Support PdM and Developers during refinement and implementation

Interactions
- Works directly with Product Managers to detail priorities and acceptance criteria
- Collaborates with Developers and QA to ensure requirements are testable and understood
- Informs Project Managers of scope clarifications that affect timelines

---

### UX Designer

Role Summary
- Owns user experience design, research outputs, and usability validation to ensure the product is intuitive and usable.

Responsibilities
- Produce user flows, wireframes, prototypes, and design specs
- Conduct usability testing and incorporate feedback
- Provide design tokens, accessibility guidance, and handoff artifacts to Developers
- Advocate for user needs during planning and prioritization

Interactions
- Partners with Product Managers early in discovery to shape requirements
- Works with Developers and QA to ensure design intent is implemented and verified
- Shares findings with Project Manager if design changes affect scope or schedule

---

### Release Manager

Role Summary
- Coordinates release planning, release execution, and rollback/mitigation plans to reduce deployment risk.

Responsibilities
- Create and maintain release timelines and checklists
- Verify release readiness (CI, security, QA sign-offs, documentation)
- Coordinate cross-team release activities and communicate windows
- Maintain rollback plans and runbook references

Interactions
- Works with Project Managers and Product Managers to schedule releases
- Coordinates with QA, Developers, and Support for release verification and post-release monitoring
- Escalates release blockers to stakeholders when necessary

---

### Quality Lead

Role Summary
- Oversees quality strategy, test coverage, and acceptance standards across the program to ensure consistent quality outcomes.

Responsibilities
- Define test strategy and quality metrics for a program or product line
- Review acceptance criteria and test coverage during planning
- Mentor QA engineers and support automated testing initiatives
- Track quality trends and feed back into planning and retrospectives

Interactions
- Works with Project Managers and Product Managers to set quality goals
- Collaborates with Developers and QA teams to improve test automation and coverage
- Supports Release Manager in gating criteria for releases

---

## Using these personas in OctoAcme processes

- Add the primary role(s) for feature/epic in the Project One-pager and backlog items (owner fields).
- Use the persona definitions during kickoffs to set expectations and escalation paths.
- When assigning work, include the interaction points (e.g., "handoff to QA", "design review by UX, then dev implementation").
- Capture role-specific artifacts: UX prototypes, BA acceptance docs, release checklists, and QA test reports.

## Role Interaction Examples & Quick RACI (high-level)

Example: Shipping a minor feature
- Responsible: Developers, QA
- Accountable: Product Manager
- Consulted: UX Designer, Business Analyst
- Informed: Project Manager, Stakeholders

Use this document as the canonical reference for role definitions; maintain shorter, project-specific role assignments in the Project One-pager or backlog items.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
