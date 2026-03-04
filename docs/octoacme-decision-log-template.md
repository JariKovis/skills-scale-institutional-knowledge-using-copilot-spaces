# OctoAcme — Decision Log Template

## Purpose
A Decision Log captures key project decisions as they are made, preserving context and rationale for future reference. Use this template to reduce knowledge loss, support onboarding, and avoid revisiting settled decisions without new information.

## When to use
- Any decision that meaningfully affects scope, timeline, architecture, process, or resource allocation
- Decisions that have been escalated beyond the immediate delivery team
- Decisions where the choice among alternatives is not obvious

---

## How to use this template

1. Copy the **Decision Record** section below for each new decision.
2. Complete all fields. If a field is not applicable, write `N/A` rather than leaving it blank.
3. Add the record to the decision log table at the top of your project's decision log document, then append the full record below it.
4. Link the decision record from any relevant backlog items, planning docs, or risk register entries.

---

## Decision Log Index

Use this table as a summary index. Add one row per decision.

| ID | Title | Date | Owner | Status |
|----|-------|------|-------|--------|
| DEC-001 | _Example: Use PostgreSQL as primary database_ | YYYY-MM-DD | _Role / Name_ | Accepted |

**Status values:** `Proposed` · `Accepted` · `Superseded` · `Deprecated`

---

## Decision Record

### DEC-XXX — [Short Decision Title]

| Field | Value |
|-------|-------|
| **ID** | DEC-XXX |
| **Date** | YYYY-MM-DD |
| **Owner** | _Role and/or name of the person accountable for this decision_ |
| **Status** | `Proposed` / `Accepted` / `Superseded` / `Deprecated` |
| **Supersedes** | _ID of an earlier decision this replaces, or N/A_ |

#### Context
_Describe the situation or problem that required a decision. Include relevant constraints, pressures, and background information. Keep this factual and concise._

#### Decision
_State clearly what was decided. Use active voice: "We will…" or "The team agreed to…"_

#### Alternatives Considered

| Alternative | Pros | Cons | Reason Not Chosen |
|-------------|------|------|-------------------|
| _Option A_ | | | |
| _Option B_ | | | |

#### Consequences
_Describe the expected outcomes of this decision — both positive and negative. Include any follow-up actions, risks introduced, or constraints created._

#### Related Links
- Backlog items: _link(s)_
- Risk register entries: _link(s) or IDs_
- Relevant docs: _link(s)_

---

## Tips

- Log decisions as soon as they are made — context fades quickly.
- Decisions should be linked from the relevant planning or initiation documents; see [octoacme-project-initiation.md](octoacme-project-initiation.md) and [octoacme-project-planning.md](octoacme-project-planning.md).
- When a decision is revisited, update its **Status** to `Superseded` and create a new record that references it.
- The Project Manager is typically responsible for maintaining the decision log, but any team member can add an entry.
