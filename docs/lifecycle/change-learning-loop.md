# Change Learning Loop

This document defines the **canonical learning loop in CIMP**.

It describes how a system turns changes, failures, and surprises
into **durable, enforceable knowledge** — not just experience.

This is not a team ritual.  
This is not a retrospective format.  
This is not a best-practice catalog.

This is a **system-level learning mechanism**.

---

## The Core Loop

Every meaningful change in a system may trigger learning.

CIMP defines the following canonical chain:

```
CHANGE_PLAN
↓
RETRO
↓
INCIDENT_LESSON
↓
PRACTICE
↓
CHECKLIST / CONSTRAINT
↓
FOLLOW-UP CHANGE (if needed)
```


Each step has a **single responsibility**.
Skipping steps breaks the learning loop.

---

## Step Definitions

### 1. CHANGE_PLAN — Controlled Intent

A CHANGE_PLAN defines:
- what we intend to change
- what must not be broken (invariants)
- how the change will be executed and rolled back

A change without a plan is an uncontrolled experiment.

---

### 2. RETRO — System Feedback

A RETRO answers:
- what actually happened
- what worked
- what failed
- what surprised us

A RETRO:
- does not assign blame
- does not describe execution
- does not fix the problem

Its purpose is **reflection, not action**.

---

### 3. INCIDENT_LESSON — Generalized Knowledge

An INCIDENT_LESSON extracts **reusable knowledge** from a failure or surprise.

It captures:
- the failure pattern
- violated or missing invariants
- detection gaps
- preventive signals

It is:
- not an incident report
- not a root cause analysis
- not a fix description

A lesson must survive beyond the specific incident.

---

### 4. PRACTICE — System Rule

A PRACTICE turns a lesson into a **normative rule**.

A practice:
- is imperative (“must / must not”)
- protects an invariant
- is testable
- may allow explicit, documented exceptions

Practices define **how the system is expected to behave going forward**.

---

### 5. CHECKLIST / CONSTRAINT — Enforcement

Practices are only useful if they are enforced.

Enforcement mechanisms include:
- review checklists
- CI/CD validation
- schema constraints
- monitoring rules

A practice without enforcement is advice.
Advice is not learning.

---

### 6. FOLLOW-UP CHANGE — Structural Correction (Optional)

Some lessons require structural changes:
- new tooling
- new tests
- new constraints
- refactoring

In such cases, a new CHANGE_PLAN is created,
and the loop starts again.

---

## What Counts as Learning

In CIMP:

> A retrospective that does not produce a lesson,  
> a lesson that does not become a practice,  
> and a practice that is not enforced  
> **do not count as learning**.

Learning is only complete when future changes
are **structurally prevented** from repeating the same class of failure.

---

## How This Differs from Agile Retrospectives

Agile retrospectives usually stop here:

```
CHANGE
↓
RETRO
↓
“We learned something”
```

CIMP continues until:
- the lesson is explicit
- the rule is written
- the rule is enforced

CIMP is not about remembering better.
It is about **making forgetting impossible**.

---

## Relationship to Practices in This Repository

Practices in this repository are expected to be:
- outputs of the Change Learning Loop
- derived from real changes or incidents
- justified by lessons, not opinions

A practice without a traceable origin
is considered weak and temporary.

---

## Design Principle

> Systems do not learn by reflection.  
> Systems learn by changing their rules.

The Change Learning Loop is how CIMP
turns experience into system behavior.
