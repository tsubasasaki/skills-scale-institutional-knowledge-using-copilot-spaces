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

## UX Designer

### Role Summary
UX Designers create and validate user-facing experiences, ensuring the product is usable, accessible, and aligned with user needs. They translate requirements into wireframes, prototypes, and design specifications that guide development.

### Responsibilities
- Conduct user research, usability testing, and competitive analysis
- Create wireframes, mockups, and interactive prototypes
- Define interaction patterns, accessibility standards, and visual guidelines
- Collaborate with Product Managers to translate requirements into design specifications
- Participate in acceptance reviews to verify that implemented UI matches intended designs

### Goals
- Ensure end-users can accomplish their goals with minimal friction
- Maintain a consistent, accessible design language across the product
- Reduce rework by validating designs early with users and stakeholders

### Typical Communication
- Design reviews with Product Managers and Developers
- Usability test reports and design documentation
- Feedback on PRs where UI changes are introduced

### Interactions
- **Developers:** Provide annotated design specs and assets; review implemented UI against designs in QA and pre-release stages.
- **Product Managers:** Collaborate during Initiation and Planning to align designs with product vision and acceptance criteria.
- **Project Managers:** Flag design-scope changes that may affect timelines; participate in sprint planning.
- **QA Lead:** Share design specs so QA can include UI/UX acceptance criteria in test plans.
- **Lifecycle:** Active during Planning (design creation), Execution (spec handoff, dev support), and Release (UI acceptance sign-off).

---

## DevOps Engineer

### Role Summary
DevOps Engineers build, operate, and improve the infrastructure and pipelines that enable reliable, repeatable software delivery. They bridge development and operations, ensuring deployments are safe, fast, and observable.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and automation
- Manage cloud infrastructure, environment configuration, and secrets
- Monitor system health, define alerting, and lead incident response
- Enforce security scanning, dependency management, and compliance gates in pipelines
- Support Developers and QA with environment provisioning and debugging

### Goals
- Reduce lead time from code commit to production deployment
- Maximize system reliability and minimize incident impact
- Maintain infrastructure-as-code practices for reproducibility and auditability

### Typical Communication
- Release and deployment coordination with PM and Developers
- Incident retrospectives and post-mortems
- Infrastructure change requests and runbooks

### Interactions
- **Developers:** Collaborate on pipeline configuration, local development environments, and build tooling.
- **Product Managers:** Communicate infrastructure constraints and capacity limitations that may affect roadmap planning.
- **Project Managers:** Provide deployment readiness status; flag infrastructure risks in the risk register.
- **QA Lead:** Provision test environments; integrate automated test execution into CI/CD pipelines.
- **Lifecycle:** Active from Planning (infrastructure design) through Execution (pipeline operation) and Release (deployment execution, post-deploy verification) and Retrospective (incident learnings).

---

## QA Lead

### Role Summary
The QA Lead (Quality Assurance Lead) defines and owns the team's testing strategy, ensuring software meets quality standards and acceptance criteria before release. They coordinate manual and automated testing and serve as the release quality gate.

### Responsibilities
- Define and maintain the testing strategy, including scope, approach, and tooling
- Write, review, and maintain automated and manual test plans
- Coordinate testing efforts across sprints and validate acceptance criteria
- Identify, document, and track defects through resolution
- Assess release readiness and provide a quality sign-off before production deployment

### Goals
- Prevent defects from reaching production by detecting them early
- Shorten feedback loops through fast, reliable automated test coverage
- Ensure acceptance criteria are testable and consistently validated

### Typical Communication
- Bug and defect reports shared with Developers and Project Managers
- Test coverage summaries before release reviews
- Participation in sprint planning to identify testability risks

### Interactions
- **Developers:** Review acceptance criteria for testability during Planning; collaborate on test automation and defect triage during Execution.
- **Product Managers:** Confirm that acceptance criteria are clearly defined and measurable; verify that shipped features meet the intended outcome.
- **Project Managers:** Report testing status and blockers; surface risks that may affect release timelines.
- **DevOps Engineer:** Coordinate environment availability and integrate test suites into CI/CD pipelines.
- **Lifecycle:** Active from Planning (test strategy, DoR/DoD review) through Execution (continuous testing) and Release (quality sign-off).

---

## Business Analyst

### Role Summary
Business Analysts bridge business needs and technical solutions. They elicit, document, and validate requirements, ensuring that what gets built solves the right problem in the right way.

### Responsibilities
- Facilitate requirements workshops and stakeholder interviews
- Document functional and non-functional requirements, user stories, and acceptance criteria
- Map current-state and future-state workflows; identify gaps and risks
- Validate that delivered solutions meet business requirements before release
- Maintain traceability between business goals and technical deliverables

### Goals
- Ensure technical teams have clear, unambiguous requirements before development begins
- Reduce scope creep and rework by aligning stakeholders early
- Bridge communication gaps between business stakeholders and engineering teams

### Typical Communication
- Requirements documents, user story maps, and process diagrams
- Structured walkthroughs and sign-off sessions with stakeholders and Product Managers
- Participation in sprint reviews to validate delivered functionality

### Interactions
- **Developers:** Clarify requirements and acceptance criteria during development; review implemented features against documented requirements.
- **Product Managers:** Co-own the backlog refinement process; align requirements with product strategy and prioritization.
- **Project Managers:** Surface requirements-related risks and dependencies; flag when scope changes may affect timelines.
- **Stakeholders:** Primary liaison for eliciting and validating business needs and sign-off.
- **Lifecycle:** Active during Initiation (requirements gathering), Planning (backlog refinement, acceptance criteria), Execution (clarification, validation), and Release (business acceptance testing).

---

## Stakeholder

### Role Summary
Stakeholders represent user, business, or customer interests in the project. They provide input on priorities, review key deliverables, approve requirements and releases, and participate in escalation and decision-making when needed. This role spans individuals from executive sponsors to end-user representatives.

### Responsibilities
- Provide clear, timely input on business goals, constraints, and priorities
- Review and approve key artifacts (requirements, designs, release plans)
- Participate in demos and milestone reviews to assess progress against expectations
- Escalate and make decisions when trade-offs exceed the team's authority
- Communicate organizational or market changes that may affect the project

### Goals
- Ensure the project delivers measurable business value aligned with organizational goals
- Maintain confidence in delivery through regular, meaningful progress updates
- Enable the team to move forward by providing timely decisions and approvals

### Typical Communication
- Monthly (or milestone-based) stakeholder updates from the Project Manager
- Demo invitations at end-of-sprint or milestone completion
- Ad-hoc escalation calls for significant scope, timeline, or budget decisions

### Interactions
- **Developers:** Minimal direct interaction; occasionally invited to demos or for domain-expert input.
- **Product Managers:** Regular engagement to align on roadmap, trade-offs, and success metrics.
- **Project Managers:** Primary communication channel for status, risks, and escalations.
- **Business Analyst:** Key partner for requirements elicitation, validation, and sign-off.
- **Lifecycle:** Engaged at Initiation (problem framing, charter approval), Planning (priority alignment), Execution (periodic demos), Release (go/no-go decision), and Retrospective (outcome review).

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

## Related Docs
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Role Handoff Checklist](octoacme-role-handoff-checklist.md)
- [Definition of Ready / Definition of Done](octoacme-definition-of-ready-done.md)

