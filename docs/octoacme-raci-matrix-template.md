# OctoAcme — RACI / Ownership Matrix Template

## Purpose
This template provides a reusable structure for mapping role responsibilities across project lifecycle phases. Use it to clarify who is **Responsible**, **Accountable**, **Consulted**, and **Informed** for each key activity.

## RACI Key

| Code | Meaning |
|------|---------|
| **R** | **Responsible** — does the work |
| **A** | **Accountable** — owns the outcome; single point of accountability |
| **C** | **Consulted** — provides input before or during the activity |
| **I** | **Informed** — kept up-to-date on progress or outcome |

> Each activity must have exactly one **A**. Multiple **R** entries are allowed when work is shared.

---

## How to use this template

1. Copy the matrix below into your project's planning docs or repo.
2. Fill in the activity rows relevant to your project, removing or adding rows as needed.
3. Assign RACI codes for each role column. Leave the cell blank if the role has no involvement.
4. Review with the full team during kickoff or planning to confirm shared understanding.

---

## RACI Matrix

| Activity | Project Manager | Product Manager | Developer | QA | DevOps/SRE | UX/UI | Business Analyst | Change Manager | Security Champion | Accessibility Lead | Data Analyst | Customer Support | Stakeholders |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| **INITIATION** | | | | | | | | | | | | | |
| Define problem statement and goals | C | A | | | | C | C | C | | | | C | C |
| Stakeholder identification and analysis | A | C | | | | | R | | | | | C | I |
| Initial risk identification | R | C | C | C | C | | C | C | C | | | | I |
| Go/no-go decision | C | R | | | | | C | | | | | | A |
| **PLANNING** | | | | | | | | | | | | | |
| Backlog creation and prioritization | C | A | C | C | C | C | R | | | C | C | C | I |
| Effort estimation | C | C | R | R | R | R | C | | | | | | |
| Release plan and milestone map | A | C | C | C | R | | | | | | | | I |
| Change management plan | C | C | | | | | | A | | | | | I |
| Threat modeling | C | I | C | C | C | | | | A | | | | |
| Accessibility requirements | C | C | R | C | | R | C | | | A | | | |
| Measurement and metrics plan | C | A | C | | C | | C | | | | R | | I |
| **EXECUTION** | | | | | | | | | | | | | |
| Feature implementation | I | I | A/R | C | C | C | | | C | C | | | |
| Design review | C | C | C | I | | A | C | | | C | | | |
| QA and testing | I | I | R | A | C | C | | | C | C | | | |
| Security review | C | I | C | C | C | | | | A | | | | |
| Accessibility review | C | C | R | C | | R | | | | A | | | |
| Risk register updates | A | C | C | C | C | | C | C | C | | C | | I |
| Change communications | C | C | I | I | I | I | C | A | | | | R | I |
| **RELEASE** | | | | | | | | | | | | | |
| Release readiness sign-off | A | C | C | R | R | | | C | C | C | C | C | I |
| Deployment execution | I | I | C | C | A | | | | C | | | | |
| Release notes and communications | C | R | C | C | | | C | C | | | | R | I |
| **RETROSPECTIVE** | | | | | | | | | | | | | |
| Retro facilitation | A | C | C | C | C | C | C | C | C | C | C | C | I |
| Metrics and outcome review | C | R | C | C | C | | C | | | | A | C | I |
| Process improvement actions | A | C | R | R | R | R | R | R | C | C | C | C | I |

---

## Tips

- Revisit and update the RACI at the start of each major lifecycle phase.
- Where ownership is unclear, treat it as a risk and resolve it explicitly in planning.
- For cross-team activities, ensure the **A** role has the authority to make final decisions.
- Reference this template in [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md) and [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md).
- See [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) for full role definitions.
