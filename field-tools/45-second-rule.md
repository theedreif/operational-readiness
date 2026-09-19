# Field Tool 002 — The 45-Second Rule

### A point-of-need test for operational learning and performance support

> **If the operator cannot find, understand, and act on the critical information within 45 seconds under field conditions, the learning system has failed at the point of need.**

The **45-Second Rule** is a design constraint for information that must support action when time, attention, and cognitive bandwidth are limited.

It does **not** mean every skill can be learned in 45 seconds.

It means that when a trained operator reaches a consequential moment and needs critical support, the system should not force that person to search through courses, dense manuals, long videos, slide decks, or unnecessary explanation before discovering what matters.

The clock is a forcing function.

## The Test

Start the clock when the operator recognizes a need for support.

Within 45 seconds, can the operator:

### 1. FIND
**Locate the relevant information.**

Can the operator reach the right procedure, limit, warning, decision aid, or job aid without hunting?

### 2. UNDERSTAND
**Recognize what matters now.**

Can the operator distinguish the critical signal, condition, constraint, or action from background information?

### 3. ACT
**Convert the information into an appropriate next move.**

Does the support make the required action, boundary, escalation path, or decision clear enough to use?

> # FIND → UNDERSTAND → ACT

If any stage fails under realistic conditions, the point-of-need design needs work.

## The 45-Second Field Check

Use this against an SOP, QRC, job aid, checklist, AI assistant, knowledge base, interface, or performance-support tool.

| Check | Question |
|---|---|
| **FIND** | Can the operator locate the critical information quickly? |
| **UNDERSTAND** | Can the operator identify what matters without interpretation overhead? |
| **ACT** | Can the operator determine the next justified action? |
| **LIMIT** | Are safety, authority, policy, or system boundaries visible? |
| **ESCALATE** | Is it obvious when the operator should stop, intervene, or seek help? |
| **EVIDENCE** | Can the operator capture or reconstruct why the action was taken? |

## Design Rules

### Put the decision before the explanation
At the point of need, the operator usually needs the **next justified action** before the background lesson.

### Make limits visible
Critical constraints should not be buried in prose.

### Design for degraded attention
Assume noise, interruption, stress, gloves, movement, poor connectivity, multiple screens, or competing priorities where those conditions are realistic.

### Remove navigation debt
Every unnecessary click, page, menu, paragraph, and search result consumes operational attention.

### Separate learning from retrieval
Training can build deep understanding over hours or days. Point-of-need support has a different job: help a prepared person retrieve and apply the right information now.

### Test in context
A document that works at a desk may fail in the field. Measure the tool where and how it is expected to be used.

## Run the Test

```text
45-SECOND FIELD TEST

TASK / DECISION:
____________________________________________

OPERATING CONDITIONS:
____________________________________________

START THE CLOCK.

FIND
Time to locate critical information: __________ seconds

UNDERSTAND
Can the operator identify what matters?
[ ] YES   [ ] NO

ACT
Can the operator identify the next justified action?
[ ] YES   [ ] NO

LIMIT
Are critical boundaries visible?
[ ] YES   [ ] NO

ESCALATE
Is the intervention / escalation condition clear?
[ ] YES   [ ] NO

TOTAL TIME TO ACTION:
__________ seconds

RESULT
[ ] SURVIVES THE FIELD
[ ] REDESIGN REQUIRED

WHAT CREATED FRICTION?
____________________________________________

WHAT SHOULD CHANGE?
____________________________________________
```

## What the Rule Is Not

The 45-Second Rule is **not** a universal human-performance threshold, a claim that complex expertise can be compressed into 45 seconds, or a substitute for training.

It is a deliberately demanding **design heuristic** for point-of-need support.

The number creates a testable constraint:

> **Can the system deliver usable support at the speed of the operating problem?**

## Relationship to Judgment at the Edge

The 45-Second Rule helps deliver information quickly enough for the operator to enter the decision loop:

> **SIGNAL → CONDITION → LIMIT → DECISION → EVIDENCE**

The [Decision Field Card](https://github.com/theedreif/judgment-at-the-edge/tree/main/decision-tools) structures the decision.

The 45-Second Rule tests whether the supporting information can reach the operator in time to matter.

## The Standard

A learning system should not merely contain the correct information.

It should make the critical information **retrievable, comprehensible, and actionable at the point of need**.

> **If it cannot survive the field, it does not count.**

---

**Field Tool 002 · The 45-Second Rule · v1.0**  
Part of the [Ed Reif Operational Readiness](https://github.com/theedreif/operational-readiness) field toolkit.
