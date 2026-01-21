# Change

A Change is a **deliberate modification** to a system that can alter its behavior, constraints, or risk profile.

Not all work is a Change.

This distinction is fundamental.

---

## What counts as a Change

A Change is any action that can:

- alter system behavior
- modify constraints or invariants
- introduce or remove risk
- change failure modes
- affect operational assumptions
- impact users, data, or compliance

If an action can change **how the system behaves or fails**, it is a Change.

---

## Examples of Changes

The following are Changes:

- modifying business logic
- changing data models or schemas
- altering performance characteristics
- introducing caching or queues
- changing deployment topology
- modifying access control rules
- altering configuration that affects runtime behavior
- refactoring that changes failure modes

Even if functionality appears unchanged,  
a different failure mode is still a Change.

---

## What is not a Change

The following are usually **not** Changes:

- formatting or stylistic code edits
- comment-only updates
- documentation changes without behavioral impact
- test additions that do not alter execution paths

However, if these actions influence:
- operational behavior
- safety assumptions
- decision-making

they may still qualify as Changes.

---

## Change vs implementation detail

A Change is defined by **effect**, not by implementation size.

A one-line change can be a major Change.  
A large refactor may be a minor Change.

Lines of code are irrelevant.

---

## Intent precedes Change

A Change without Intent is noise.

Before a Change is executed:
- Intent must be explicit
- scope must be bounded
- constraints must be known

A Change that cannot explain *why it exists*  
is indistinguishable from accidental modification.

---

## Change and risk

Every Change introduces risk.

Risk may be:
- direct or indirect
- known or unknown
- acceptable or unacceptable

Denying risk does not remove it.

CIMP treats risk as a property of Change, not as an exception.

---

## Change granularity

Changes should be **as small as possible**, but **as complete as necessary**.

Artificially small Changes hide intent.  
Overly large Changes hide risk.

Granularity is a governance decision, not a coding preference.

---

## Change ownership

Every Change must have:
- a clear owner
- an explicit Intent
- traceable decisions

Collective ownership without accountability  
is indistinguishable from no ownership.

---

## Change and incidents

Incidents do not occur in isolation.

They are consequences of previous Changes.

Understanding an incident requires understanding:
- which Change introduced the conditions
- what Intent justified it
- which constraints were assumed

Without Changes, incidents have no history.

---

## Final distinction

Work is activity.

Change is commitment.

CIMP governs Change, not work.
