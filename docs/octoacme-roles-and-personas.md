# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Project Delivery Roles

These roles form the nucleus of any OctoAcme project team.

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Quality & Technical Expertise Roles

These roles ensure quality, technical excellence, and risk mitigation across projects.

### QA / Testing Lead

#### Role Summary
QA/Testing Lead owns the quality discipline, defining test strategy, acceptance criteria validation, and quality metrics. They ensure features meet standards before release.

#### Responsibilities
- Define test strategy and approach for each project
- Create and maintain test plans and acceptance criteria
- Coordinate manual and automated testing efforts
- Track quality metrics and test coverage
- Validate acceptance criteria before PR approval
- Coordinate security and performance testing in CI

#### Goals
- Ensure features meet quality standards
- Reduce defects reaching production
- Maintain high test coverage and confidence in releases

#### Typical Communication
- Planning sessions to refine acceptance criteria
- Testing progress in standups and status reports
- Quality reports and metrics dashboards
- Incident post-mortems and root cause analysis

---

### Technical Lead / Architect

#### Role Summary
Technical Lead makes architectural decisions, ensures code quality, and guides technical strategy. They work across teams to align on technical direction and handle complex design challenges.

#### Responsibilities
- Define technical architecture and design patterns
- Review and approve technical designs and major PRs
- Identify and mitigate technical risks and debt
- Guide technology choices and tool selection
- Mentor developers and support skill development
- Ensure scalability, performance, and maintainability

#### Goals
- Build reliable, maintainable systems
- Reduce technical debt and risk
- Establish clear technical standards and best practices

#### Typical Communication
- Architecture design reviews and RFCs
- Code review feedback and technical guidance
- Risk identification in planning and execution
- Knowledge sharing and team mentoring

---

### Security Lead

#### Role Summary
Security Lead ensures projects comply with security standards, identifies security risks, and manages incident response. They work cross-functionally to embed security into the development lifecycle.

#### Responsibilities
- Define security requirements and acceptance criteria
- Review designs for security implications
- Configure and monitor security scanning in CI/CD
- Manage incident response and post-mortems
- Track security metrics and compliance
- Provide security guidance and training to team

#### Goals
- Prevent security breaches and vulnerabilities
- Meet compliance requirements
- Build security awareness across the organization

#### Typical Communication
- Security design reviews
- CI/CD security scan results
- Incident response coordination
- Security training and awareness updates

---

## Governance & Operations Roles

These roles provide business oversight, data-driven decision-making, and operational efficiency.

### Stakeholder / Sponsor

#### Role Summary
Sponsors are senior stakeholders who approve project initiation, allocate resources, and ensure alignment with strategic priorities. They provide authority and business context for decision-making.

#### Responsibilities
- Approve project initiation and business case
- Allocate budget and resources
- Make go/no-go decisions at key gates
- Escalate business-level risks and blockers
- Provide strategic context and guidance
- Monitor project progress against business goals

#### Goals
- Ensure projects align with business strategy
- Maximize return on investment
- Reduce organizational risk
- Support successful project delivery through strategic alignment

#### Typical Communication
- Monthly executive updates and health checks
- Gate reviews and approval meetings
- Escalation notifications for high-impact risks
- Strategic guidance and context-setting

---

### Product Operations (ProdOps)

#### Role Summary
Product Operations supports product and project management with data infrastructure, metrics dashboards, and process tooling. They enable data-driven decision-making and operational efficiency.

#### Responsibilities
- Build and maintain metrics dashboards for success criteria
- Coordinate data collection and analytics
- Support project board and workflow tooling
- Provide reporting for project health and velocity
- Identify process improvements and automation opportunities
- Support retrospectives and continuous improvement initiatives

#### Goals
- Enable data-driven decision-making
- Reduce manual reporting and overhead
- Accelerate project execution through better tools and visibility
- Drive continuous process improvement

#### Typical Communication
- Weekly metrics and dashboards updates
- Project board and workflow support
- Data-driven insights for planning and retrospectives
- Process improvement recommendations and implementation

---

## How These Personas Are Used

### In Project Planning & Execution
- Use these persona definitions to identify who needs to be involved in each project phase
- Reference typical communication patterns to ensure proper stakeholder engagement
- Map responsibilities to team members and clarify decision-making authority
- Identify gaps in team composition early

### In Escalation & Risk Management
- Use roles to define clear escalation paths (e.g., Developer → Tech Lead → PM → Sponsor)
- Understand each role's authority for go/no-go decisions and risk acceptance
- Clarify who owns specific decisions (technical, business, quality, security)

### In Copilot Spaces
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance
- Ask Copilot Spaces for "Project Manager perspective" or "Technical Lead guidance" on specific scenarios
- Use personas to provide context-appropriate recommendations aligned with role responsibilities

### In Onboarding & Team Building
- Use these definitions to help new team members understand their role and how it connects to others
- Adapt persona definitions to your organization's structure and staffing models
- Reference goals and responsibilities to clarify expectations and success criteria

---

## Cross-Role Collaboration Patterns

### Planning Phase
- **Product Manager** defines what to build and success metrics
- **Project Manager** creates timeline and identifies dependencies
- **Technical Lead** assesses technical feasibility and risks
- **QA Lead** defines test strategy
- **Security Lead** identifies security requirements
- **Stakeholder/Sponsor** approves scope and resources
- **ProdOps** sets up metrics tracking

### Execution Phase
- **Developers** implement features
- **Technical Lead** reviews designs and guides technical decisions
- **QA Lead** coordinates testing and validates quality
- **Security Lead** monitors security scans and manages vulnerabilities
- **Project Manager** tracks progress and manages risks
- **ProdOps** provides visibility through dashboards and metrics

### Release Phase
- **QA Lead** verifies acceptance criteria and quality gates
- **Security Lead** confirms security scanning passed and compliance verified
- **Technical Lead** approves release readiness
- **Project Manager** coordinates deployment timing
- **Stakeholder/Sponsor** approves go/no-go decision
- **ProdOps** monitors deployment metrics and success indicators

### Retrospective & Improvement
- **Project Manager** facilitates the retrospective
- **ProdOps** provides data on velocity, quality, and outcomes
- **All roles** contribute learnings and identify improvements
- **Stakeholder/Sponsor** provides strategic feedback on business outcomes
