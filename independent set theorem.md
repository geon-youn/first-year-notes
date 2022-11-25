---
alias:
tags: MATH_1B03
---
# Independent Set Theorem
Let $H$ be a subset for a vector space $V$ and $S= \left\{\vec{v_1},\dots\vec{v_p}\right\}$ be an independent set in $H$. Then, some *superset* of $S$ is a basis for $H$ and $\text{dim}H\leq \text{dim}V$ 

## Difference from [[spanning set theorem]]
We assume that $S$ is already independent and work upwards by a superset instead of a subset.

## Proof
We can achieve our proof inductively:
1. If $S$ spans, then $S$ is a basis. 
2. Otherwise, $\exists \vec{v_{p+1}} \in H\setminus\text{Span}S$ such that $\{\vec{v_1},\dots,\vec{v_p},\vec{v_{p+1}}\}$ is independent.
3. So, if this spans, it is a basis.
4. Otherwise, repeat until we reach a basis.

We must eventually reach a basis since $\text{dim}H\leq \text{dim}V$. So, we will have at most $\text{dim}V$ vectors in the set. 