# OctoAcme Project Management Guide

Welcome to OctoAcme! This guide provides new teammates with a high-level overview of how we approach project management, collaborate across teams, and deliver quality software.

## Our Project Management Philosophy

At OctoAcme, we follow these core principles:

- **Customer-first**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Deliver small, testable increments to get feedback early
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

## Project Lifecycle Stages

Every OctoAcme project follows a structured lifecycle to ensure quality and alignment:

### 1. Initiation
- Validate business need and define measurable outcomes
- Identify stakeholders and champions
- Create a Project One-pager (problem, goal, success metrics)
- Define initial timeline and key milestones
- Decide go/no-go for planning

**Key Deliverables**: Project One-pager, stakeholder list, high-level timeline, initial risk list

📖 [Learn more about Project Initiation](octoacme-project-initiation.md)

### 2. Planning
- Break work into shippable increments
- Create prioritized backlog with acceptance criteria
- Estimate scope and define Definition of Done
- Identify dependencies and integration points
- Create release plan and milestone map

**Key Deliverables**: Prioritized backlog, release timeline, Definition of Done, risk register

📖 [Learn more about Project Planning](octoacme-project-planning.md)

### 3. Execution & Tracking
- Daily standups to track progress and blockers
- Weekly delivery syncs and sprint/milestone demos
- Use project boards (GitHub Projects) to track workflow
- Small, focused Pull Requests with automated CI checks
- Continuous quality assurance and testing

**Key Deliverables**: Working software, test coverage, progress reports

📖 [Learn more about Execution & Tracking](octoacme-execution-and-tracking.md)

### 4. Release & Deployment
- Ensure all acceptance criteria are met
- Run security scans and smoke tests
- Deploy to staging first, then production
- Document rollback plans
- Announce release to stakeholders

**Key Deliverables**: Release notes, deployment checklist, smoke test results

📖 [Learn more about Release & Deployment](octoacme-release-and-deployment.md)

### 5. Retrospective & Continuous Improvement
- Capture learnings after each sprint, release, or milestone
- Identify what went well and what could be improved
- Create actionable improvement items with owners
- Measure impact of changes

**Key Deliverables**: Retrospective notes, prioritized action items

📖 [Learn more about Retrospectives](octoacme-retrospective-and-continuous-improvement.md)

## Roles & Responsibilities

### Project Manager (PM)
**Coordinates delivery activities and manages schedules, risks, and communications**

- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation
- Coordinate cross-team and stakeholder communication

### Product Manager (PdM)
**Defines what should be built to deliver customer and business value**

- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders on trade-offs
- Validate solutions through user research and metrics

### Developers
**Design, build, test, and deliver software components**

- Implement features to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Identify technical risks and propose mitigations

### QA/Testing
**Validate quality and acceptance criteria**

- Execute test plans and acceptance criteria
- Report and track defects
- Perform security and performance testing
- Collaborate on test automation

📖 [Learn more about Roles & Personas](octoacme-roles-and-personas.md)

## Communication & Collaboration

### Communication Cadence
- **Daily standups**: 15-minute team sync on progress, blockers, dependencies (or twice-weekly as agreed by the team)
- **Weekly PM + PdM sync**: Align on priorities, risks, and decisions
- **Sprint/milestone demos**: Show progress and gather feedback
- **Monthly stakeholder updates**: Share progress and key metrics
- **Ad-hoc escalations**: As needed for urgent issues

### Escalation Paths
When blockers or issues arise:
1. **Level 1**: Team-level triage in daily standup
2. **Level 2**: PM escalates to Product Lead and dependent teams
3. **Level 3**: Sponsor-level escalation for business-impacting issues

For security incidents, follow the security incident runbook and notify Security on-call immediately.

📖 [Learn more about Risk Management & Communication](octoacme-risks-and-communication.md)

## Quality Assurance Methods

We maintain high quality through multiple layers of validation:

### Continuous Integration (CI)
- Automated tests run on every Pull Request
- Linting and code quality checks
- Security scanning for vulnerabilities
- Build verification before merge

### Testing Strategy
- **Unit tests**: For new logic and functions
- **Integration tests**: For component interactions, API integrations, and cross-service dependencies
- **End-to-end smoke tests**: For critical user flows before release
- **Manual QA**: For feature acceptance when needed

### Quality Gates
- All PRs require at least one approval (or team-defined policy)
- Passing CI checks before merge
- Acceptance criteria must be met
- Security scans must pass

### Continuous Improvement
- Regular retrospectives to capture learnings
- Action items tracked with clear owners and due dates
- Measure impact of improvements
- Celebrate successes and iterate on processes

## Key Artifacts

Throughout the project lifecycle, we maintain these essential documents:

- **Project Charter / One-pager**: Problem, goal, success metrics
- **Roadmap and Release Plan**: Timelines and milestone map
- **Sprint/Iteration Backlog**: Prioritized work items
- **Acceptance Criteria & Definition of Done**: Quality standards
- **Risk Register**: Identified risks, impact, and mitigation plans
- **Retrospective notes**: Learnings and action items

## Getting Started

1. **New to a project?** Read the Project One-pager in the project repository
2. **Want to understand a specific phase?** Check the detailed guides linked above
3. **Need to know who does what?** Review the [Roles & Personas](octoacme-roles-and-personas.md) document
4. **Questions about process?** Reach out to your PM or Product Lead

## Additional Resources

For a comprehensive overview of all our processes, see:
- [Project Management Overview](octoacme-project-management-overview.md)

---

**Remember**: These processes are designed to help us deliver quality software efficiently. They should be adapted to fit the needs of each project while maintaining our core principles of customer focus, iterative delivery, and continuous improvement.
