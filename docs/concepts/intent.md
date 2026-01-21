# Intent

Intent describes **why a change exists**.

It is not a description of work.  
It is not a solution.  
It is not a justification after the fact.

A valid Intent can be evaluated **before** execution and **revisited after**.

---

## What Intent is

Intent defines:
- the problem being addressed
- the outcome that would make the change successful
- the reason this change is necessary *now*

Intent exists **before** design, implementation, or execution.

---

## What Intent is not

Intent is not:
- a list of tasks
- a technical solution
- a restatement of the implementation
- a vague improvement goal

Examples of invalid intent:
- “Improve performance”
- “Refactor this module”
- “Clean things up”
- “Make it more reliable”

These describe activity, not intent.

---

## Properties of a valid Intent

A valid Intent has the following properties.

### 1. It is falsifiable

Intent must be testable in principle.

After the change, it must be possible to say:
- the intent was achieved
- the intent was partially achieved
- the intent was not achieved

If failure is undefined, success is meaningless.

---

### 2. It is outcome-oriented

Intent describes outcomes, not actions.

Compare:

> ❌ “Introduce caching for user profiles”

> ✅ “Reduce p95 latency of user profile reads from ~450ms to under 200ms under peak load”

The second can be evaluated.  
The first cannot.

---

### 3. It has a time horizon

Intent exists in time.

It must answer:
- why this change matters *now*
- what happens if it is delayed

Intent without urgency is indistinguishable from backlog noise.

---

### 4. It acknowledges trade-offs

Every meaningful change has costs.

Intent must acknowledge at least one trade-off:
- increased complexity
- operational risk
- maintenance burden
- performance in other dimensions

Ignoring trade-offs does not remove them.

---

### 5. It has an owner

Intent must have a responsible owner.

This does not mean a single implementer.  
It means a single accountable decision-maker.

Without ownership, intent decays into consensus.

---

## Intent vs solution

Intent should remain stable even if the solution changes.

If a solution changes:
- the Intent usually does not
- unless the problem definition itself was wrong

If changing the solution requires rewriting the Intent,  
the Intent was likely a solution description.

---

## Intent in practice

A minimal Intent statement usually fits in **3–6 lines**.

Example:

> **Intent**  
> Reduce billing reconciliation errors caused by delayed invoice generation.  
> Success is defined as reducing manual correction cases from ~12 per week to zero.  
> This change is required before onboarding new enterprise accounts next quarter.  
> Trade-off: increased complexity in the invoice pipeline.  
> Owner: Billing platform lead.

This is sufficient.

---

## Reviewing Intent

Before accepting a change, ask:
- Can this intent be proven wrong?
- Would two reasonable people interpret success the same way?
- Is the urgency real or implied?
- Are trade-offs acknowledged?

If these questions cannot be answered,  
the change is not ready.

---

## Intent and incidents

When an incident occurs, Intent becomes evidence.

It allows you to ask:
- Did the change achieve its stated goal?
- Were the risks acknowledged?
- Was the trade-off acceptable in hindsight?

Without Intent, post-incident analysis becomes speculation.

---

## Final note

Intent slows the start of change.

It speeds up everything that follows.
``
