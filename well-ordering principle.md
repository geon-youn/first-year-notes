---
alias:
tags: MATH_1C03
---
# The Well-Ordering Principle
Let $S$ be a non-empty subset of the set of non-negative integers, $\mathbb{Z}_{\geq 0}$. Then, $S$ has a smallest element $m$. In fact, $m$ is **unique**. This principle is equivalent to the principle of [[mathematical induction]]. For a simpler explanation, look at [[well-order]].

## Proof (If inductive, then well-ordered)
Fix $S\subseteq \mathbb{Z}_{\geq 0}$ nonempty. Assume that $S$ does not contain a smallest element. Want to show that $S$ must be empty. 

Base case ($n=0$): $0\notin S$ because if it was, it would be the smallest element in $S$. 

Inductive step: Assume for all $k$, $0 \leq k \leq n$ that $k\notin S$. 

Then $n+1 \notin S$, because if it was, it would be the smallest element in $S$. 

Therefore, $\forall n\in \mathbb{Z}_{\geq 0},n\notin S$.