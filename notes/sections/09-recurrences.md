---
title: DM S09 — Recurrences
type: note
topic: teaching
subject: Discrete Math
section: S09
created: 2026-09-25
tags: [ta, teaching, section, discrete-math]
---
# S09 — Recurrences

> [!NOTE]
> Discrete Math, section 09. Index: [Discrete Math Sections](../section-plan.md) · questions: [Discrete Math Question Bank](../../practice/question-bank.md) · teaching notes: [Discrete Math Playbook](../teaching-playbook.md).

**One idea to land:** a recurrence is a *definition*; a closed form is a *theorem* — and induction is how you get from one to the other.

**Board:**
1. Set up a recurrence from a word problem (rabbits, tilings, or towers of Hanoi — reuse whatever the lecture used).
2. Unroll the first four terms, spot the pattern, guess the closed form, then **prove it by induction** — explicitly connecting back to S04.
3. Solve a linear homogeneous recurrence via the characteristic equation; do the repeated-root case if the syllabus covers it.

**They solve:** `a_n = 2a_{n-1} + 1`, `a_0 = 1`; then a second-order one, verified on n = 0..3.

**Mistakes I expect:** ignoring the initial conditions; guessing the closed form and never proving it; arithmetic slips in the characteristic equation; dropping one root's coefficient.

-----
[← S08](08-counting.md) · [All sections](../section-plan.md) · [S10 →](10-number-theory.md)
