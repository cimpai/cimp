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

---

## Core concepts

CIMP is built around a small set of fundamental concepts:

- **Intent** — why a change is made
- **Scope** — what may change and what must not
- **Constraints / Invariants** — boundaries that must hold
- **Change Plan** — how intent becomes execution
- **Decision** — an explicit commitment with an owner
- **Incident** — when reality diverges from expectations
- **Remediation** — a deliberate corrective change
- **Architecture Memory** — preserved context over time

These concepts are technology-agnostic and apply equally to:
- code
- infrastructure
- data
- processes
- organizations

---

## How CIMP is used

CIMP can be adopted incrementally.

Common entry points:
- writing a **Change Plan** before risky changes
- documenting **invariants** explicitly
- treating incidents as structured inputs to future changes
- preserving key decisions instead of losing them in chat logs

No tooling is required to start.

---

## Repository structure

This repository defines the **canonical CIMP framework**:

- `docs/philosophy/` — why CIMP exists
- `docs/concepts/` — core terminology
- `docs/lifecycle/` — change and incident lifecycles
- `docs/governance/` — constraints, policies, accountability

Practical templates and real examples live in separate repositories.

---

## Related repositories

- **cimp-practices** — how to apply CIMP without tools  
- **cimp-examples** — real Change Plans and incidents  
- **cimp-cli** — tooling (planned)  
- **cimp-ui** — visualization and history (planned)

---

## Status

CIMP is under active development as an open framework.

Concepts are stable.  
Practices evolve.  
Tooling is optional.

---

## License

Apache License 2.0
