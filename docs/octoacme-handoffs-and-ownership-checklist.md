# OctoAcme — Handoffs & Ownership Checklist

## Purpose
Define clear ownership and handoff criteria for each major stage of the project lifecycle, reducing gaps in accountability and ensuring smooth transitions between teams and roles.

## How to Use
- Work through each stage checklist before moving to the next stage.
- The **Owner** column identifies the role primarily responsible for completing or sign-off.
- The **Consulted / Informed** column lists roles that must be engaged at that step.
- Adapt this checklist per project by adding stage-specific items as needed.

---

## RACI Key
| Symbol | Meaning |
|--------|---------|
| **R** | Responsible — does the work |
| **A** | Accountable — final sign-off |
| **C** | Consulted — provides input |
| **I** | Informed — kept up to date |

---

## Stage 1 — Requirements → Design Handoff

| Checklist Item | Owner (R/A) | Consulted / Informed |
|---|---|---|
| Problem statement and business requirements documented | Business Analyst (R), PdM (A) | Project Manager (I), Stakeholders (C) |
| User stories written with clear acceptance criteria | PdM (R/A) | Business Analyst (C), UX Designer (C) |
| UX research findings and user flows shared | UX Designer (R/A) | PdM (C), Developers (I) |
| Wireframes / prototypes reviewed and approved | UX Designer (R), PdM (A) | Developers (C), QA (I) |
| Design handoff package (specs, assets) delivered to Developers | UX Designer (R/A) | Developers (C) |

**Checklist before advancing:**
- [ ] Business requirements signed off by PdM and Business Analyst
- [ ] Wireframes approved by PdM
- [ ] Design specs accessible to development team
- [ ] Acceptance criteria include UX/usability expectations

---

## Stage 2 — Design → Build Handoff

| Checklist Item | Owner (R/A) | Consulted / Informed |
|---|---|---|
| Backlog items refined and estimated | Project Manager (R), PdM (A) | Developers (C), QA (C), Business Analyst (C) |
| Infrastructure and environment requirements identified | DevOps/SRE (R/A) | Developers (C), Project Manager (I) |
| Initial test plan drafted | QA Engineer (R/A) | PdM (C), Developers (C) |
| Definition of Done documented and agreed | Project Manager (R), PdM (A) | All roles (C) |
| Support readiness checklist started | Customer Support Liaison (R/A) | PdM (I) |

**Checklist before advancing:**
- [ ] Sprint backlog ready with estimated items meeting Definition of Ready
- [ ] DevOps environment and pipeline in place
- [ ] Initial test plan shared with team
- [ ] Definition of Done agreed and documented

---

## Stage 3 — Build → QA Handoff

| Checklist Item | Owner (R/A) | Consulted / Informed |
|---|---|---|
| Feature implementation complete per acceptance criteria | Developers (R/A) | PdM (I), QA (I) |
| Unit and integration tests passing in CI | Developers (R/A) | DevOps/SRE (C) |
| PR reviewed and merged with no open critical issues | Developers (R), Project Manager (A) | QA (I) |
| Feature deployed to staging/test environment | DevOps/SRE (R/A) | Developers (I), QA (I) |
| Build notes / known issues documented for QA | Developers (R/A) | QA (C) |

**Checklist before advancing:**
- [ ] All acceptance criteria implemented
- [ ] CI pipeline green (tests, lint, security scan)
- [ ] Build deployed and verified in staging
- [ ] QA has received build notes and test environment access

---

## Stage 4 — QA → Release Handoff

| Checklist Item | Owner (R/A) | Consulted / Informed |
|---|---|---|
| Test cases executed and results documented | QA Engineer (R/A) | Project Manager (I), PdM (I) |
| Critical and high-severity defects resolved or risk-accepted | Developers (R), PdM (A) | QA (C), Project Manager (C) |
| QA sign-off (go/no-go) provided | QA Engineer (R/A) | Project Manager (C), PdM (I) |
| Release notes drafted | PdM (R/A) | Customer Support Liaison (C), Project Manager (C) |
| Rollback plan confirmed | DevOps/SRE (R/A) | Project Manager (I), PdM (I) |

**Checklist before advancing:**
- [ ] QA sign-off received
- [ ] No unresolved critical defects
- [ ] Release notes finalized
- [ ] Rollback procedure documented and tested

---

## Stage 5 — Release → Support Handoff

| Checklist Item | Owner (R/A) | Consulted / Informed |
|---|---|---|
| Deployment executed and post-deploy checks completed | DevOps/SRE (R/A) | Developers (C), Project Manager (I) |
| Release announcement sent to stakeholders | Project Manager (R), PdM (A) | Customer Support Liaison (I) |
| Support team briefed on new features and known issues | Customer Support Liaison (R/A) | PdM (C) |
| Knowledge base / documentation updated | Customer Support Liaison (R/A) | PdM (C), Developers (C) |
| Post-launch monitoring in place | DevOps/SRE (R/A) | Project Manager (I) |

**Checklist before advancing:**
- [ ] Deployment verified in production
- [ ] Stakeholders and support team notified
- [ ] Documentation updated and published
- [ ] Monitoring dashboards and alerts active

---

## Stage 6 — Retrospective Inputs

| Checklist Item | Owner (R/A) | Consulted / Informed |
|---|---|---|
| Deployment and reliability metrics shared | DevOps/SRE (R/A) | Project Manager (I) |
| Defect and quality trend data shared | QA Engineer (R/A) | Project Manager (I), PdM (I) |
| Customer feedback and support ticket themes shared | Customer Support Liaison (R/A) | PdM (C) |
| Retrospective facilitated and action items captured | Project Manager (R/A) | All roles (C/I) |
| Action items assigned owners and added to next iteration | Project Manager (R), PdM (A) | All roles (I) |

---

## Related Documents
- [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) — Full role definitions and responsibilities
- [octoacme-project-planning.md](octoacme-project-planning.md) — Planning checklist and backlog template
- [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md) — Execution checklist and workflows
- [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md) — Release process
- [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md) — Retrospective process
