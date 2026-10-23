# Code examples from the lecture notes

Sage sessions and C-style pseudocode reproduced from the [lecture notes](../notes/lecture-notes.pdf). These are instructional transcripts; `sage:` prompts and printed output are retained.

## Logic and proofs: example 1

Propositional Equivalences

```text
sage: f1 = propcalc.formula("~(p -> q)")
sage: f2 = propcalc.formula("~(~p | q)")
sage: f1==f2
True
sage: f1.truthtable()
p       q       value
False   False   False
False   True    False
True    False   True
True    True    False

sage: f2.truthtable()
p       q       value
False   False   False
False   True    False
True    False   True
True    True    False
```

## Logic and proofs: example 2

Predicates:

```text
if (x > 0)
y = 3; //C-language code.
```

## Logic and proofs: example 3

Using Rules of Inference to Build Arguments (recall Ex. 1.3.12)

```text
sage: f = propcalc.formula("((~p & q) & (r -> p) & (~r -> s) & (s -> t)) -> t")

sage: f
((~p&q)&(r->p)&(~r->s)&(s->t))->t

sage: f.truthtable()
p       q       r       s       t       value
False   False   False   False   False   True
False   False   False   False   True    True
False   False   False   True    False   True
False   False   False   True    True    True
False   False   True    False   False   True
False   False   True    False   True    True
False   False   True    True    False   True
False   False   True    True    True    True
False   True    False   False   False   True
False   True    False   False   True    True
False   True    False   True    False   True
False   True    False   True    True    True
False   True    True    False   False   True
False   True    True    False   True    True
False   True    True    True    False   True
False   True    True    True    True    True
True    False   False   False   False   True
True    False   False   False   True    True
True    False   False   True    False   True
True    False   False   True    True    True
True    False   True    False   False   True
True    False   True    False   True    True
True    False   True    True    False   True
True    False   True    True    True    True
True    True    False   False   False   True
True    True    False   False   True    True
True    True    False   True    False   True
True    True    False   True    True    True
True    True    True    False   False   True
True    True    True    False   True    True
True    True    True    True    False   True
True    True    True    True    True    True
```

## Logic and proofs: example 4

Using Rules of Inference to Build Arguments (recall Ex. 1.3.12)

```text
sage: f = propcalc.formula("((p -> q) & (~p -> r) & (r -> s)) -> (~q -> s)")

sage: f
((p->q)&(~p->r)&(r->s))->(~q->s)

sage: f.truthtable()
p       q       r       s       value
False   False   False   False   True
False   False   False   True    True
False   False   True    False   True
False   False   True    True    True
False   True    False   False   True
False   True    False   True    True
False   True    True    False   True
False   True    True    True    True
True    False   False   False   True
True    False   False   True    True
True    False   True    False   True
True    False   True    True    True
True    True    False   False   True
True    True    False   True    True
True    True    True    False   True
True    True    True    True    True
```

## Logic and proofs: example 5

Exhaustive Proof and Proof by Cases

```text
sage: for i in range(1000000):
....:     if not ((i^2 % 10) in {0, 1, 4, 5, 6, 9}):
....:         print(i)
....:
```

## Sets, functions, and sums: example 1

Cartesian Products

```text
for(i=1, i<=|A|, i++)
        for(j=1, j<=|B|, j++)
                (A[i], B[j]); // C-like pseudo-code.
```

## Sets, functions, and sums: example 2

Introduction

```text
float TestFunction(int x){
    ...
}
```

## Sets, functions, and sums: example 3

Other important functions

```text
int Factorial(int n){
  for(int product=1; n>=1; n--)
    product*=n;
  return product;
}
```

## Sets, functions, and sums: example 4

Notations and Basics

```text
s=0;
for(int i=m; i <= n; i++)
   s+= a[i];
```

## Sets, functions, and sums: example 5

Notations and Basics

```text
sage: j=var('j')
sage: sum(1/j, j, 10, 100)
32885835761679513760951913715533243583283 /
   13944075045942495432906761787062460711360
```

## Sets, functions, and sums: example 6

Notations and Basics

```text
sage: i, j= var('i, j')
sage: sum(sum(i*j, j, 1, 3), i, 1, 4)
60
```

## Sets, functions, and sums: example 7

Notations and Basics

```text
s=0;
for(int i=1; i <= 4; i++)
   for(int j=1; j <= 3; j++)
      s+= i*j;
```
