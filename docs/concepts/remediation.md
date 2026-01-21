# Remediation

Remediation is a **Change**.

It is not an exception, not a shortcut, and not a lesser form of change.

Treating remediation as “just a fix” is one of the most common sources of repeated incidents.

---

## What remediation is

Remediation is a deliberate action taken in response to:
- an Incident
- an unacceptable risk
- a discovered flaw in assumptions

Its purpose is to restore acceptable system behavior  
or to change the system so that the incident cannot recur.

---

## What remediation is not

Remediation is not:
- an emergency override without accountability
- a temporary patch with no follow-up
- an excuse to bypass governance
- a silent correction

Speed does not change the nature of a Change.

---

## Why remediation is a Change

Remediation modifies:
- system behavior
- constraints or invariants
- failure modes
- operational assumptions
- risk distribution

Even a minimal fix alters the system.

Therefore, remediation must be governed as a Change.

---

## The remediation trap

Common failure patterns:

- “We’ll fix it now and document later”
- “This is too urgent for a Change Plan”
- “It’s only temporary”

Temporary changes have permanent consequences.

Undocumented remediation becomes invisible debt.

---

## Remediation under pressure

Remediation often happens under stress.

This increases the likelihood of:
- unexamined trade-offs
- hidden scope expansion
- new failure modes

CIMP does not prohibit fast remediation.

It requires **explicit intent even under pressure**.

---

## Minimal remediation intent

Remediation does not require full design documentation.

But it does require:
- a stated intent
- an explicit owner
- known risks
- a plan for review or rollback

Even a few lines are sufficient.

---

## Remediation and learning

Remediation is not complete when the system stabilizes.

It is complete when:
- the incident is understood
- assumptions are corrected
- future changes are informed

Without this step, remediation only resets the clock.

---

## Remediation chains

Poor remediation creates chains:
- fix introduces new risk
- new incident triggers another fix
- system becomes brittle

Each ungoverned remediation compounds fragility.

---

## Remediation and architecture memory

Every remediation must contribute to Architecture Memory.

This includes:
- why the fix was chosen
- which alternatives were rejected
- what risks were accepted

Without memory, remediation erases evidence.

---

## Replay as remediation

Replay is a **special form of remediation** applied to historical data, events, or effects of a Change.

Replay does not fix the past.  
It corrects the system’s **current state** by reprocessing prior actions under updated rules or assumptions.

---

### When replay is used

Replay is appropriate when:
- incorrect data has already been persisted
- business rules were wrong or incomplete
- historical effects must be recalculated
- auditability and traceability must be preserved

Replay is common in:
- billing systems
- ledgers
- analytics pipelines
- event-driven architectures

---

### Replay is still a Change

Replay modifies:
- current system state
- balances or aggregates
- derived data
- user-visible outcomes

Therefore, replay must be treated as a **governed Change**, not a background operation.

---

### Scope-limited by design

Replay is often **deliberately limited in scope**.

Limitations may be based on:
- time ranges
- affected entities
- business decisions
- acceptable impact

Limiting replay scope is a valid decision,  
even when broader correction is technically possible.

---

### Replay and idempotency

Replay must be:
- idempotent
- repeatable
- auditable

Without these properties, replay increases risk instead of reducing it.

---

### Replay and accountability

Replay requires:
- explicit Intent
- documented scope
- business approval when impact is material
- clear ownership

Silent or implicit replay undermines trust.

---

### Replay and learning

Replay completes remediation only when:
- the original Incident is understood
- incorrect assumptions are documented
- future Changes are informed

Replay without learning resets the system  
but preserves the conditions for recurrence.

---

## Final note

Incidents are expensive.

Ungoverned remediation wastes their cost.

CIMP treats remediation as the most critical form of Change.
