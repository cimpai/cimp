# CIMP

**CIMP (Change Intelligence Management Platform)** is a governance framework for designing, evaluating, and executing changes in complex systems.

CIMP sits between **intent** and **execution**.

It does not replace engineering practices, tools, or teams.  
It makes change **intentional, accountable, and observable**.

---

## Why CIMP exists

Modern systems fail not because of bad code, but because of **unmanaged change**.

Typical symptoms:
- changes are made without explicit intent
- risks are known but undocumented
- constraints exist only “in people’s heads”
- incidents are investigated, but lessons are lost
- decisions disappear after the PR is merged

CIMP exists to address this gap.

It provides a **shared language and structure** for changes — before, during, and after they happen.

---

## What CIMP is

CIMP is:

- a **conceptual framework**
- a **set of governance principles**
- a **shared vocabulary** for change
- a **lifecycle model** for intent, execution, and incidents
- a way to preserve **architectural memory over time**

CIMP can be used:
- without AI
- without new tools
- without changing your tech stack

---

## What CIMP is not

CIMP is **not**:
- a CI/CD system
- a project management tool
- a ticketing system
- a code generator
- a replacement for engineering judgment

CIMP does not automate decisions.  
It makes decisions **explicit and traceable**.

See:  
👉 [`docs/philosophy/what-cimp-is-not.md`](docs/philosophy/what-cimp-is-not.md)

---

## Related Work & Inspiration

CIMP builds upon and synthesizes ideas from established practices, including:

- **Architecture Decision Records (ADR)** — explicit recording of architectural decisions  
  ([Michael Nygard's original ADR format](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions))
- **RFC processes** — structured change proposals and review  
  (inspired by IETF RFC process and internal RFC practices at tech companies)
- **Post-mortem culture** — learning from incidents and failures  
  (practices from SRE and incident response communities)
- **Design by Contract / Invariant-driven design** — defining and protecting system boundaries  
  (concepts from Eiffel, formal methods, and constraint-based design)

CIMP's contribution is not the invention of new practices,  
but the **unified framework** that connects Intent, Change, Decisions,
Incidents, and Architecture Memory into a single governance system.

---

## Core concepts

CIMP is built around a small set of fundamental concepts.

Each concept is intentionally minimal and explicitly defined.

- **Intent** — why a change exists  
  [`docs/concepts/intent.md`](docs/concepts/intent.md)

- **Scope** — what may change and what must not  
  [`docs/concepts/scope.md`](docs/concepts/scope.md)

- **Constraints / Invariants** — boundaries that must hold  
  [`docs/concepts/constraints.md`](docs/concepts/constraints.md)

- **Change** — a deliberate modification that alters behavior or risk  
  [`docs/concepts/change.md`](docs/concepts/change.md)

- **Decision** — an explicit commitment under uncertainty  
  [`docs/concepts/decisions.md`](docs/concepts/decisions.md)

- **Incident** — a significant divergence from expected behavior  
  [`docs/concepts/incident.md`](docs/concepts/incident.md)

- **Remediation** — corrective action treated as a Change  
  [`docs/concepts/remediation.md`](docs/concepts/remediation.md)

- **Architecture Memory** — preserved reasoning over time  
  [`docs/concepts/architecture-memory.md`](docs/concepts/architecture-memory.md)

These concepts apply equally to:
- code
- infrastructure
- data
- processes
- organizations

---

## Lifecycles

CIMP defines two symmetric lifecycles.

They describe how change and failure evolve over time.

- **Change Lifecycle** — from Intent to consequences  
  [`docs/lifecycle/change-lifecycle.md`](docs/lifecycle/change-lifecycle.md)

- **Incident Lifecycle** — from emergence to memory  
  [`docs/lifecycle/incident-lifecycle.md`](docs/lifecycle/incident-lifecycle.md)

---

## Why changes fail

CIMP is grounded in analysis, not prescription.

A detailed explanation of structural failure modes can be found here:

👉 [`docs/philosophy/why-changes-fail.md`](docs/philosophy/why-changes-fail.md)

---

## Governance

CIMP prioritizes stability and clarity over speed.

The governance model defines how the framework evolves:

👉 [`GOVERNANCE.md`](GOVERNANCE.md)

---

## Practical application

CIMP does not require tooling.

Practical templates and usage patterns live in a separate repository:

👉 [`cimp-practices`](https://github.com/cimpai/cimp-practices)

This repository is **not part of the canon** and does not define or modify canonical concepts.

---

## Status

CIMP is under active development as an open framework.

- Concepts are stable
- Practices evolve
- Tooling is optional

---

## License

Apache License 2.0
