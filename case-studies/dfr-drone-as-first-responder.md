# DFR — When Everything Works Except Certainty

> **Engagement status: Independent analysis.** Written by Ed Reif on his own
> initiative from publicly documented information about drone-as-first-responder
> workflows and the Skydio–Axon integration. See [PROVENANCE.md](../PROVENANCE.md).

## The situation, as publicly documented

Drone as First Responder is a public-safety workflow in which an autonomous aircraft launches to an incident ahead of ground units. Capture and evidence workflows solve important engineering problems. The remaining questions include human judgment.

## Problem one — the decision the autonomy cannot make

The aircraft arrives. The feed is clean. Every system reports nominal. And the operator still has to answer a question the platform has no opinion about: given what I am now looking at, should this mission continue in this form?

That is the thesis of [Judgment at the Edge](../concepts/judgment-at-the-edge.md):

> **The aircraft can continue. That does not mean the mission should.**

The DFR decision is made under a live feed, a running clock, an incomplete picture, an audience, and a record that may be examined later.

### The Mission Loop

**NOTICE → INTEGRATE → PRIORITISE → DECIDE → DEFEND**

PRIORITISE is where a technically correct call and a wrong mission call can diverge. DEFEND is where the operator preserves the evidence that justified the decision at the time.

## Problem two — twenty seconds to launch, six months to find it

The second problem is downstream: information can be captured correctly yet remain difficult to retrieve later if it is indexed by the producing subsystem rather than by the language of the person searching for it.

> **Publication is not availability.**

A bounded audit can produce:
1. A controlled vocabulary
2. A metadata schema indexed by observed symptom
3. Rewritten titles and descriptions for high-traffic assets
4. A search-log and zero-result baseline
5. An ownership register with review triggers

## Concepts applied

[Judgment at the Edge](../concepts/judgment-at-the-edge.md) ·
[The 45-Second Rule](../concepts/45-second-rule.md) ·
[Trust Calibration](../concepts/trust-calibration.md) ·
[Telemetry Over Testing](../concepts/telemetry-over-testing.md) ·
Mission Loop · Exposure Register

## Artefacts

- *Twenty Seconds to Launch. Six Months to Find It.*
- The DFR series on the Judgment at the Edge line — *When Everything Works Except Certainty*

The aircraft is autonomous. The knowledge isn't. That's the job.
