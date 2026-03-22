# OctoAcme — Release Checklist

## Purpose
A concrete, actionable checklist that complements [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md) with specific owner responsibilities, required artifacts, approvals, and communication steps.

---

## 1. Pre-Release Preparation

| # | Task | Owner | Done |
|---|---|---|---|
| 1 | All acceptance criteria met and PRs merged to release branch | Developers | [ ] |
| 2 | CI pipeline green (build, lint, unit tests) | Developers | [ ] |
| 3 | Security scans completed; no unresolved high/critical findings | Security Engineer | [ ] |
| 4 | Full regression suite executed; defects triaged | QA | [ ] |
| 5 | Release notes drafted and reviewed | Technical Writer | [ ] |
| 6 | Migration scripts (if any) tested in staging | Developers / QA | [ ] |
| 7 | Rollback / mitigation plan documented | Release Manager | [ ] |
| 8 | Deployment window scheduled and communicated | Release Manager | [ ] |
| 9 | Support team briefed on changes and known issues | Customer Support Representative | [ ] |
| 10 | Documentation published or staged for publish | Technical Writer | [ ] |

---

## 2. Pre-Release Sign-Off

Each role below confirms they have completed their checklist items and the release is ready to proceed. Update with name and date.

| Role | Name | Date | Sign-Off |
|---|---|---|---|
| Product Manager | | | [ ] Approved |
| QA Lead | | | [ ] Approved |
| Security Engineer | | | [ ] Approved |
| Technical Writer | | | [ ] Approved |
| Customer Support Representative | | | [ ] Prepared |
| Release Manager | | | [ ] Go / ⬜ No-Go |

> If any role marks **No-Go**, the Release Manager records the blocker and reschedules. No-Go reasons must be documented in the project risk register.

---

## 3. Release Execution

| # | Task | Owner | Done |
|---|---|---|---|
| 1 | Tag release in version control | Developers | [ ] |
| 2 | Deploy to staging; run smoke tests | Developers / QA | [ ] |
| 3 | Staging smoke tests pass | QA | [ ] |
| 4 | Deploy to production (automated pipeline preferred) | Developers / Release Manager | [ ] |
| 5 | Run post-deploy smoke tests in production | QA / Developers | [ ] |
| 6 | Confirm monitoring dashboards show healthy state | Developers / Release Manager | [ ] |

---

## 4. Post-Release Communication

| # | Task | Owner | Done |
|---|---|---|---|
| 1 | Send release announcement to stakeholders | Release Manager / Project Manager | [ ] |
| 2 | Publish release notes (external or internal) | Technical Writer | [ ] |
| 3 | Notify Customer Support with final release summary | Release Manager | [ ] |
| 4 | Update project board / milestone as released | Project Manager | [ ] |

---

## 5. Rollback Reminder

If a critical issue is detected after deployment:
1. **Release Manager** triggers rollback decision and notifies the team.
2. **Developers** execute the rollback procedure documented in [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md).
3. **QA** verifies the rollback restored expected behavior.
4. **Project Manager** logs the incident in the risk register and schedules a retrospective item.
5. **Customer Support Representative** communicates service status to affected users.

---

## Related documents
- [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md) — Release types, deployment guide, rollback playbook
- [role-responsibility-matrix.md](role-responsibility-matrix.md) — RACI for release readiness and execution activities
- [project-handoff-checklist.md](project-handoff-checklist.md) — Handoff checklist before release phase begins
- [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) — Full role descriptions
