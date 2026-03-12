# OctoAcme — Role Handoff Checklist

## Purpose
Ensure smooth, explicit handoffs between roles at each lifecycle stage. Use this checklist when work is transitioning between teams or personas to reduce dropped context and missed dependencies.

---

## How to use
1. The **outgoing** role completes their section of the checklist before handoff.
2. The **incoming** role reviews and confirms receipt before taking ownership.
3. The Project Manager tracks that each handoff is completed and unblocked.

---

## Initiation → Planning Handoff

**From: Product Manager / Business Analyst → Project Manager + Team**

- [ ] Problem statement is documented and approved by Stakeholders
- [ ] Success metrics and acceptance criteria are defined (SMART)
- [ ] Initial stakeholder list is confirmed with communication preferences noted
- [ ] High-level scope and any known constraints are documented
- [ ] Project one-pager / charter is reviewed and sign-off recorded

---

## Planning → Execution Handoff

**From: Project Manager + Product Manager → Developers + QA Lead + UX Designer**

- [ ] Backlog items are refined, prioritized, and meet the Definition of Ready (see [DoR/DoD](octoacme-definition-of-ready-done.md))
- [ ] Acceptance criteria are written for all items in the first sprint/milestone
- [ ] Design specs and assets are available for items entering development
- [ ] Test plan and testing environments are confirmed with QA Lead and DevOps Engineer
- [ ] Dependencies and risks are documented in the risk register
- [ ] Milestone schedule and sprint cadence are communicated to the team

---

## Execution → QA Handoff

**From: Developers → QA Lead**

- [ ] Feature branch is merged to the integration branch and CI is passing
- [ ] Acceptance criteria checklist is completed by the Developer
- [ ] PR description links to the relevant issue and includes testing notes
- [ ] Known edge cases or limitations are documented in the PR or ticket
- [ ] Design specs reviewed (UX Designer confirms implementation if UI changes)
- [ ] Smoke test instructions provided where automated coverage is incomplete

---

## QA → Release Handoff

**From: QA Lead → DevOps Engineer + Project Manager**

- [ ] All acceptance criteria are verified and documented (pass/fail per criterion)
- [ ] No open P1 or P2 defects; any known issues are listed with mitigations
- [ ] Test coverage summary shared with Project Manager and Product Manager
- [ ] Release notes reviewed for accuracy by QA and Product Manager
- [ ] Staging smoke test results documented
- [ ] QA sign-off recorded (date, tester, scope)

---

## Release → Post-Release Handoff

**From: DevOps Engineer → Project Manager + Product Manager + Support**

- [ ] Deployment to production is complete and verified
- [ ] Post-deploy verification checks passed
- [ ] Monitoring and alerting are active for the new release
- [ ] Release announcement sent to stakeholders
- [ ] Rollback plan confirmed (ready to execute if needed)
- [ ] Retrospective scheduled (see [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md))

---

## Related Docs
- [Roles & Personas](octoacme-roles-and-personas.md)
- [Definition of Ready / Definition of Done](octoacme-definition-of-ready-done.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Risks & Communication](octoacme-risks-and-communication.md)
