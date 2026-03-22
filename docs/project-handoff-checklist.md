# OctoAcme — Project Handoff Checklist

## Purpose
Ensure smooth, low-risk transitions between project phases by making handoff expectations explicit. Use this checklist at two key transition points: **Planning → Execution** and **Execution → Release**.

---

## Handoff 1: Planning → Execution

**Triggered by:** Completion of the planning phase (kickoff held, backlog groomed, timeline agreed).  
**Owned by:** Project Manager (PM)

### Project One-Pager / Charter Completeness

| Field | Owner | Status |
|---|---|---|
| Problem statement | Product Manager (PdM) | [ ] Complete |
| Success metrics and KPIs | Product Manager (PdM) | [ ] Complete |
| Scope summary | Product Manager (PdM) + Project Manager | [ ] Complete |
| Timeline and milestones | Project Manager (PM) | [ ] Complete |
| Risk register (initial) | Project Manager (PM) | [ ] Complete |
| Stakeholder list | Project Manager (PM) | [ ] Complete |
| Resource plan | Project Manager (PM) | [ ] Complete |
| Design assets / wireframes | UX Designer | [ ] Complete or In Progress |
| Security requirements | Security Engineer | [ ] Consulted |
| Documentation plan | Technical Writer | [ ] Consulted |

### Execution Readiness

| # | Item | Owner | Done |
|---|---|---|---|
| 1 | Backlog prioritized with acceptance criteria on top items | Product Manager | [ ] |
| 2 | Definition of Done documented and agreed | Project Manager | [ ] |
| 3 | Development environments provisioned | Developers | [ ] |
| 4 | Initial UX wireframes reviewed and approved | UX Designer + Product Manager | [ ] |
| 5 | Security requirements captured in backlog (if applicable) | Security Engineer | [ ] |
| 6 | Test plan / QA approach drafted | QA | [ ] |
| 7 | Documentation milestone added to plan | Technical Writer + Project Manager | [ ] |
| 8 | Team onboarded (access, tooling, repos) | Project Manager | [ ] |

### Sign-Off: Planning → Execution

| Role | Name | Date | Sign-Off |
|---|---|---|---|
| Project Manager | | | [ ] Ready to proceed |
| Product Manager | | | [ ] Ready to proceed |
| Tech Lead / Developers | | | [ ] Ready to proceed |

---

## Handoff 2: Execution → Release

**Triggered by:** Feature-complete milestone reached; all items meet the Definition of Done.  
**Owned by:** Release Manager (coordinates), Project Manager (confirms timeline).

### Feature Completeness

| # | Item | Owner | Done |
|---|---|---|---|
| 1 | All planned scope implemented and merged | Developers | [ ] |
| 2 | Acceptance criteria verified for all stories | QA + Product Manager | [ ] |
| 3 | Outstanding defects triaged; only accepted known issues remain | QA | [ ] |
| 4 | UX review completed on implemented features | UX Designer | [ ] |

### Environment & Infrastructure Readiness

| # | Item | Owner | Done |
|---|---|---|---|
| 1 | Staging environment updated and stable | Developers | [ ] |
| 2 | Database migrations tested in staging | Developers | [ ] |
| 3 | Infrastructure / config changes documented | Developers | [ ] |
| 4 | Monitoring and alerting verified | Developers | [ ] |

### Documentation & Training

| # | Item | Owner | Done |
|---|---|---|---|
| 1 | User-facing documentation drafted and reviewed | Technical Writer | [ ] |
| 2 | Release notes finalized | Technical Writer | [ ] |
| 3 | Internal runbooks / ops docs updated (if applicable) | Technical Writer + Developers | [ ] |
| 4 | Support team training / briefing completed | Customer Support Representative | [ ] |

### Security & Compliance

| # | Item | Owner | Done |
|---|---|---|---|
| 1 | Security scans completed with no unresolved criticals | Security Engineer | [ ] |
| 2 | Security sign-off provided | Security Engineer | [ ] |
| 3 | Compliance requirements met (if applicable) | Security Engineer + Project Manager | [ ] |

### Sign-Off: Execution → Release

| Role | Name | Date | Sign-Off |
|---|---|---|---|
| Project Manager | | | [ ] Ready to proceed |
| Product Manager | | | [ ] Ready to proceed |
| QA Lead | | | [ ] Ready to proceed |
| Security Engineer | | | [ ] Ready to proceed |
| Technical Writer | | | [ ] Ready to proceed |
| Release Manager | | | [ ] Go for release |

> Once this sign-off is complete, open [release-checklist.md](release-checklist.md) to begin the release execution process.

---

## Notes for the Project Manager

- **Success Metrics** are owned by the **Product Manager** and must be agreed before execution begins.
- **Timeline and risk register** are owned by the **Project Manager** throughout the project.
- **Design sign-off** requires **UX Designer** and **Product Manager** approval — see [role-responsibility-matrix.md](role-responsibility-matrix.md).
- **Security review** should be consulted at both handoff points, not just at release.
- **Documentation** completeness is confirmed by the **Technical Writer** — do not proceed to release without this sign-off.

---

## Related documents
- [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) — Full role descriptions and interaction notes
- [role-responsibility-matrix.md](role-responsibility-matrix.md) — RACI for all activities
- [release-checklist.md](release-checklist.md) — Release execution checklist
- [octoacme-project-planning.md](octoacme-project-planning.md) — Planning activities and templates
