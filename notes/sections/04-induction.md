---
title: DM S04 — Induction
type: note
topic: teaching
subject: Discrete Math
section: S04
created: 2026-09-25
tags: [ta, teaching, section, discrete-math]
---
# S04 — Induction

> [!NOTE]
> Discrete Math, section 04. Index: [Discrete Math Sections](../section-plan.md) · questions: [Discrete Math Question Bank](../../practice/question-bank.md) · teaching notes: [Discrete Math Playbook](../teaching-playbook.md).

**One idea to land:** the step must **use** the hypothesis. An induction step that proves `k+1` from scratch is not an induction.

**Board:**
1. Dominoes once, briefly, then never again — the metaphor is a hook, not an argument.
2. Full write-up of `1 + 2 + … + n = n(n+1)/2` with the three parts labeled, and the *exact* line where the hypothesis is substituted circled in a second colour.
3. Strong induction, motivated by a claim ordinary induction cannot reach (every n ≥ 2 has a prime factor).
4. A false "proof" by induction with a broken base case — they find it.

**They prove:** `2^n > n` for n ≥ 1, then a divisibility claim (`3 | n³ - n`).

**Mistakes I expect:** no base case, or a base case at the wrong n; "assume it is true for all n" (that is the theorem, not the hypothesis); a step that never touches the hypothesis; strong vs ordinary confusion.

**Close:** "Show me the line where you used the hypothesis. No such line, no induction."

-----
[← S03](03-proof-methods.md) · [All sections](../section-plan.md) · [S05 →](05-sets.md)
