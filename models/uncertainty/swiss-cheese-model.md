---
type: DecisionModel
title: Swiss Cheese Model
description: How we get things wrong — accidents and failures as aligned holes in layered defenses.
tags: [decision-model, uncertainty, risk, failure, systems]
family: uncertainty
timestamp: 2026-07-18T13:00:00Z
status: ready
---

# Overview

The Swiss Cheese Model explains accidents and organizational failure as **several imperfect layers of defense**. Each layer (procedure, training, technology, supervision) has holes; disaster happens when the holes **line up** and a hazard passes through every slice.

Attributed to James Reason: the point is not “who blundered,” but how **latent conditions** and **active failures** combine.

### Diagram

```text
  Hazard ---> [Layer1 ##] [Layer2 # #] [Layer3 ## #] ---> Incident
                    holes align ---------------->
```

# When to use

- Something went wrong despite “checks” and good intentions.
- You are designing safety, quality, or compliance and temptation is to add one more rule.
- Blame is stuck on the last person in the chain; you need a systemic view.
- Near-misses keep recurring in different guises.

Skip it when the question is pure uncertainty taxonomy (use [Rumsfeld Matrix](/models/uncertainty/rumsfeld-matrix.md)) or when you need interpersonal conflict craft (use [Conflict Resolution](/models/relate/conflict-resolution-model.md)).

# How it works

Imagine stacked slices of Swiss cheese between a **hazard** and a **harm**:

1. Each slice is a **defense** — policy, review, automated interlock, second pair of eyes, culture of speaking up.
2. Each slice has **holes** — gaps, fatigue, conflicting goals, outdated assumptions, workarounds.
3. Holes move over time; most of the time they do **not** align.
4. When they align, the hazard gets through → incident, outage, scandal, or quiet quality failure.

### Two kinds of failure

| Type | What it is | Example |
|------|------------|---------|
| **Active failures** | Unsafe acts at the sharp end | Wrong click, skipped check, misread signal |
| **Latent conditions** | Weaknesses built into the system | Understaffing, bad UI, conflicting KPIs, missing training |

### Questions to ask after a miss

1. Which **layers** were supposed to stop this?
2. Which **holes** existed in each — and how long had they been there?
3. What **pressures** made workarounds rational?
4. What would **add a new layer** vs **shrink holes** in existing ones?

### How to act

1. **Map the layers** for the process (don’t stop at the last actor).
2. **Fix latent conditions** first — they create many future holes.
3. Prefer **diverse** defenses (different people, methods, technologies) so holes are less correlated.
4. Treat near-misses as free rehearsals: the cheese already lined up; luck intervened.

### Practice tip

In a postmortem, ban “human error” as a root cause until you have named at least three layers that failed to catch it. If you only punish the last person, the holes stay.

### Facilitation steps

1. **Incident** — What failure or near-miss are we examining?
2. **Layers** — List the defenses that should have stopped it (process, people, tech, culture).
3. **Holes** — Where did each layer have a hole this time?
4. **Alignment** — How did the holes line up?
5. **Fix** — Which layer gets a stronger independent barrier next (not only blame)?

# Relations

- Family: [Face Uncertainty](/models/uncertainty/index.md)
- Catalog: [Decision jobs](/index.md)
- Related: [Rumsfeld Matrix](/models/uncertainty/rumsfeld-matrix.md) — classify what you knew vs didn’t before the holes aligned
- Related: [Black Swan Theory](/models/uncertainty/black-swan-theory.md) — rare paths through the cheese that rewrite expectations
- Related: [Double-Loop Learning](/models/learn/double-loop-learning.md) — change governing rules that create latent holes
- Related: [Feedback Analysis](/models/learn/feedback-analysis.md) — personal pattern of where your defenses fail
- Contrast: [Black Box Model](/models/uncertainty/black-box-model.md) — Swiss Cheese opens the box; Black Box accepts opacity

# Citations

[1] James Reason — Swiss cheese model of accident causation (aligned holes in layered defenses).

[2] Used widely in safety science, aviation, and healthcare quality improvement.
