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

## Project Sponsors

### Role Summary
Project Sponsors provide high-level executive support and ensure the project aligns with strategic business goals. They have final approval authority and help remove organizational roadblocks.

### Responsibilities
- Provide funding and resource authorization
- Ensure project alignment with business strategy
- Remove high-level organizational barriers
- Give final approval on major deliverables and scope changes
- Champion the project at the executive level

### Goals
- Maximize return on investment
- Ensure strategic alignment with organizational priorities
- Enable project success through resource allocation and support

### Typical Communication
- Monthly steering committee meetings
- Executive briefings on major milestones and risks
- Sign-off on business cases and major change requests

---

## Quality Assurance Leads

### Role Summary
Quality Assurance Leads drive process and product quality across the project lifecycle. They plan and oversee testing strategies and serve as the quality advocate between development teams and stakeholders.

### Responsibilities
- Define and implement testing strategies and quality standards
- Plan and coordinate test activities across project phases
- Review test coverage and quality metrics
- Identify quality risks and recommend mitigations
- Ensure defects are properly tracked and resolved

### Goals
- Deliver high-quality, defect-free releases
- Prevent quality issues through early detection
- Maintain comprehensive test coverage

### Typical Communication
- Test plans and quality reports
- Daily collaboration with developers on defects
- Weekly quality metrics reviews with Project Managers
- Release readiness assessments

---

## Change Managers

### Role Summary
Change Managers coordinate and approve major changes to project scope, schedule, or deliverables. They ensure changes are properly evaluated, communicated, and aligned with stakeholder expectations.

### Responsibilities
- Evaluate change requests for impact and feasibility
- Facilitate change control board meetings
- Ensure change documentation and traceability
- Communicate approved changes to all stakeholders
- Track change implementation and closure

### Goals
- Minimize uncontrolled scope creep
- Ensure changes are properly vetted and approved
- Maintain alignment between deliverables and expectations

### Typical Communication
- Change request documentation and impact assessments
- Change control board meeting facilitation
- Change approval notifications and updates

---

## Business Analysts

### Role Summary
Business Analysts gather and clarify requirements from business stakeholders and translate them into specifications that technical teams can implement. They bridge the gap between business needs and technical solutions.

### Responsibilities
- Elicit and document business requirements
- Analyze business processes and identify improvement opportunities
- Create detailed functional specifications
- Validate that delivered solutions meet business needs
- Facilitate requirements workshops and reviews

### Goals
- Ensure clear, actionable requirements
- Minimize rework due to misunderstood requirements
- Optimize business value delivery

### Typical Communication
- Requirements documents and user stories
- Stakeholder interviews and workshops
- Clarification sessions with development teams
- Acceptance criteria reviews

---

## Release Managers

### Role Summary
Release Managers own the release process and coordinate deployment activities across all functions. They manage cutover events and ensure smooth transitions from development to production.

### Responsibilities
- Create and maintain release schedules and plans
- Coordinate release activities across teams
- Manage deployment procedures and runbooks
- Oversee production cutover and rollback procedures
- Communicate release status to stakeholders

### Goals
- Achieve zero-downtime deployments
- Minimize release-related incidents
- Ensure predictable, repeatable release processes

### Typical Communication
- Release plans and deployment schedules
- Go/no-go decision meetings
- Post-release reports and metrics
- Coordination with QA, Developers, and Operations

---

## Process Improvement Champions

### Role Summary
Process Improvement Champions identify process bottlenecks, coordinate retrospectives, and ensure continuous improvement initiatives are documented and tracked. They drive operational excellence across the project.

### Responsibilities
- Facilitate retrospectives and lessons learned sessions
- Identify and document process inefficiencies
- Propose and track process improvement initiatives
- Measure effectiveness of process changes
- Share best practices across teams

### Goals
- Continuously improve team efficiency and effectiveness
- Reduce waste and eliminate bottlenecks
- Foster a culture of continuous learning

### Typical Communication
- Retrospective facilitation and action items
- Process improvement proposals
- Metrics dashboards showing efficiency trends
- Knowledge sharing sessions

---

## Role Interactions and Collaboration

The personas described above work together in an interconnected ecosystem. Understanding these relationships is critical for effective project delivery:

### Strategic Level
- **Project Sponsors** work closely with **Project Managers** to set direction, approve major decisions, and remove organizational barriers
- **Business Analysts** translate business needs from stakeholders into requirements that inform the **Product Managers**' roadmap priorities

### Planning and Requirements
- **Business Analysts** collaborate with **Product Managers** and **Developers** to ensure requirements are clear and technically feasible
- **Change Managers** partner with **Project Managers** to evaluate scope changes and their impact on timelines and resources

### Delivery and Quality
- **Quality Assurance Leads** work with **Developers** on test strategies and defect resolution, and coordinate with **Release Managers** on quality gates
- **Release Managers** coordinate with **QA Leads**, **Developers**, and **Project Managers** to plan and execute deployments
- **Developers** implement features guided by **Business Analysts**' specifications and **Product Managers**' priorities

### Continuous Improvement
- **Process Improvement Champions** engage all roles to identify opportunities, with particular focus on **Project Managers** for process optimization
- **Project Managers** incorporate feedback from **Process Improvement Champions** into team workflows

### Example Scenario: Feature Release Handoff

**Context**: A new customer-facing feature is ready for production release.

1. **Business Analyst** confirms final requirements with stakeholders and validates acceptance criteria with **Product Manager**
2. **Developers** complete implementation and notify **QA Lead** that code is ready for testing
3. **QA Lead** executes test plan, reports results to **Project Manager**, and gives quality sign-off
4. **Release Manager** coordinates with **QA Lead** and **Developers** to schedule deployment window
5. **Change Manager** reviews the deployment plan, assesses risk, and approves the release
6. **Project Manager** communicates readiness to **Project Sponsor** and obtains final business approval
7. **Release Manager** executes deployment, monitors production, and confirms success
8. **Process Improvement Champion** facilitates post-release retrospective to capture lessons learned

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

