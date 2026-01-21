# Incident Lifecycle

An Incident is not a moment of failure.

It has a lifecycle.

Understanding this lifecycle is essential to learning from incidents rather than merely surviving them.

---

## Overview

The CIMP Incident Lifecycle describes how an Incident:
- emerges from prior Changes
- is detected and contained
- is understood
- leads to remediation
- becomes part of system memory

The lifecycle does not end when the system stabilizes.

---

## 1. Emergence

Incidents rarely begin at detection.

They emerge when:
- assumptions become invalid
- risks materialize
- constraints are violated
- accumulated changes interact unexpectedly

Emergence often predates detection by days or weeks.

---

## 2. Detection

Detection is the moment the Incident becomes visible.

Detection may come from:
- monitoring and alerts
- user reports
- audits or reviews
- secondary effects

Lack of detection does not mean lack of incident.

---

## 3. Containment

Containment limits impact.

Typical containment actions:
- disabling features
- rolling back changes
- isolating components
- applying temporary fixes

Containment is not remediation.

Its goal is to stop harm, not to solve the problem.

---

## 4. Stabilization

Stabilization restores acceptable system behavior.

At this stage:
- user impact is reduced or eliminated
- operational pressure decreases
- short-term safety is achieved

Stabilization creates space for understanding.

---

## 5. Understanding

Understanding explains **why** the Incident occurred.

This includes:
- tracing the Incident to prior Changes
- examining original Intent
- identifying violated assumptions
- understanding why risks were accepted

Skipping this step guarantees recurrence.

---

## 6. Remediation

Remediation addresses root causes.

Remediation:
- is itself a Change
- requires explicit Intent
- introduces new trade-offs

Treating remediation as a shortcut undermines learning.

---

## 7. Verification

After remediation, the system must be verified.

Verification asks:
- did the remediation work?
- were new risks introduced?
- are assumptions now valid?

Verification closes the technical loop.

---

## 8. Memory integration

An Incident is not resolved until it is remembered.

This includes:
- recorded Incident analysis
- linked Changes and Intent
- documented lessons
- updates to constraints or practices

Without memory, resolution is temporary.

---

## Lifecycle is not linear

In practice:
- containment and remediation may overlap
- understanding may continue after stabilization
- new Incidents may emerge during remediation

The lifecycle is conceptual, not procedural.

---

## Governance implication

Governing Incidents means governing their lifecycle.

Focusing only on:
- detection
- containment
- uptime metrics

ignores where most learning is lost.

---

## Final note

Incidents reveal the truth about systems.

Surviving an Incident is easy.

Learning from it requires structure.
