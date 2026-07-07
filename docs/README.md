# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management Documentation. This folder contains the core processes, workflows, and guidance that power how we run projects at OctoAcme.

## Overview

OctoAcme follows a structured, iterative approach to project delivery that emphasizes:
- **Customer-first decision making** — Prioritize customer value and usability in all decisions
- **Clear ownership and accountability** — Each project has a named Project Manager and Product Lead
- **Data-informed iterations** — Measure impact and iterate based on evidence
- **Psychological safety and continuous improvement** — Encourage feedback and learning through retrospectives
- **Cross-functional collaboration** — Enable effective teamwork across developers, product, and stakeholders

## Project Management Approach

OctoAcme delivers projects through five key lifecycle phases, supported by cross-cutting processes for risk management, communication, and continuous improvement:

**Phase 1: Initiation** validates the business need and aligns stakeholders on the problem statement, success metrics, and high-level timeline. A lightweight Project One-pager serves as the decision gate—if success metrics are clear, stakeholders agree on priority, and team availability is confirmed, the project advances to planning.

**Phase 2: Planning** transforms approved initiatives into actionable backlogs by breaking work into shippable increments, estimating scope using T-shirt sizing or story points, defining acceptance criteria and Definition of Done, and creating a release plan with key milestones. This disciplined front-end planning ensures clarity and alignment before development begins.

**Phase 3: Execution** is driven by a consistent team rhythm centered on transparency and incremental progress. Daily standups (15 minutes) focus on blockers and dependencies, while weekly delivery syncs track progress and flag risks. The team uses GitHub Projects with standardized columns to visualize workflow. Pull requests are kept small (≤400 lines when possible), require automated testing and linting before review, and need at least one approval before merging. Quality is embedded throughout: unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release, and security scanning in CI.

**Phase 4: Release & Deployment** standardizes how features move to production to reduce risk and improve observability. All acceptance criteria must be met, CI and security scans must pass, release notes must be drafted, and a rollback plan documented. Post-deployment verification and stakeholder announcements ensure successful launches and rapid issue detection.

**Phase 5: Retrospective & Continuous Improvement** closes the loop on delivery excellence by capturing what went well, what could improve, and identifying actionable improvements with clear owners and due dates. These learnings feed back into the planning process, ensuring systematic refinement of processes over time.

**Cross-cutting processes** for risk management and communication operate throughout the entire lifecycle. Teams maintain an active Risk Register reviewed at weekly syncs, following clear escalation paths (team-level → PM → Product Lead → Sponsor) to ensure blockers don't linger unaddressed.

## Core Roles

- **Project Manager (PM)** — Coordinates delivery, manages schedules, risks, and communications. Enables the team to deliver on commitments efficiently.
- **Product Manager (PdM)** — Defines outcomes, prioritizes the backlog, and measures success. Owns the product vision and validates solutions.
- **Developers** — Implement features, collaborate on design, write and maintain tests. Deliver reliable, maintainable code.
- **QA/Testing** — Validate quality and acceptance criteria. Ensure features meet standards before release.
- **Stakeholders** — Provide inputs, approvals, and business context. Receive regular updates and participate in key decisions.

## Process Documentation

Our project lifecycle and supporting processes are organized as follows:

### Project Lifecycle

1. **[Project Initiation Guide](./octoacme-project-initiation.md)** — Validate the business need, align stakeholders, and make the go/no-go decision to move into planning.
   - Confirm business need and measurable outcome
   - Identify stakeholders & champions
   - Create a lightweight Project One-pager
   - Decide go/no-go for planning

2. **[Project Planning](./octoacme-project-planning.md)** — Break approved work into actionable backlog items, estimate scope, identify dependencies, and create a release plan.
   - Conduct project kickoff meeting
   - Create prioritized backlog with acceptance criteria
   - Estimate scope and define Definition of Done
   - Identify dependencies and integration points
   - Create release plan and milestone map

3. **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Day-to-day delivery activities including standups, PR workflows, testing, and progress tracking.
   - Maintain consistent team rhythm (daily standups, weekly syncs)
   - Use GitHub Projects for workflow visualization
   - Execute PR workflow with automated testing and reviews
   - Implement quality practices (unit tests, integration tests, security scanning)
   - Track velocity, burndown, and success metrics

4. **[Release & Deployment](./octoacme-release-and-deployment.md)** — Standardized process for releasing features to production safely and verifying their impact.
   - Define release types (patch, minor, major)
   - Complete pre-release requirements and smoke tests
   - Execute deployment checklist and post-deploy verification
   - Document rollback and incident playbooks
   - Announce releases to stakeholders

5. **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements.
   - Run structured retrospectives after sprints, releases, and milestones
   - Identify what went well and what could improve
   - Create action items with clear owners and timelines
   - Track improvements and celebrate incremental changes

### Cross-Cutting Processes

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identify, assess, and monitor risks; maintain stakeholder alignment throughout the project.
  - Maintain Risk Register with ID, description, impact, likelihood, owner, mitigation, status
  - Follow risk lifecycle: Identify → Assess → Mitigate → Monitor
  - Communicate regularly with stakeholders via weekly status updates
  - Escalate issues through clear escalation paths

- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to core roles, key artifacts, and communication cadence.
  - Understand core principles and roles
  - Review key artifacts (Charter, Roadmap, Backlog, Risk Register)
  - Follow communication cadence (weekly PM/PdM syncs, twice-weekly standups, monthly stakeholder updates)

- **[Roles and Personas](./octoacme-roles-and-personas.md)** — Definitions of Project Managers, Product Managers, Developers, and other key roles and their responsibilities.
  - Review typical responsibilities for each role
  - Understand goals and communication patterns
  - Apply persona definitions to project scenarios

## Quick Reference Guide

**Starting a new project?**  
Begin with the [Project Initiation Guide](./octoacme-project-initiation.md) to validate the business need and create your Project One-pager.

**Need to understand roles?**  
See [Roles and Personas](./octoacme-roles-and-personas.md) for definitions of responsibilities and communication patterns.

**Managing an active project?**  
Reference [Project Planning](./octoacme-project-planning.md) for backlog and milestone creation, and [Execution & Tracking](./octoacme-execution-and-tracking.md) for day-to-day workflows.

**Identifying and managing risks?**  
Use [Risk Management & Communication](./octoacme-risks-and-communication.md) to maintain your Risk Register and escalation paths.

**Getting ready to ship?**  
Review [Release & Deployment](./octoacme-release-and-deployment.md) for pre-release requirements, deployment checklists, and rollback playbooks.

**Improving processes?**  
See [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) to capture learnings and drive action items.

**Need a high-level overview?**  
Visit [Project Management Overview](./octoacme-project-management-overview.md) for core principles, artifacts, and communication cadence.

## How to Use This Documentation

- **New team members:** Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand our approach, then reference specific documents as you work on projects.
- **Project Managers:** Keep the Project One-pager and Risk Register updated in your project repo. Refer to the [Project Planning](./octoacme-project-planning.md) and [Risk Management & Communication](./octoacme-risks-and-communication.md) documents regularly.
- **Product Managers:** Use [Project Initiation Guide](./octoacme-project-initiation.md) to validate new initiatives and [Project Planning](./octoacme-project-planning.md) to create prioritized backlogs.
- **Developers:** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) for PR workflows and quality practices, and [Release & Deployment](./octoacme-release-and-deployment.md) before shipping.
- **All team members:** Participate actively in retrospectives ([Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)) to drive continuous improvement.

## Keeping Documentation Current

As processes evolve and new best practices emerge, update these documents to reflect the team's learnings. Use the [Process Doc Update](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose additions or changes. This ensures our documentation remains a living resource that grows with the team.

---

**Last updated:** 2026-07-07  
**Owner:** OctoAcme Project Management Team
