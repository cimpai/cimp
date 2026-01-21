# Constraints

Constraints define **boundaries that must hold**  
regardless of how a Change is implemented.

They protect the system from unacceptable outcomes.

---

## What Constraints are

Constraints define:
- conditions that must remain true
- assumptions that cannot be violated
- boundaries enforced by business, law, or architecture

Constraints answer the question:

> “What must not break, even if everything else changes?”

---

## What Constraints are not

Constraints are not:
- goals
- preferences
- implementation details
- optimizations

Constraints limit freedom by design.

---

## Types of constraints

Common categories include:
- data integrity constraints
- security constraints
- regulatory or legal constraints
- performance floors or ceilings
- operational constraints
- architectural invariants

Not all constraints are technical.

---

## Invariants

An **Invariant** is a constraint that must hold **at all times**.

Examples:
- balances must never become negative
- data must never be lost
- access must always be authorized

All invariants are constraints.  
Not all constraints are invariants.

---

## Explicit vs implicit constraints

Most systems operate with implicit constraints:
- “this must never happen”
- “we assume this is safe”
- “this is not supposed to change”

Implicit constraints are fragile.

Undocumented constraints are eventually violated.

---

## Constraints and Change

Every Change must be evaluated against constraints.

If a Change violates a constraint:
- it must be rejected
- or the constraint must be consciously revised

Silent violation is the worst outcome.

---

## Constraints and incidents

Many Incidents are constraint violations.

Without explicit constraints:
- violations look like surprises
- root cause analysis becomes vague
- accountability disappears

Constraints turn surprises into signals.

---

## Constraints as governance

Constraints are not suggestions.

They are **non-negotiable boundaries**  
until explicitly changed.

Changing a constraint requires:
- explicit decision
- documented rationale
- accepted risk

---

## Final note

Constraints make systems predictable.

Without them, Change has no limits.
