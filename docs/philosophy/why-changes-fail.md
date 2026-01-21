# Why Changes Fail

Most changes fail for reasons that are invisible at the moment the change is made.

Failures are rarely caused by a single mistake.  
They emerge from accumulated blind spots.

This document describes the most common structural reasons why changes fail in complex systems.

---

## Failure is not an event

Failure is not a moment.

It is a **process**.

By the time an incident occurs, the failure has usually been unfolding for weeks or months.

The incident only reveals it.

---

## Missing intent

Many changes begin with action instead of intent.

Common signals:
- “We need to fix this quickly”
- “Let’s refactor while we’re here”
- “This is obvious, no need to write it down”

When intent is not explicit:
- success criteria are unclear
- trade-offs are implicit
- disagreement is discovered too late

The change may still work — but only by accident.

---

## Unbounded scope

Changes fail when scope is undefined.

Without explicit boundaries:
- “small changes” expand silently
- unrelated improvements are mixed in
- risk grows non-linearly

Scope creep is not caused by bad discipline.  
It is caused by missing constraints.

---

## Implicit constraints

Most systems have constraints that are real but undocumented.

Examples:
- “This table must never lock”
- “This endpoint cannot change behavior”
- “This process runs under regulatory assumptions”

When constraints are implicit:
- they are easy to violate
- violations are only detected in production
- blame replaces analysis

Systems do not enforce undocumented rules.

---

## Decision diffusion

When decisions are not explicit, responsibility diffuses.

Typical patterns:
- “Everyone agreed”
- “It was obvious”
- “We’ve always done it this way”

After a failure, no one can explain:
- who decided
- what alternatives were considered
- why risks were accepted

Without decisions, there is no accountability.

---

## Loss of architectural memory

Complex systems evolve over years.

Context is lost when:
- decisions are made in chat
- PR discussions disappear
- incidents are not connected to future changes

The system remembers behavior.  
Humans forget intent.

Without memory, the same mistakes repeat — rationally, with good reasons each time.

---

## Optimizing for speed

Speed hides risk.

When speed becomes the dominant value:
- review is shortened
- assumptions go unchallenged
- dissent is discouraged

Fast feedback loops are valuable.

Fast **unexamined** change is not.

---

## Tool-driven change

Tools shape behavior.

When tools lead and intent follows:
- pipelines define what is possible
- automation replaces judgment
- change becomes mechanical

Tools are excellent at execution.

They are poor at understanding consequences.

---

## Incident-centric learning

Many organizations “learn” only from incidents.

This creates a distorted model:
- near-misses are ignored
- successful risky changes teach nothing
- learning is reactive

Incidents are signals, not teachers.

Learning requires structure.

---

## Final observation

Changes do not fail because people are careless.

They fail because systems make it easy to act  
and hard to think.

CIMP exists to reverse that balance.
