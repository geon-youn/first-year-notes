---
alias: intersect, disjoint
tags: MATH_1C03
---
# Set Intersection
Let $A$ and $B$ be [[set]]s. The **intersection of A and B** is
$$A\cap B=\left\{x | x\in A \wedge x\in B\right\}$$

If $A\cap B=\emptyset$ then $A$ and $B$ are said to be **disjoint**.

## Basic Properties
Let $A,B$ be sets. Then:
1. $A\cap\emptyset=\emptyset$
2. $A\cap\overline{A}=\emptyset$
3. $A\cup A=A\cap A=A$
4. $A\cap B\subseteq A \subseteq A \cup B$

## "Order of Operations" Properties
Let $A,B,C$ be subsets of some universal set $U$. Then:
1. ($\cap$ is [[associativity|associative]]) $A\cap(B\cap C)=(A\cap B)\cap C$
2. ($\cap$ [[distributivity|distributes]] over $\cup$) $A\cap(B\cup C)=(A\cap B)\cup (A\cap C)$

## Finite Properties
For all positive [[integers]] $n\geq 1$, if $A$ and $B_1,\dots,B_n$ are sets, then $\cap$ distributes over [[finite union]]:
$$A\cap\left(\bigcup^n_{i=1}B_i\right)=\bigcup^n_{i=1}(A\cap B_i)$$
The same applies to [[arbitrary union]]s.