# Change Lifecycle

A Change is not a moment.

It has a lifecycle.

Understanding this lifecycle is essential to governing change in complex systems.

---

## Overview

The CIMP Change Lifecycle describes how a Change:
- originates from Intent
- moves through design and execution
- interacts with reality
- produces consequences
- becomes part of system memory

The lifecycle does not end at deployment.

---

## 1. Intent

The lifecycle begins with **Intent**.

At this stage:
- the problem is defined
- success criteria are stated
- urgency is explained
- trade-offs are acknowledged
- ownership is assigned

No design or implementation should begin before Intent exists.

Intent defines *why* change is allowed to exist.

---

## 2. Scope and boundaries

Intent alone is insufficient.

Before execution, a Change must define:
- what is allowed to change
- what must not change
- which constraints or invariants apply

Boundaries protect both the system and the people changing it.

Unbounded change is indistinguishable from risk accumulation.

---

## 3. Design and proposal

Design translates Intent into a **Change Plan**.

At this stage:
- alternative approaches are considered
- risks are identified
- failure modes are discussed
- rollback or mitigation is planned

The Change Plan is not a guarantee of success.  
It is a declaration of assumptions.

---

## 4. Execution

Execution applies the Change to reality.

This includes:
- code changes
- configuration updates
- infrastructure modifications
- operational actions

Execution is where intent meets uncertainty.

Perfect execution does not eliminate risk.

---

## 5. Observation

After execution, the system must be observed.

Observation answers:
- did behavior change as expected?
- were assumptions valid?
- did new risks appear?

Lack of observation turns Change into guesswork.

---

## 6. Consequences

Every Change produces consequences.

Consequences may be:
- intended or unintended
- immediate or delayed
- local or systemic

Not all consequences are failures.

Ignoring consequences does not prevent them.

---

## 7. Incident (optional, but possible)

Some consequences exceed acceptable boundaries.

When this happens, the Change lifecycle intersects with an **Incident**.

An Incident is not a failure of process.

It is feedback from reality.

---

## 8. Remediation

Remediation is itself a Change.

It requires:
- a new Intent
- explicit ownership
- conscious trade-offs

Treating remediation as “just a fix” breaks the lifecycle.

---

## 9. Architecture memory

The lifecycle ends when the Change is remembered.

This includes:
- preserved Intent
- documented decisions
- recorded incidents
- lessons tied to future Changes

Without memory, the lifecycle loops blindly.

---

## Lifecycle is not linear

In practice, stages overlap.

- Observation may begin before execution completes
- Consequences may appear long after deployment
- Remediation may reveal flawed Intent

The lifecycle is conceptual, not procedural.

---

## Governance implication

Governing Change means governing the entire lifecycle.

Focusing only on:
- design
- implementation
- deployment

ignores where most failures emerge.

---

## Final note

Changes do not end when code is merged.

They end when their consequences are understood  
and integrated into future decisions.
