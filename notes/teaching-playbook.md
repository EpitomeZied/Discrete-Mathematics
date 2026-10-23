---
title: Discrete Math Playbook
type: note
topic: teaching
created: 2026-09-25
tags: [ta, teaching, discrete-math]
---
# Discrete Math — Playbook delta

> [!NOTE]
> The universal TA method lives in the general teaching playbook (local reference). This file is only what is **different about this subject**.

## What makes this subject hard for them

They have spent twelve years being graded on *answers*. This course grades **arguments**, and nobody has ever taught them what a complete argument looks like. That gap — not the content — is what fails people.

- **The answer is not the point.** "Prove √2 is irrational" has a known answer; the marks live in the justification. Say this in week one and keep saying it.
- **No numbers to hide behind.** In calculus a wrong step produces a wrong number they can notice. Here a wrong step produces a sentence that *sounds fine*. So: read proofs aloud, word by word, and ask "is that sentence true?"
- **Quantifiers are a foreign language.** ∀∃ order, negation, vacuous truth — treat these as language instruction, with drills, not as one lecture.

## Section-specific moves

- **Proof skeletons on the board, before content.** For each method, the fixed opening and closing lines:
  - *Direct:* "Assume P. … Therefore Q. ∎"
  - *Contrapositive:* "We prove ¬Q → ¬P. Assume ¬Q. …"
  - *Contradiction:* "Suppose, for contradiction, P ∧ ¬Q. … contradiction. ∎"
  - *Induction:* "Base: n = … Hypothesis: assume for n = k. Step: show for k+1 **using the hypothesis**."
  A student who can write the skeleton unprompted is halfway to every proof on the exam.
- **Two-column proofs early** — claim on the left, justification on the right. It forces them to name *why* each line follows. Drop the scaffolding around week 5.
- **Wrong proofs as material.** I put a flawed proof on the board and they hunt the flaw. Far more effective than another correct proof, and it removes the shame from being wrong.
- **Truth tables are a machine, not an insight.** Do two by hand, then move to reasoning about logical equivalence — otherwise they will try to truth-table a 5-variable exam question and run out of time.
- **Count twice, two ways.** Every combinatorics answer gets a second derivation or a small-case sanity check (n = 2, n = 3 by hand). This catches almost every counting error they make.
- **Draw the graph.** Graph theory answers with no drawing are guesses.

## Grading, subject-specific

- **Grade structure first, then correctness.** A proof with the right skeleton and one wrong algebraic line is much closer to correct than a pile of true statements with no direction. Mark it that way and tell them why.
- **The three standing deductions**, published in advance:
  - Induction step that never *uses* the hypothesis → the step is not worth full marks, however true the algebra.
  - Assuming what is being proved (circularity) → no marks for the affected step; name it explicitly in the comment.
  - Proof by example for a universal claim → no marks, every time, with "one case is not ∀" written on it.
- **Counterexamples must be verified, not asserted.** A claimed counterexample with no check is half an answer.
- **Notation abuse:** flag it, cost little at first, then hold the line after the midterm. `⊂` vs `∈`, `⇒` used as "and then", missing quantifiers.

## The question I ask all term

> "Which quantifier is doing the work in this statement, and what would a counterexample have to look like?"

If they can answer that, they can read any theorem in any later course.

## Misconception log — seeded

Format and rules in the general teaching playbook (local reference). Add a row the same day it happens.

| Misconception | Where it shows up | The move that fixes it |
|---|---|---|
| "The converse is the same claim" | S01, and every proof after it | one statement whose converse is plainly false |
| "`p → q` must be false when p is false" | S01 truth tables | the umbrella example, on a sunny day |
| "Examples prove a ∀ claim" | everywhere | `n² + n + 41` at n = 41 |
| "∀∃ and ∃∀ say the same thing" | S02 | the two integer statements, one true, one false |
| "The induction step just proves k+1" | S04 | ask them to point at the hypothesis-use line |
| "Set equality needs one inclusion" | S05 | a pair with A ⊆ B and B ⊄ A |
| "Symmetric and antisymmetric are opposites" | S07 | a relation that is both |
| "A Venn diagram is a proof" | S05 | a three-set claim a diagram cannot settle |
| "Mod arithmetic works like ordinary arithmetic" | S10 | `2·3 ≡ 4·3 (mod 6)` with `2 ̸≡ 4` |

**The layer usually missing underneath:** the precise definition being used (even, divides, subset). Ask them to write the definition before the proof.
