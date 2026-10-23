---
title: DM S05 — Sets
type: note
topic: teaching
subject: Discrete Math
section: S05
created: 2026-09-25
tags: [ta, teaching, section, discrete-math]
---
# S05 — Sets

> [!NOTE]
> Discrete Math, section 05. Index: [Discrete Math Sections](../section-plan.md) · questions: [Discrete Math Question Bank](../../practice/question-bank.md) · teaching notes: [Discrete Math Playbook](../teaching-playbook.md).

**One idea to land:** set equality is *two subset proofs*, and a subset proof always starts "let x ∈ A be arbitrary."

**Board:**
1. ∈ vs ⊆ — the most persistent confusion of the term. `{1} ∈ {{1}}` and `{1} ⊆ {1,2}`; write both, ask for the difference in words.
2. Prove `A ∩ (B ∪ C) = (A ∩ B) ∪ (A ∩ C)` by double inclusion, element-wise, each line justified by a logic law from S01. Say the connection aloud: **set identities are propositional logic wearing different notation.**
3. Power set of a 3-element set, and why `|P(S)| = 2^|S|` (a counting argument — forward reference to S08).
4. Venn diagrams: fine for intuition, not a proof. Say it once and hold it.

**They prove:** `A \ (B ∩ C) = (A \ B) ∪ (A \ C)`.

**Mistakes I expect:** mixing ∈ and ⊆; proving one inclusion and stopping; using a Venn diagram as the proof; forgetting that ∅ ⊆ every set.

-----
[← S04](04-induction.md) · [All sections](../section-plan.md) · [S06 →](06-functions.md)
