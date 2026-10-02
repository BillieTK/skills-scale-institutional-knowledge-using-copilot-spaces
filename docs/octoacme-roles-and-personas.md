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

## Stakeholder / Sponsor

### Role Summary
Stakeholders and sponsors represent the business or customer interest in a project. They sponsor the investment, confirm strategic alignment, and help unblock decisions that affect scope, priority, or funding.

### Responsibilities
- Approve project goals, funding, and scope direction
- Provide business context, constraints, and priorities
- Review progress against strategic outcomes and success metrics
- Make decisions on trade-offs, escalations, and major dependencies
- Support risk mitigation when business impact is high

### Goals
- Ensure the project delivers measurable business value
- Maintain alignment between project work and organizational strategy
- Support timely, informed decisions across the project lifecycle

### Interaction with Other Roles
- **Project Manager**: Reviews milestones, decisions, and stakeholder communications
- **Product Manager**: Aligns outcomes, priorities, and market/customer impact
- **Developers**: Provides direction on business constraints and acceptance expectations
- **Security / Release roles**: Reviews risk, compliance, and launch readiness where business impact is material

### Typical Communication
- Executive updates and milestone reviews
- Approvals for scope, budget, and deployment timing
- Escalation points for risks, blockers, or business-impacting issues

---

## QA / Testing Lead

### Role Summary
The QA or Testing Lead owns quality strategy and validation across the delivery lifecycle. They define the testing approach, monitor quality gates, and help ensure releases meet agreed acceptance criteria and reliability standards.

### Responsibilities
- Define test strategy, coverage requirements, and quality gates
- Review requirements and acceptance criteria for testability
- Coordinate manual and automated test execution
- Track defects, regression risk, and quality trends
- Partner with developers and PMs on release readiness

### Goals
- Detect defects early and reduce production risk
- Improve confidence in product quality and release readiness
- Balance speed of delivery with predictable quality outcomes

### Interaction with Other Roles
- **Developers**: Reviews testability, defects, and fix validation
- **Project Manager**: Aligns QA timelines, release readiness, and risk visibility
- **Product Manager**: Confirms acceptance criteria and customer-critical scenarios
- **Release Manager**: Validates smoke tests and deployment readiness

### Typical Communication
- Test planning and quality reviews
- Regression triage and defect prioritization
- Release-readiness check-ins and signoff discussions

---

## Technical Lead / Architect

### Role Summary
The Technical Lead or Architect helps shape the technical direction of the project. They guide system design, support implementation decisions, and ensure the solution remains maintainable, scalable, and aligned with engineering standards.

### Responsibilities
- Define and review architecture, technical standards, and design trade-offs
- Identify technical dependencies, risks, and integration points
- Mentor developers and review technical decisions for quality and consistency
- Guide refactoring, scalability, and maintainability work
- Coordinate technical alignment across teams or systems

### Goals
- Keep the solution technically sound and sustainable
- Reduce rework caused by design drift or unclear technical direction
- Support delivery without sacrificing maintainability or security

### Interaction with Other Roles
- **Developers**: Provides architecture guidance, review feedback, and design decisions
- **Project Manager**: Aligns technical dependencies, sequencing, and risk management
- **Product Manager**: Helps translate roadmap intent into feasible technical approaches
- **Security Lead**: Reviews security implications of design decisions

### Typical Communication
- Design reviews and architecture discussions
- Technical dependency updates and risk assessments
- Architecture decision records and implementation guidance

---

## Release Manager

### Role Summary
Release Managers coordinate and orchestrate product releases across environments. They reduce deployment risk by managing release readiness, communication, and rollback planning.

### Responsibilities
- Coordinate release schedule and deployment windows with stakeholders and operations teams
- Confirm pre-release requirements are met, including CI, QA, and security checks
- Manage communication to support, stakeholders, and end users
- Orchestrate deployment sequencing and verification steps
- Maintain rollback, incident, and post-release follow-up plans

### Goals
- Minimize deployment risk and unplanned downtime
- Improve release predictability and operational readiness
- Support fast, controlled recovery when issues arise

### Interaction with Other Roles
- **Project Manager**: Aligns on release timing, checkpoints, and stakeholder updates
- **QA / Testing Lead**: Confirms smoke tests and quality signoff before production release
- **Developers**: Coordinates hotfix or rollback actions during release issues
- **Product Manager**: Confirms release notes and business-facing impact communication
- **Security Lead**: Confirms security checks are complete before deployment

### Typical Communication
- Release planning and readiness reviews
- Deployment window coordination and post-release verification updates
- Incident response and rollback communication

---

## Security Lead

### Role Summary
The Security Lead embeds security practices into the project lifecycle. They help teams identify and reduce risk early, validate compliance needs, and support rapid response when security issues arise.

### Responsibilities
- Identify security requirements during initiation and planning
- Review technical designs, dependencies, and exposure risks
- Define security testing, scanning, and validation standards
- Support incident response for security or privacy-related issues
- Help developers understand secure practices and remediation priorities

### Goals
- Reduce security vulnerabilities and compliance risk
- Integrate security into delivery without slowing the team unnecessarily
- Maintain trust in the product and customer data handling

### Interaction with Other Roles
- **Developers**: Reviews secure coding practices and vulnerability fixes
- **Project Manager**: Escalates risk and tracks mitigation responsibilities
- **QA / Testing Lead**: Aligns testing scope for security coverage and validation
- **Release Manager**: Confirms security checks and exception approvals before deployment
- **Technical Lead**: Reviews secure architecture choices and threat surfaces

### Typical Communication
- Security reviews, threat checks, and architecture feedback
- Weekly risk discussions and incident coordination
- Security checkpoint updates during release and deployment windows

---

## Agile Coach / Scrum Master

### Role Summary
The Agile Coach or Scrum Master improves team effectiveness and process health. They help teams work with clarity, improve collaboration, and remove impediments that slow delivery.

### Responsibilities
- Facilitate team rituals such as standups, sprint planning, and retrospectives
- Remove blockers and improve workflow efficiency
- Help teams apply the agreed process consistently and effectively
- Support continuous improvement and team learning
- Coach the team on communication, decision-making, and delivery practices

### Goals
- Improve team flow, accountability, and adaptability
- Reduce friction caused by unclear process or unresolved blockers
- Support sustainable, high-performing delivery practices

### Interaction with Other Roles
- **Project Manager**: Aligns on delivery cadence, meeting flow, and risk visibility
- **Product Manager**: Helps prioritize and clarify backlog conversations
- **Developers**: Supports collaboration, facilitation, and continuous improvement practices
- **Stakeholders**: Helps communicate progress and process issues when needed

### Typical Communication
- Team facilitation and retrospectives
- Delivery health discussions and blocker tracking
- Process improvement recommendations and coaching sessions

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

