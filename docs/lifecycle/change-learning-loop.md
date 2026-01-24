# Change Learning Loop

This document defines the **Change Learning Loop** as a canonical lifecycle
in CIMP.

The Change Learning Loop describes how experience from changes and incidents
is converted into **durable, enforceable system knowledge** over time.

Learning in CIMP is a property of the system, not of individuals or teams.

---

## Canonical loop

Every meaningful change or incident may introduce new knowledge.

CIMP defines the following canonical learning loop:

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

Each step has a **distinct and non-overlapping responsibility**.

If any step is skipped, learning is considered incomplete.

---

## Lifecycle elements

### CHANGE_PLAN — Intent under constraint

A CHANGE_PLAN fixes:
- the intent of the change
- the scope of impact
- the invariants that must not be violated
- the conditions for rollback or termination

A change without an explicit plan is an uncontrolled change
and cannot be safely learned from.

---

### RETRO — Observation of outcomes

A RETRO records:
- what actually happened
- what outcomes were observed
- what deviated from expectations

A RETRO does not:
- assign blame
- prescribe solutions
- perform remediation

Its role is to capture **observations**, not decisions.

---

### INCIDENT_LESSON — Generalized knowledge

An INCIDENT_LESSON extracts knowledge that is:
- independent of a specific implementation
- applicable beyond a single incident
- expressed in terms of invariants, patterns, and detection gaps

An INCIDENT_LESSON is not:
- an incident report
- a root cause analysis
- a remediation plan

A lesson that cannot be reused is not considered a lesson.

---

### PRACTICE — Normative rule

A PRACTICE encodes a lesson as a **normative rule**.

A practice:
- states what must or must not be done
- protects one or more invariants
- is testable or reviewable
- may allow explicitly documented exceptions

Practices define expected system behavior for future changes.

---

### CHECKLIST / CONSTRAINT — Enforcement

A PRACTICE only becomes effective when enforced.

Enforcement mechanisms include:
- review checklists
- automated validation
- schema or runtime constraints
- monitoring and alerting rules

A rule that is not enforced is advisory.
Advisory rules do not constitute learning.

---

### FOLLOW-UP CHANGE — Structural response

Some lessons require structural changes to the system.

In such cases, a new CHANGE_PLAN is created to:
- introduce new constraints
- add missing validation
- modify architecture or tooling

This initiates a new iteration of the learning loop.

---

## Learning criteria

In CIMP, learning is only considered complete when:

- experience produces an explicit lesson
- the lesson becomes a normative rule
- the rule is enforced by the system

A retrospective without a lesson,  
a lesson without a practice,  
or a practice without enforcement  
**does not count as learning**.

---

## Relationship to practices

Practices in CIMP are **outputs** of the Change Learning Loop.

A practice without a traceable origin in:
- a change
- an incident
- or a retrospective

is considered provisional and subject to revision.

---

## Canonical observation

Systems do not learn by reflection alone.

Systems learn when experience
results in **changes to the rules that govern future behavior**.

The Change Learning Loop defines how CIMP
prevents systems from forgetting what they have learned.


Each step has a **distinct and non-overlapping responsibility**.

If any step is skipped, learning is considered incomplete.

---

## Lifecycle elements

### CHANGE_PLAN — Intent under constraint

A CHANGE_PLAN fixes:
- the intent of the change
- the scope of impact
- the invariants that must not be violated
- the conditions for rollback or termination

A change without an explicit plan is an uncontrolled change
and cannot be safely learned from.

---

### RETRO — Observation of outcomes

A RETRO records:
- what actually happened
- what outcomes were observed
- what deviated from expectations

A RETRO does not:
- assign blame
- prescribe solutions
- perform remediation

Its role is to capture **observations**, not decisions.

---

### INCIDENT_LESSON — Generalized knowledge

An INCIDENT_LESSON extracts knowledge that is:
- independent of a specific implementation
- applicable beyond a single incident
- expressed in terms of invariants, patterns, and detection gaps

An INCIDENT_LESSON is not:
- an incident report
- a root cause analysis
- a remediation plan

A lesson that cannot be reused is not considered a lesson.

---

### PRACTICE — Normative rule

A PRACTICE encodes a lesson as a **normative rule**.

A practice:
- states what must or must not be done
- protects one or more invariants
- is testable or reviewable
- may allow explicitly documented exceptions

Practices define expected system behavior for future changes.

---

### CHECKLIST / CONSTRAINT — Enforcement

A PRACTICE only becomes effective when enforced.

Enforcement mechanisms include:
- review checklists
- automated validation
- schema or runtime constraints
- monitoring and alerting rules

A rule that is not enforced is advisory.
Advisory rules do not constitute learning.

---

### FOLLOW-UP CHANGE — Structural response

Some lessons require structural changes to the system.

In such cases, a new CHANGE_PLAN is created to:
- introduce new constraints
- add missing validation
- modify architecture or tooling

This initiates a new iteration of the learning loop.

---

## Learning criteria

In CIMP, learning is only considered complete when:

- experience produces an explicit lesson
- the lesson becomes a normative rule
- the rule is enforced by the system

A retrospective without a lesson,  
a lesson without a practice,  
or a practice without enforcement  
**does not count as learning**.

---

## Relationship to practices

Practices in CIMP are **outputs** of the Change Learning Loop.

A practice without a traceable origin in:
- a change
- an incident
- or a retrospective

is considered provisional and subject to revision.

---

## Canonical observation

Systems do not learn by reflection alone.

Systems learn when experience
results in **changes to the rules that govern future behavior**.

The Change Learning Loop defines how CIMP
prevents systems from forgetting what they have learned.
