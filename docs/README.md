# OctoAcme Project Management Docs

This README provides a summary of OctoAcme's project management processes and quick links to all supporting documentation in this folder. Use this as your entry point to understand our methodology and navigate to specific workflows and best practices.

---

## Overview of Project Management Processes

OctoAcme follows a structured, iterative project management framework centered on **customer value**, **frequent delivery**, and **clear accountability**. Our approach balances flexibility with rigor, ensuring teams can execute efficiently while maintaining visibility and quality.

### Project Lifecycle

Our projects move through five key phases:

1. **Initiation**: New ideas are validated through a lightweight Project One-pager that captures the business problem, success metrics, stakeholder alignment, and resource needs. This phase culminates in a go/no-go decision before deeper planning begins.

2. **Planning**: Approved initiatives are broken into shippable increments with clear acceptance criteria, estimates, and prioritization. Teams define a release timeline, identify dependencies, establish a Definition of Done, and create a comprehensive risk register.

3. **Execution & Tracking**: Work progresses through a GitHub Projects board (Backlog → Ready → In Progress → In Review → QA → Done). Small pull requests (≤400 lines) are reviewed and tested in CI before merging. Daily standups surface blockers and dependencies; weekly syncs with leadership review progress against milestones.

4. **Release & Deployment**: Before shipping, teams verify all acceptance criteria are met, CI/security scans pass, staging tests succeed, and rollback plans are documented. Deployments follow a standardized checklist with post-deploy verification and stakeholder announcement.

5. **Retrospective & Continuous Improvement**: After each sprint or milestone, teams reflect on what went well, identify improvements, and assign 2–3 actionable items. This culture of learning ensures processes evolve based on evidence and team feedback.

### Core Roles & Accountability

Clear role definition prevents ambiguity and ensures ownership:

- **Product Manager (PdM)**: Owns the product vision, prioritizes the backlog based on customer value, and measures outcomes through success metrics. Validates solutions through user research and data.

- **Project Manager (PM)**: Coordinates delivery activities, manages schedules, risks, and cross-team dependencies. Facilitates key meetings, maintains project documentation, and ensures transparent status reporting.

- **Developers**: Implement features and fixes, write and maintain tests, participate in design and code reviews, and help identify technical risks. Responsible for quality and maintainability of delivered work.

- **QA/Testing**: Validate acceptance criteria, run manual testing when needed, and ensure quality gates are met before release.

- **Stakeholders**: Provide business context, prioritization input, approvals, and feedback throughout the project lifecycle.

### Communication & Risk Management

Communication is intentional and multi-layered to ensure alignment without overhead:

- **Weekly PM-PdM Sync**: Strategic alignment on priorities, risks, and decisions.
- **Twice-Weekly Standups**: Delivery team covers progress, blockers, and dependencies.
- **Monthly Stakeholder Updates**: Leadership and business stakeholders receive high-level status, key metrics, and upcoming milestones.
- **Risk Register**: Formal tracking of risks with impact, likelihood, mitigation plans, and owners. Escalation flows from team → PM → Product Lead → Sponsor.
- **Weekly Status Templates**: Consistent communication of progress, next steps, risks/blockers, and decisions needed.

### Quality & Continuous Improvement

Quality is embedded throughout the workflow:

- **Testing & CI**: Unit tests, integration tests, and end-to-end smoke tests validate functionality. Automated linting and security scanning run on every PR.
- **Code Review**: Minimum one approval required before merge; small PR sizes enable thorough review.
- **Metrics & Measurement**: Teams track velocity, burndown, and success metrics defined in the Project One-pager.
- **Retrospectives**: Structured reflection (45–75 minutes) to identify what worked, what didn't, and actionable improvements.
- **Iterative Refinement**: Action items are tracked and measured for impact, creating a culture of continuous learning.

---

## Process Docs Index

Each document below provides in-depth workflows, templates, checklists, and best practices for a specific phase or area:

| Document | Purpose |
|----------|---------|
| [Project Management Overview](./octoacme-project-management-overview.md) | High-level introduction to OctoAcme's project management approach, principles, roles, and key artifacts. Start here for orientation. |
| [Project Initiation Guide](./octoacme-project-initiation.md) | Steps to validate a new project idea, align stakeholders, and make a go/no-go decision. Includes Project One-pager template. |
| [Project Planning](./octoacme-project-planning.md) | Turning an approved initiative into an actionable plan: backlog creation, estimation, Definition of Done, risk management, and release planning. |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Day-to-day execution guidance: team rhythm, GitHub Projects workflow, PR practices, testing strategy, metrics, and blocker escalation. |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | Maintaining a risk register, identifying and mitigating risks, stakeholder communication templates, and escalation paths. |
| [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Pre-release requirements, deployment checklist, rollback playbook, and release notes template. Standardizes shipping to production. |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Running effective retrospectives, capturing learnings, tracking action items, and building a culture of continuous improvement. |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Detailed descriptions of key roles (PM, PdM, Developers, QA, Stakeholders), responsibilities, goals, and typical communication patterns. |

---

## How to Use These Docs

- **New to the team?** Start with [Project Management Overview](./octoacme-project-management-overview.md) to understand our principles and lifecycle, then review [Roles & Personas](./octoacme-roles-and-personas.md) to find your role.

- **Starting a new project?** Follow [Project Initiation Guide](./octoacme-project-initiation.md) → [Project Planning](./octoacme-project-planning.md) → [Execution & Tracking](./octoacme-execution-and-tracking.md).

- **Shipping a release?** Reference [Release & Deployment Guide](./octoacme-release-and-deployment.md) for the pre-flight checklist and deployment process.

- **Managing risk or communication?** Use [Risk Management & Communication](./octoacme-risks-and-communication.md) for templates and escalation guidance.

- **Wrapping up a milestone?** Turn to [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) to run an effective reflection session.

Each document includes templates, checklists, and examples to make the processes actionable. Keep project artifacts (One-pagers, risk registers, retrospective notes) in your project repository for easy reference and version control.

---

## Getting Help

- Questions about a specific phase? Check the relevant process doc.
- Need a template? Look for the template section in each document.
- Have suggestions for improving these processes? Create an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.