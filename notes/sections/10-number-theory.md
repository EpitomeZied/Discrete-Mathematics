---
title: DM S10 — Number theory
type: note
topic: teaching
subject: Discrete Math
section: S10
created: 2026-09-25
tags: [ta, teaching, section, discrete-math]
---
# S10 — Number theory

> [!NOTE]
> Discrete Math, section 10. Index: [Discrete Math Sections](../section-plan.md) · questions: [Discrete Math Question Bank](../../practice/question-bank.md) · teaching notes: [Discrete Math Playbook](../teaching-playbook.md).

**One idea to land:** `a ≡ b (mod n)` means `n | (a - b)` — one definition, and everything (arithmetic, inverses, Euclid) unrolls from it.

**Board:**
1. Divisibility from the definition: `a | b` means `b = ak`. Prove a small transitivity claim straight from it.
2. Division algorithm, uniqueness stated.
3. Euclid's algorithm by hand on a pair, then extended Euclid to get the Bézout coefficients — kept as a table, not as prose.
4. Modular arithmetic: what you may do (add, multiply), and the trap (division needs an inverse, which needs gcd = 1).

**They compute/prove:** gcd and Bézout for a given pair; solve `7x ≡ 3 (mod 11)`; prove the sum of two odds is even, from definitions only.

**Mistakes I expect:** cancelling a common factor mod n without checking gcd; treating mod as only the remainder operator; arithmetic errors in extended Euclid; forgetting that congruence classes, not numbers, are the objects.

-----
[← S09](09-recurrences.md) · [All sections](../section-plan.md) · [S11 →](11-graphs-and-trees.md)
