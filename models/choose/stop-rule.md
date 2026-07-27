---
type: DecisionModel
title: Stop Rule
description: When to revise a decision — pre-commit the signals that mean “change course,” not “try harder.”
tags: [decision-model, choose, revision, commitment]
family: choose
timestamp: 2026-07-18T13:00:00Z
status: ready
---

# Overview

A **Stop Rule** answers: *When should I revise or abandon a decision I already made?* Without one, sunk costs and pride keep you on a failing path; with a vague one, you quit at the first discomfort. The model asks you to define exit and revision criteria *in advance*, while you are still clear-headed.

Stopping is not failure by default — it is deciding again with new information.

### Diagram

```text
  Commit → track signals → [stop rule fires?] --yes--> revise/exit
                              |
                             no
                              v
                           continue
```

# When to use

- You are about to commit time, money, or reputation to a plan, bet, or project.
- Past you tends to escalate commitments that are clearly underperforming.
- Teams need a shared definition of “pivot” vs “persist.”
- You want to distinguish temporary pain from true disconfirming evidence.

Skip it when you have not decided yet (use [Yes/No Rule](/models/choose/yes-no-rule.md) or [Consequences Model](/models/choose/consequences-model.md) first), or when you are only sorting daily tasks (use [Eisenhower Matrix](/models/prioritize/eisenhower-matrix.md)).

# How it works

### 1. Separate pain from signal

Before starting, write what would count as:

- **Expected friction** — hard but normal (learning curve, early criticism, slow week)
- **Stop / revise triggers** — evidence the plan’s premise is wrong

If everything “feels hard” qualifies as a stop, the rule is useless.

### 2. Define the rule in measurable terms

Good stop rules name **what**, **how much**, and **by when**:

1. **Metric or event** — revenue, health, relationship quality, error rate, legal risk, key hire declined…
2. **Threshold** — below X for Y periods; two independent warnings; a hard constraint broken
3. **Response** — pause, revise scope, switch option, or exit fully

Example: “If after 8 weeks we have fewer than 10 paying users *and* no clear pipeline, we stop the launch plan and run a postmortem — we do not ‘give it one more month’ by default.”

### 3. Review on a schedule

Put the stop-rule check on the calendar. Do not wait for a crisis mood. At each check: *trigger hit?* If yes, revise; if no, continue without renegotiating the rule casually.

### Practice tip

Write the stop rule where the original decision lives (doc, ticket, notebook). Revisiting the *same* sentence beats reinventing criteria when emotions are high. Pair with [Feedback Analysis](/models/learn/feedback-analysis.md) so revision is learning, not self-blame.

### Facilitation steps

1. **Commitment** — What decision or plan are you already in that might need revision?
2. **Pain vs signal** — What would feel hard but still be “try harder,” vs a true stop signal?
3. **Rule** — Write a pre-commit stop rule in measurable terms (metric, date, or event).
4. **Review** — When will you check the rule (calendar)?
5. **Obey** — If the signal already fires today, what changes now?

# Relations

- Family: [Choose & Commit](/models/choose/index.md)
- Catalog: [Decision jobs](/index.md)
- Related: [Eisenhower Matrix](/models/prioritize/eisenhower-matrix.md) — re-prioritize work after you revise the plan
- Related: [Feedback Analysis](/models/learn/feedback-analysis.md) — evaluate outcomes so stop rules improve over time
- Related: [Project Portfolio](/models/prioritize/project-portfolio.md) — kill or pause initiatives without losing overview
- Related: [Consequences Model](/models/choose/consequences-model.md) — decide early; Stop Rule governs when early bets change
- Related: [SMART Model](/models/prioritize/smart-model.md) — goals with checkpoints make stop rules easier to write
- Contrast: [Yes/No Rule](/models/choose/yes-no-rule.md) — making the call; Stop Rule is about *unmaking* or remaking it later
- Contrast: [Unconscious Thought Theory](/models/choose/unconscious-thought-theory.md) — forming a judgment; Stop Rule monitors the judgment after commitment

# Citations

[1] Precommitment and stopping rules in decision theory and behavioral design — define exit criteria before sunk-cost pressure peaks.

[2] Related: “kill criteria” in project portfolio management and scientific stopping rules as practical cousins.
