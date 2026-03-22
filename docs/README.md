# OctoAcme Project Management Docs

This README serves as the main entry point for OctoAcme's project management methodology. It summarizes our project management principles and lifecycle, and links to the detailed process documents for each stage.

## OctoAcme Project Management Summary

OctoAcme organizes work around a clear project lifecycle—initiation, planning, execution, release, and retrospective—supported by a small set of core artifacts: the Project One‑pager, roadmap/release plan, sprint backlog, acceptance criteria/Definition of Done, and a risk register. Initiation focuses on validating the business need with a one‑pager that captures the problem, goals, measurable success metrics, stakeholders, and a high‑level timeline. Planning turns approved initiatives into a prioritized, estimated backlog, defines the DoD, and maps releases and milestones while capturing risks and dependencies for ongoing tracking.

Execution follows a disciplined board and Pull Request workflow (Backlog → Ready → In Progress → In Review → QA → Done). Pull Requests should be small when possible, include issue links and acceptance criteria, and run automated tests and linting in CI before review. Team delivery rhythms include short daily standups, weekly delivery syncs, and demos at the end of sprints or milestones. Blocker escalation is tiered from team-level triage to PM escalation, then Product Lead and dependent teams, up to Sponsor-level escalation for business-impacting issues.

Roles and responsibilities are explicit: Product Managers define outcomes, prioritize the backlog and measure success; Project Managers coordinate delivery, schedules, risk and cross-team communications; Developers implement and test features; and QA/testing validates acceptance criteria and quality. Stakeholder input and approvals are captured in artifacts and decision gates, and retrospective action items are turned into tracked issues with owners and due dates so improvements are executed.

Quality assurance and release practices are integrated into the workflow: unit, integration, and end-to-end smoke tests are expected for new work; CI runs tests and security scans; and manual QA is used as needed. Releases follow defined types (patch/minor/major) with pre-release checks (passing CI, release notes, rollback plan) and a deployment checklist that includes staging smoke tests and post-deploy verification. Teams track velocity, burndown, and the Project One‑pager success metrics via dashboards to measure progress and inform continuous improvement during retrospectives.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
