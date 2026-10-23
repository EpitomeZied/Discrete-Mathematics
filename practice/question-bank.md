---
title: Discrete Math Question Bank
type: note
topic: teaching
created: 2026-09-25
tags: [ta, teaching, discrete-math]
---
# Discrete Math — Question Bank

> [!NOTE]
> Three kinds per topic: **Recap** (first 5 minutes, cold-called, ungraded) · **Exercise** (their turn, in-section) · **Exam-style**.
> Companions: [Discrete Math Sections](../notes/section-plan.md) · [Discrete Math Playbook](../notes/teaching-playbook.md) · the general teaching playbook (local reference).

## Contents
- [How to use this](#how-to-use-this)
- [Logic](#logic)
- [Quantifiers](#quantifiers)
- [Proof methods](#proof-methods)
- [Induction](#induction)
- [Sets](#sets)
- [Functions](#functions)
- [Relations](#relations)
- [Counting](#counting)
- [Recurrences](#recurrences)
- [Number theory](#number-theory)
- [Graphs and trees](#graphs-and-trees)
- [Find the flaw](#find-the-flaw)

-----

## How to use this

- Pick **three** recap questions the night before; write them down. Improvised questions are always too easy or too cruel.
- Favour questions whose answer is one sentence — I need eight answers in five minutes.
- The best questions hand them a **plausible wrong claim** to attack. Nobody loses face demolishing a position I supplied.
- Anything missed twice becomes a row in the misconception log in the general teaching playbook (local reference).

-----

## Logic

**Recap**
1. Is `p → q` true when p is false?
2. Which of converse / inverse / contrapositive is equivalent to the original?
3. Negate "it is raining and cold."
4. `p → q` written with ∨?
5. When is `p ↔ q` true?

**Exercise**
1. Build the truth table for `(p → q) ∧ (q → p)` and name what it equals.
2. Show `¬(p → q) ≡ p ∧ ¬q` and read it in English.
3. Write the converse, inverse, and contrapositive of "if a number is divisible by 4, it is even," and say which are true.

**Exam-style**
1. Simplify `¬(p ∨ (¬p ∧ q))` using laws, naming each law used.
2. Is `{¬, ∧}` enough to express every connective? Justify.
3. Three statements about one circuit; decide consistency.

-----

## Quantifiers

**Recap**
1. Does `∀x ∃y` mean the same as `∃y ∀x`?
2. Negate `∀x P(x)`.
3. What is the truth value of `∀x ∈ ∅, P(x)`?
4. To disprove a ∀ statement, what do you produce?
5. Why does the domain change the answer?

**Exercise**
1. Translate: "every student has a course they dislike," then negate it in words *and* symbols.
2. Over ℤ, decide: `∀x ∃y (x + y = 0)` and `∃y ∀x (x + y = 0)`.
3. Write "there is exactly one x with P(x)" using only ∀, ∃, and =.

**Exam-style**
1. Negate a three-quantifier statement step by step, showing each push inward.
2. Give a predicate and two domains where the same ∀ statement is true in one and false in the other.
3. Disprove `∀n ∈ ℤ⁺, n² + n + 41 is prime` — and state why "I checked ten cases" would have been worthless.

-----

## Proof methods

**Recap**
1. First line of a proof by contradiction of `P → Q`?
2. When is contrapositive easier than direct?
3. What must a proof by cases also establish?
4. Is one example ever a proof of a ∀ claim?
5. Definition of "n is even," usable in algebra?

**Exercise**
1. Prove: if n² is even then n is even. (Contrapositive.)
2. Prove √2 is irrational. (Contradiction.)
3. Prove the product of two consecutive integers is even. (Cases, or parity.)
4. Prove: for all integers n, `n² + n` is even.

**Exam-style**
1. Prove or disprove: the sum of two irrationals is irrational.
2. Prove that if `a | b` and `b | c` then `a | c`, from the definition only.
3. Prove there are infinitely many primes; then say which method it is and where the contradiction lands.

-----

## Induction

**Recap**
1. The three parts of an induction proof?
2. What must the step contain to count?
3. Difference between ordinary and strong induction?
4. What breaks if the base case is at the wrong n?
5. Is "assume true for all n" a legal hypothesis?

**Exercise**
1. `1 + 2 + … + n = n(n+1)/2`.
2. `2^n > n` for n ≥ 1.
3. `3 | n³ − n` for all n ≥ 0.
4. Every integer n ≥ 2 has a prime divisor. (Strong.)
5. Sum of the first n odd numbers is n². Then *see* it as a square of dots.

**Exam-style**
1. A geometric-sum formula, proved fully, with the hypothesis-use line labeled.
2. Prove a tiling/recursive-structure claim by strong induction.
3. Here is an induction "proof" that all horses are the same colour. Find the exact broken step.

-----

## Sets

**Recap**
1. `∈` vs `⊆`, in one sentence each.
2. Is `{1} ∈ {{1}}`? Is `{1} ⊆ {{1}}`?
3. `|P(S)|` for `|S| = 4`?
4. How do you prove `A = B`?
5. Is ∅ ⊆ A always?

**Exercise**
1. Prove `A ∩ (B ∪ C) = (A ∩ B) ∪ (A ∩ C)` by double inclusion.
2. Prove `A \ (B ∩ C) = (A \ B) ∪ (A \ C)`.
3. List `P({a, b, c})` and check the count against `2^n`.
4. Disprove: `A ∪ B = A ∪ C ⇒ B = C`.

**Exam-style**
1. Prove a De Morgan law for sets and name the logic law each line mirrors.
2. `|A ∪ B ∪ C|` by inclusion–exclusion, applied to given sizes.
3. Prove `A ⊆ B ⇔ A ∩ B = A`. (Both directions.)

-----

## Functions

**Recap**
1. Injective, in the form you prove it?
2. Surjective, in the form you prove it?
3. Is `f(x) = x²` injective on ℝ? On ℝ⁺?
4. When does `f⁻¹` exist?
5. Why does the codomain matter?

**Exercise**
1. For three given functions, decide and prove/disprove injective and surjective.
2. Show that if `g ∘ f` is injective then f is injective.
3. Give a function ℤ → ℤ that is surjective but not injective, and one that is injective but not surjective.

**Exam-style**
1. Prove `f(x) = 3x + 2` on ℝ→ℝ is a bijection and compute the inverse.
2. Prove `|A| = |B|` by constructing a bijection, for two given infinite sets.
3. Disprove injectivity of a given function — with two explicit inputs, not an assertion.

-----

## Relations

**Recap**
1. The three properties of an equivalence relation.
2. Symmetric vs antisymmetric — are they opposites?
3. What does an equivalence relation induce?
4. To kill transitivity, what do you show?
5. Is the empty relation on a nonempty set reflexive? Is it symmetric? Is it transitive?

**Exercise**
1. Verify congruence mod 5 is an equivalence relation and list its classes.
2. For a given relation on `{1,2,3,4}`, check all four properties.
3. Find a relation that is reflexive and symmetric but not transitive.
4. Draw the Hasse diagram of divisibility on `{1,2,3,4,6,12}`.

**Exam-style**
1. Prove the relation "same remainder mod n" partitions ℤ, and count the classes.
2. Given a partial order, find maximal, minimal, greatest, and least elements — and say which may fail to exist.
3. Prove that if R is symmetric and transitive on its domain, adding reflexivity makes it an equivalence relation.

-----

## Counting

**Recap**
1. When order matters and repetition is forbidden, which counting formula applies?
2. `C(n, k)` vs `P(n, k)` — the relationship?
3. `C(n, 0)` and `C(n, n)`?
4. How do you count "at least one"?
5. Pigeonhole, stated in one sentence.

**Exercise**
1. From 10 people, choose a committee of 4; then a president, VP, and secretary. Which is which formula?
2. Count 5-letter strings over a 26-letter alphabet with and without repetition.
3. Committees of 5 from 6 men and 4 women with at least one woman — two ways (direct and complement), answers must agree.
4. How many ways to arrange the letters of a word with repeats?

**Exam-style**
1. Inclusion–exclusion over three given sets, with the Venn diagram drawn.
2. Distribute 10 identical items into 4 distinct boxes.
3. Prove `C(n, k) = C(n, n−k)` by a *counting* argument, not algebra.
4. Show that among any 13 people, two share a birth month. State the pigeons and the holes explicitly.

-----

## Recurrences

**Recap**
1. What does a recurrence need besides the rule?
2. What do you do after guessing a closed form?
3. Recurrence for Towers of Hanoi and its closed form?
4. How many initial conditions does a second-order recurrence need?
5. What is the characteristic equation for?

**Exercise**
1. Unroll `a_n = 2a_{n-1} + 1`, `a_0 = 1`, guess the closed form, prove it.
2. Solve `a_n = a_{n-1} + 6a_{n-2}` with given initial values; verify n = 0..3.
3. Set up (do not solve) the recurrence for the number of binary strings of length n with no two consecutive 1s.

**Exam-style**
1. Solve a second-order homogeneous recurrence with a repeated root.
2. Model a word problem as a recurrence, justify the model in words, then solve.
3. Given a closed form and a recurrence, verify they agree — and say what verification does and does not prove.

-----

## Number theory

**Recap**
1. Definition of `a | b`.
2. `a ≡ b (mod n)` means what, exactly?
3. When may you divide both sides of a congruence by c?
4. What does extended Euclid give you beyond the gcd?
5. `gcd(a, b) · lcm(a, b) = ?`

**Exercise**
1. Euclid for `gcd(252, 198)`, then extended Euclid for Bézout.
2. Solve `7x ≡ 3 (mod 11)`.
3. Prove: the sum of two odd integers is even — definitions only.
4. Compute `3^100 mod 7` without a calculator.

**Exam-style**
1. Prove that if `d | a` and `d | b` then `d | (ax + by)` for all integers x, y.
2. Find the multiplicative inverse of 17 mod 43, showing the work.
3. Prove there is no integer solution to a given congruence, and name the obstruction.

-----

## Graphs and trees

**Recap**
1. Handshake lemma?
2. How many odd-degree vertices can a graph have?
3. Euler circuit condition?
4. Edges in a tree on n vertices?
5. Is a Hamiltonian path condition as clean as Euler's?

**Exercise**
1. Prove the handshake lemma by double counting.
2. Decide bipartiteness for two drawn graphs, with justification.
3. Prove: a graph where every vertex has degree ≥ 2 contains a cycle.
4. Count the spanning trees of a small graph by hand.

**Exam-style**
1. Prove by induction that a tree on n vertices has n − 1 edges.
2. Model a scheduling conflict problem as a graph colouring and interpret the chromatic number in the problem's own words.
3. Does a graph with degree sequence `(3,3,3,1)` exist? Justify.

-----

## Find the flaw

Projected on screen, 60 seconds each, hands down until time is up. In this subject this is the single highest-value five minutes I run.

**F1** — *Claim: all horses are the same colour.* "Base: one horse, trivially. Step: assume any k horses are the same colour. Given k+1 horses, the first k are the same colour and the last k are the same colour, so all k+1 are."

**F2** — *Claim: if n² is even then n is even.* "Proof: n² is even, so n² = 2k, so n = √(2k), which is even. ∎"

**F3** — *Claim: 1 + 2 + … + n = n(n+1)/2.* "Step: assume true for k. Then 1 + … + (k+1) = (k+1)(k+2)/2, which is the formula at k+1. ∎"

**F4** — *Claim: `∀n ∈ ℤ⁺`, n² + n + 41 is prime.* "Proof: 41, 43, 47, 53, 61 are all prime, and the pattern continues. ∎"

**F5** — *Claim: A = B.* "Proof: let x ∈ A. Then x ∈ B. Therefore A = B. ∎"

**F6** — *Claim: R is transitive.* "Proof: 1 R 2 and 2 R 3, and indeed 1 R 3. So R is transitive. ∎"

**F7** — *Claim: if `ac ≡ bc (mod n)` then `a ≡ b (mod n)`.* "Proof: divide both sides by c. ∎"

**F8** — *Claim: √2 is irrational.* "Suppose √2 = p/q. Then 2q² = p², so p² is even, so p is even. Therefore √2 is irrational. ∎"

-----
