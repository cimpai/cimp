# Incident

An Incident is a **significant divergence between expected and actual system behavior**.

It is defined by impact, not by surprise.

---

## What counts as an Incident

An Incident occurs when system behavior:

- violates stated or implicit invariants
- causes unacceptable user impact
- introduces data integrity risk
- breaches operational or regulatory assumptions
- exceeds agreed risk boundaries

An Incident may be visible to users or fully internal.

Visibility does not define severity.

---

## What is not an Incident

The following are not Incidents by default:

- expected and handled errors
- known limitations behaving as designed
- rejected requests within defined constraints
- performance degradation within accepted thresholds

Discomfort is not an Incident.  
Unexpected behavior is not automatically an Incident.

Impact is the criterion.

---

## Incident vs bug

Not every bug is an Incident.

A bug becomes an Incident when:
- it affects real users or data
- it violates critical assumptions
- it exceeds accepted risk

Conversely, an Incident may occur without a traditional “bug”.

---

## Incident vs failure

Failure describes what happened.

Incident describes **why attention is required**.

An Incident marks a boundary where:
- assumptions were wrong
- risks materialized
- consequences exceeded tolerance

---

## Incident ownership

Every Incident must have:
- a responsible owner
- a clearly stated impact
- a defined resolution path

Incidents without ownership decay into folklore.

---

## Incident lifecycle

An Incident has its own lifecycle:
- detection
- containment
- understanding
- remediation
- learning

Stopping at containment guarantees repetition.

---

## Incident as feedback

Incidents are feedback from reality.

They expose:
- flawed Intent
- missing constraints
- unexamined trade-offs
- lost architectural memory

Ignoring this feedback wastes the cost already paid.

---

## Blame is not analysis

Blame focuses on people.

Incidents originate from systems.

CIMP treats Incidents as **inputs to governance**, not as moral failures.

---

## Incident severity

Severity should reflect:
- impact magnitude
- scope of affected systems or users
- reversibility of consequences

Severity is not a measure of embarrassment.

---

## Incident and Change

Incidents do not stand alone.

Every Incident is connected to one or more prior Changes.

Understanding an Incident requires tracing:
- which Change introduced the conditions
- what Intent justified it
- which constraints were assumed

Without this link, root cause analysis becomes guesswork.

---

## Final note

Incidents are expensive.

The only way to recover their cost  
is to convert them into lasting knowledge.
