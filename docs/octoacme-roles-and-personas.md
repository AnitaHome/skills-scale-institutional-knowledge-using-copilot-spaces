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

---

## QA / Testing

### Role Summary
QA Engineers validate that features and fixes meet acceptance criteria and quality standards before release. They own the test strategy, test cases, and sign-off on release readiness.

### Responsibilities
- Design and execute test plans and acceptance tests
- Identify, document, and track defects
- Collaborate with Developers on testability and test data
- Confirm the Definition of Done is met before promoting to release
- Participate in release readiness sign-off

### Goals
- Prevent regressions and defects reaching production
- Enable fast feedback loops for Developers
- Maintain a reliable, up-to-date regression suite

### Typical Communication / Interaction
- Sprint ceremonies and backlog refinement with Developers and PM
- Test summary reports to Project Manager and Product Manager
- Escalates blocking defects to Project Manager and Product Manager
- Hands off release readiness confirmation to Release Manager

---

## UX Designer

### Role Summary
UX Designers are responsible for user research, wireframes, user flows, usability testing, and ensuring accessible, user-centric design. They bridge customer needs and technical implementation.

### Responsibilities
- Conduct user research and synthesize insights into design requirements
- Create wireframes, prototypes, and user flows
- Define and document UX acceptance criteria in backlog items
- Facilitate usability testing and share findings with Product Manager
- Maintain a design system or component library as applicable
- Participate in backlog refinement to clarify design intent for Developers

### Goals
- Deliver clear, tested designs that reduce rework during development
- Ensure accessibility and usability standards are met
- Reduce ambiguity between product intent and implementation

### Typical Communication / Interaction
- **→ Product Manager:** receives prioritized problem statements; delivers research insights and design options for approval; escalates scope changes that affect UX scope.
- **→ Developers:** hands off finalized wireframes and annotated specs; available during implementation for clarification; reviews implemented UI before QA handoff.
- **→ QA:** provides UX acceptance criteria so testers can validate visual and interaction quality.
- **→ Project Manager:** flags design-blocking dependencies and timeline risks; confirms design sign-off in the [role-responsibility-matrix.md](role-responsibility-matrix.md).

---

## Technical Writer

### Role Summary
Technical Writers ensure that documentation — user guides, release notes, API references, onboarding materials — is clear, accurate, and published on time. They own the documentation artifact for each release.

### Responsibilities
- Draft and maintain user-facing and internal documentation
- Align documentation milestones with release timelines
- Review release notes drafted by Developers or Product Manager and finalize them
- Coordinate with Developers for technical accuracy
- Update the [project-handoff-checklist.md](project-handoff-checklist.md) docs section when documentation is complete

### Goals
- Ensure every release ships with complete, accurate documentation
- Reduce support ticket volume through proactive, self-service documentation
- Maintain a consistent voice and structure across all docs

### Typical Communication / Interaction
- **→ Developers:** requests technical review of drafted content; collaborates on API reference accuracy.
- **→ Product Manager:** aligns on what's user-facing vs. internal; receives sign-off on messaging.
- **→ Project Manager:** reports documentation readiness status; flags documentation risk to project timeline.
- **→ Release Manager:** confirms documentation is complete before release execution (see [release-checklist.md](release-checklist.md)).
- **→ Customer Support Representative:** coordinates on support articles and known-issues documentation.

---

## Security Engineer

### Role Summary
Security Engineers advise on security requirements, perform security reviews, and ensure that security controls are integrated throughout the project lifecycle. They own the security sign-off for each release.

### Responsibilities
- Define security requirements and acceptance criteria alongside Product Manager
- Review designs and architectures for security risks
- Conduct or coordinate security scans, penetration tests, and code reviews
- Track and prioritize security findings in the risk register
- Provide security sign-off in release readiness review (see [release-checklist.md](release-checklist.md))

### Goals
- Integrate security early (shift-left) to reduce late-stage risk
- Ensure compliance with applicable standards and policies
- Maintain a documented security posture for each release

### Typical Communication / Interaction
- **→ Project Manager:** contributes security risks to the risk register; escalates high-severity findings.
- **→ Developers:** conducts code reviews for security issues; advises on secure coding patterns.
- **→ QA:** coordinates security test scenarios and scan results.
- **→ Product Manager:** clarifies security requirements that affect scope or timeline.
- **→ Release Manager:** provides security sign-off before release execution.

---

## Release Manager

### Role Summary
Release Managers oversee the coordination of all release activities — scheduling, approvals, testing completion, stakeholder communication, and go/no-go decisions. They own the release process and the [release-checklist.md](release-checklist.md).

### Responsibilities
- Schedule and manage the release calendar
- Coordinate pre-release sign-off from QA, Security Engineer, Technical Writer, and Product Manager
- Drive the go/no-go decision and document the outcome
- Orchestrate deployment execution and post-deploy verification
- Communicate release status to stakeholders and Customer Support

### Goals
- Deliver releases on schedule with minimal risk
- Ensure all required approvals and artifacts are in place before deployment
- Maintain a clear audit trail of release decisions

### Typical Communication / Interaction
- **→ Project Manager:** receives release timeline constraints; escalates blockers that affect milestone dates.
- **→ QA:** confirms test completion and release readiness sign-off.
- **→ Security Engineer:** obtains security sign-off.
- **→ Technical Writer:** confirms documentation readiness.
- **→ Developers:** coordinates deployment steps and rollback procedures.
- **→ Customer Support Representative:** sends pre-release heads-up and post-release announcement.

---

## Customer Support Representative

### Role Summary
Customer Support Representatives serve as the bridge between end users and the product/project teams. They surface recurring customer issues, validate release impact, and ensure support readiness for every release.

### Responsibilities
- Collect, triage, and channel customer feedback to Product Manager and Project Manager
- Identify recurring issues and escalate patterns that warrant product backlog items
- Participate in release planning to understand upcoming changes
- Prepare support team with release notes, known issues, and FAQs before go-live
- Monitor post-release ticket volumes and report anomalies

### Goals
- Reduce time-to-resolution for customer issues
- Ensure support team is prepared for every release
- Close the feedback loop between customers and the delivery team

### Typical Communication / Interaction
- **→ Product Manager:** delivers aggregated customer feedback and feature requests; participates in roadmap reviews.
- **→ Release Manager:** receives pre-release communications; confirms support readiness before go/no-go.
- **→ Technical Writer:** collaborates on user-facing documentation, FAQs, and known-issues articles.
- **→ Project Manager:** escalates customer-impacting incidents that require project-level response.

---

## Example Workflow: Planning → Execution → Release

This example shows how personas interact and hand off work during a typical project cycle.

### Planning Phase
1. **Product Manager** creates problem statement and defines success metrics.
2. **Project Manager** schedules kickoff; builds timeline, milestone map, and risk register.
3. **UX Designer** runs user research and produces wireframes; hands off designs to **Developers** and **Product Manager** for approval.
4. **Security Engineer** reviews designs for security requirements; adds findings to risk register.
5. **Technical Writer** identifies documentation scope and adds documentation milestones to the plan.

### Execution Phase
1. **Developers** implement features against UX specs and acceptance criteria.
2. **UX Designer** is available for clarification; reviews implemented UI before QA.
3. **QA** executes test plans; files defects to **Developers**; reports status to **Project Manager**.
4. **Security Engineer** conducts code review and security scans; tracks findings.
5. **Technical Writer** drafts user guides and release notes in parallel with development.

### Release Phase
1. **Release Manager** opens the [release-checklist.md](release-checklist.md) and drives sign-off from QA, Security Engineer, Technical Writer, and Product Manager.
2. **Project Manager** confirms timeline and that the [project-handoff-checklist.md](project-handoff-checklist.md) is complete.
3. **Release Manager** calls go/no-go; coordinates deployment with **Developers**.
4. **Customer Support Representative** is briefed; support articles are published.
5. **Release Manager** sends post-release announcement; monitors for incidents.

See also:
- [role-responsibility-matrix.md](role-responsibility-matrix.md) — RACI for core activities
- [release-checklist.md](release-checklist.md) — Pre-release sign-off and deployment steps
- [project-handoff-checklist.md](project-handoff-checklist.md) — Planning → Execution → Release handoff

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

