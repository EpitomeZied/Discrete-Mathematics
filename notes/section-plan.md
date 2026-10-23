---
title: Discrete Math Sections
type: note
topic: teaching
created: 2026-09-25
tags: [ta, teaching, discrete-math]
---
# Discrete Math — Sections

> [!NOTE]
> Delivery plan, one block per section: the idea to land, what goes on the board, the proof I work, what they write, and the mistakes I know are coming.
> Companions: [Discrete Math Playbook](teaching-playbook.md) · [Discrete Math Question Bank](../practice/question-bank.md) · the general teaching playbook (local reference).

## Contents
- [How I run a section](#how-i-run-a-section)
- [Section map](#section-map)
- [S00 — What a proof is](sections/00-what-a-proof-is.md)
- [S01 — Propositional logic](sections/01-propositional-logic.md)
- [S02 — Predicates and quantifiers](sections/02-predicates-and-quantifiers.md)
- [S03 — Proof methods](sections/03-proof-methods.md)
- [S04 — Induction](sections/04-induction.md)
- [S05 — Sets](sections/05-sets.md)
- [S06 — Functions](sections/06-functions.md)
- [S07 — Relations](sections/07-relations.md)
- [S08 — Counting](sections/08-counting.md)
- [S09 — Recurrences](sections/09-recurrences.md)
- [S10 — Number theory](sections/10-number-theory.md)
- [S11 — Graphs and trees](sections/11-graphs-and-trees.md)
- [S12 — Review: the proof-method chooser](sections/12-review-the-proof-method-chooser.md)
- [Stretch and fallback per section](#stretch-and-fallback-per-section)
- [Prep checklist — the night before](#prep-checklist--the-night-before)
- [Reusable closing drills](#reusable-closing-drills)

-----

## How I run a section

| Time | Part | What I do |
|---|---|---|
| 0–5 | Recap | 3 questions on last section, cold-called, never graded |
| 5–15 | Skeleton | The method's fixed shape on the board, before any content |
| 15–30 | I prove | One theorem, written in full, narrating *why* each line is allowed |
| 30–45 | They prove | A near-twin problem; I walk the room instead of talking |
| 45–50 | Close | The one-sentence takeaway + what to read before next week |

Rules I hold myself to:
- **Write in full sentences on the board.** They copy my style; symbol soup produces symbol soup.
- **Name the justification of every line out loud** — "by the hypothesis", "by definition of even", "by the previous case".
- **Be wrong on purpose once per section** and let them catch it. In this subject, hunting flaws *is* the skill.
- **Never say "obviously".** If it is obvious, it takes one line, so write the line.
- **Small cases first.** n = 1, 2, 3 before any general argument.

-----

## Section map

| # | Section | Board focus | They leave able to |
|---|---|---|---|
| [00](sections/00-what-a-proof-is.md) | What a proof is | argument vs answer | tell a complete argument from a plausible one |
| [01](sections/01-propositional-logic.md) | Propositional logic | implication and its relatives | negate and rewrite any compound statement |
| [02](sections/02-predicates-and-quantifiers.md) | Quantifiers | ∀∃ order, negation | negate a quantified statement mechanically |
| [03](sections/03-proof-methods.md) | Proof methods | the four skeletons | pick a method and open the proof correctly |
| [04](sections/04-induction.md) | Induction | hypothesis actually used | write a complete induction, including strong |
| [05](sections/05-sets.md) | Sets | proving set equality | prove A ⊆ B by taking an arbitrary element |
| [06](sections/06-functions.md) | Functions | injective / surjective | prove or disprove a function is a bijection |
| [07](sections/07-relations.md) | Relations | equivalence vs order | verify three properties and find the classes |
| [08](sections/08-counting.md) | Counting | choose the model first | count the same thing two ways and agree |
| [09](sections/09-recurrences.md) | Recurrences | pattern → closed form | solve a linear recurrence and verify it |
| [10](sections/10-number-theory.md) | Number theory | divisibility, mod, gcd | run Euclid and solve a congruence |
| [11](sections/11-graphs-and-trees.md) | Graphs and trees | model the problem as a graph | prove a small graph property |
| [12](sections/12-review-the-proof-method-chooser.md) | Review | choosing the method | read an unfamiliar claim and start correctly |

-----

## The sections

One file each — open the file for the section you are about to teach.

- **S00** — [What a proof is](sections/00-what-a-proof-is.md)
- **S01** — [Propositional logic](sections/01-propositional-logic.md)
- **S02** — [Predicates and quantifiers](sections/02-predicates-and-quantifiers.md)
- **S03** — [Proof methods](sections/03-proof-methods.md)
- **S04** — [Induction](sections/04-induction.md)
- **S05** — [Sets](sections/05-sets.md)
- **S06** — [Functions](sections/06-functions.md)
- **S07** — [Relations](sections/07-relations.md)
- **S08** — [Counting](sections/08-counting.md)
- **S09** — [Recurrences](sections/09-recurrences.md)
- **S10** — [Number theory](sections/10-number-theory.md)
- **S11** — [Graphs and trees](sections/11-graphs-and-trees.md)
- **S12** — [Review: the proof-method chooser](sections/12-review-the-proof-method-chooser.md)

-----

## Stretch and fallback per section

| # | If we are ahead | If we are behind |
|---|---|---|
| 01 | NAND completeness; circuits | the → truth table and the contrapositive |
| 02 | nested quantifiers over two domains | one negation, done slowly |
| 03 | a proof needing two methods combined | the four skeletons only |
| 04 | strong induction on a recursive structure | one full write-up, three parts labeled |
| 05 | Russell's paradox as a curiosity | one double-inclusion proof |
| 06 | cardinality, countability, diagonalization | injective/surjective templates only |
| 07 | closures; equivalence ⇔ partition proof | the three checks on one small relation |
| 08 | stars and bars; derangements | permutation vs combination decision |
| 09 | non-homogeneous recurrences | unroll, guess, verify on small n |
| 10 | CRT; Fermat's little theorem | Euclid by hand |
| 11 | planarity, Euler's formula, colouring | handshake lemma + one drawing |

-----

## Prep checklist — the night before

- [ ] Write out the proof I will present, in full, by hand. If my own write-up has a gap, the board will expose it.
- [ ] Choose the *deliberate* flaw for the flaw-hunt and rehearse "discovering" it.
- [ ] Three recap questions written down, not improvised.
- [ ] The small cases I will do first (n = 1, 2, 3) computed in advance.
- [ ] Their exercise solved under time — if it takes me 6 minutes it will take them 25.
- [ ] Board layout sketched: skeleton top-left, proof centre, justifications in the right margin.

-----

## Reusable closing drills

- "Negate this statement, out loud, in words."
- "What would a counterexample have to look like? Describe its shape."
- "Which line used the hypothesis?"
- "Is this a definition, a theorem, or an assumption?"
- "Why is that step allowed?" (asked about a step that is, in fact, fine — they must justify success too)
- "Count it a second way and tell me if you still believe it."
