# OctoAcme — Role Responsibility Matrix (RACI)

## Purpose
Provide a lightweight, project-level reference showing who is **Responsible**, **Accountable**, **Consulted**, and **Informed** for each core project activity.

## How to use this matrix
- **Per project:** Copy this file into your project folder (or reference it from your Project Charter) and update the role assignments to match your project's actual staffing.
- **Ownership:** The Project Manager owns this matrix for delivery activities; the Product Manager owns the requirements and success-metric rows.
- **Updates:** Revise the matrix at kickoff and again when the team composition or scope changes significantly.
- **Abbreviations:** R = Responsible | A = Accountable | C = Consulted | I = Informed

---

## Matrix

| Activity | PM (Project Mgr) | PdM (Product Mgr) | Developers | QA | UX Designer | Technical Writer | Security Engineer | Release Manager | Customer Support |
|---|---|---|---|---|---|---|---|---|---|
| Define requirements & success metrics | C | **A/R** | C | C | C | I | C | I | C |
| Estimate & plan (timeline, milestones) | **A/R** | C | C | C | I | I | I | C | I |
| Design sign-off | C | **A** | C | I | **R** | I | C | I | I |
| Implementation | I | I | **A/R** | C | C | I | C | I | I |
| Testing & QA sign-off | C | I | R | **A/R** | C | I | C | I | I |
| Release readiness review | C | C | C | R | I | R | R | **A/R** | C |
| Release execution (deployment) | I | I | R | I | I | I | I | **A/R** | I |
| Post-release support & monitoring | C | I | C | I | I | C | C | C | **A/R** |
| Documentation | I | C | C | I | I | **A/R** | I | I | C |
| Security review | C | C | C | C | I | I | **A/R** | C | I |
| Retro action ownership | **A/R** | C | R | R | R | R | R | R | R |

> **Note:** "A/R" means the same person is both accountable and responsible for that activity on most projects. Adjust per project context.

---

## Role Key

| Abbreviation | Full Role |
|---|---|
| PM | Project Manager |
| PdM | Product Manager |
| QA | QA / Testing |
| UX Designer | UX Designer |
| Technical Writer | Technical Writer |
| SE | Security Engineer |
| RM | Release Manager |
| Customer Support | Customer Support Representative |

---

## Related documents
- [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) — Full persona descriptions and interaction notes
- [release-checklist.md](release-checklist.md) — Release readiness sign-off checklist
- [project-handoff-checklist.md](project-handoff-checklist.md) — Planning and execution handoff checklists
