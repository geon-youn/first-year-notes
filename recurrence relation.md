---
alias: recurrence relation, closed formula
tags: COMPSCI_1DM3
created: February 14, 2022 17:43
---
# Recurrence Relation
An equation that expresses $a_n$ in terms of one or more of the previous terms of the [[sequences|sequence]]. Initial conditions are required to specify terms that precede the first term where the relation takes effect.

```ad-example
$a_n=a_{n-1}+2a_{n-2}$ for $n\geq 2$ where $a_0=2$ and $a_1=5$.
```

## Solution
A sequence is called a *solution* of a recurrence relation if its terms satisfy the recurrence relation.

## Solving
Finding a formula (closed formula) for the $n$th term of the sequence generated by a recurrence relation is called *solving the recurrence relation*.

### Iterative Solution
Guessing the pattern by starting at a point (usually start or end) and working forwards (or downwards) through substitution.