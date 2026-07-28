---
type: Comparison
title: Risk and ignorance
description: When to use Rumsfeld, Black Swan, Swiss Cheese, or Black Box.
tags: [comparison, uncertainty]
families: [uncertainty]
status: ready
timestamp: 2026-07-27T20:00:00Z
---

# Overview

Not all “we don’t know” is the same. Separate **mapped ignorance**, **rare extremes**, **layered operational failure**, and **opaque systems**.

# When to use which

| Situation | Use | Core move |
|-----------|-----|-----------|
| Sort what you know / don’t / don’t know you don’t | [Rumsfeld Matrix](/models/uncertainty/rumsfeld-matrix.md) | Inventory knowledge; hunt unknown unknowns carefully |
| Rare, high-impact, retrospective-obvious events | [Black Swan](/models/uncertainty/black-swan-theory.md) | Don’t overfit past; build robustness / optionality |
| Accidents from aligned holes in defenses | [Swiss Cheese](/models/uncertainty/swiss-cheese-model.md) | Stack independent barriers; learn near-misses |
| Must act on a system you can’t open | [Black Box](/models/uncertainty/black-box-model.md) | Govern via I/O tests, trust limits, contracts |

# Suggested sequences

1. **New domain** → Rumsfeld → Black Box for subsystems you won’t open.  
2. **Safety / ops failure** → Swiss Cheese → Double-Loop if assumptions were wrong ([learn](/models/learn/double-loop-learning.md)).  
3. **Strategy after a shock** → Black Swan → Consequences / Stop Rule for commitments.  
4. **Vendor / AI / opaque process** → Black Box → Expectation Management with counterparts.

# Relations

- Family hub: [Face Uncertainty](/models/uncertainty/index.md)
- Path: [Act under ignorance](/models/paths/act-under-ignorance.md) — multi-step locate for new domains and opaque risk
- Related comparison: [Prioritization lenses](prioritization-lenses.md) — scarce resources under risk
