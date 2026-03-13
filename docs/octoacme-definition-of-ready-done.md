# OctoAcme — Definition of Ready and Definition of Done

## Purpose
Provide shared, explicit quality gates that all roles can reference to determine when work is ready to start and when it is genuinely complete. These definitions reduce ambiguity, prevent rework, and establish a common language across Developers, QA, Product Managers, and Project Managers.

---

## Definition of Ready (DoR)

A backlog item meets the Definition of Ready when all of the following are true **before** it enters a sprint or iteration.

### Product / Requirements
- [ ] User story or task is written in a clear format (e.g., "As a [role], I want [goal] so that [reason]")
- [ ] Acceptance criteria are defined, testable, and agreed upon by the Product Manager and QA Lead
- [ ] Business Analyst (if applicable) has reviewed requirements and confirmed alignment with business goals
- [ ] Dependencies on other teams or systems are identified and unblocked (or risk is accepted)

### Design
- [ ] UX designs or wireframes are available and approved (for user-facing work)
- [ ] Edge cases and error states are covered in designs or specs

### Technical
- [ ] Technical approach is understood and any spikes or research have been completed
- [ ] Estimate (relative or time-based) has been provided by the team
- [ ] Test environment is available or confirmed to be ready before work starts

### Stakeholder
- [ ] Stakeholder or Product Manager sign-off on scope has been obtained for high-impact items
- [ ] No unresolved blocking questions or open decisions on this item

---

## Definition of Done (DoD)

A backlog item meets the Definition of Done when all of the following are true **before** it is marked complete and potentially shippable.

### Development
- [ ] Code is implemented and meets all acceptance criteria
- [ ] Code is peer-reviewed and all review comments are resolved
- [ ] Unit and integration tests are written and passing in CI
- [ ] No regressions introduced (existing tests still pass)

### Quality Assurance
- [ ] QA Lead has verified all acceptance criteria (manual or automated)
- [ ] No open P1 or P2 defects; any accepted lower-priority issues are documented
- [ ] UI implementation reviewed against UX design specs (if applicable)

### Documentation & Compliance
- [ ] Relevant documentation (inline, README, process docs) is updated
- [ ] Security scanning and dependency checks pass in CI
- [ ] Release notes updated (or flagged as internal/non-user-facing)

### Operations
- [ ] DevOps Engineer confirms deployment steps are documented or automated
- [ ] Feature flags, environment config, or migration steps are prepared if needed
- [ ] Monitoring and alerting updated to cover new functionality (if applicable)

### Closure
- [ ] Issue or ticket is updated to reflect completion and linked to the merged PR
- [ ] Product Manager or designated reviewer has accepted the work
- [ ] Item is moved to "Done" on the project board

---

## RACI-Lite: Who Owns Each Gate

| Gate | Responsible | Accountable | Consulted | Informed |
|---|---|---|---|---|
| Definition of Ready | Business Analyst / Dev | Product Manager | QA Lead, UX Designer | Project Manager |
| Definition of Done — Code | Developer | Tech Lead / Dev | QA Lead | Project Manager |
| Definition of Done — QA | QA Lead | Product Manager | Developer, DevOps Eng | Project Manager |
| Definition of Done — Release | DevOps Engineer | Project Manager | QA Lead, Product Manager | Stakeholders |

> **Key:** R = Responsible (does the work), A = Accountable (final decision), C = Consulted (input needed), I = Informed (notified of outcome)

---

## Related Docs
- [Roles & Personas](octoacme-roles-and-personas.md)
- [Role Handoff Checklist](octoacme-role-handoff-checklist.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
