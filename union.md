---
alias:
tags: MATH_1C03
---
# Set Union
Let $A$ and $B$ be [[set]]s. The **union of A and B** is
$$A\cup B=\left\{x | x\in A \vee x \in B\right\}$$

## Cardinality
The [[cardinality]] of a union $A\cup B$ is $|A\cup B|=|A|+|B|-|A\cap B|$.
## Basic Properties
Let $A,B$ be sets and $U$ be the [[universe]]. Then:
1. $A\cup \emptyset=A$
2. $A\cup\overline{A}=U$
3. $A\cup A=A\cap A=A$
4. $A\cap B\subseteq A \subseteq A \cup B$

## "Order of Operations" Properties
Let $A,B,C$ be subsets of some universal set $U$. Then:
1. ($\cup$ is [[associativity|associative]]) $A\cup(B\cup C)=(A\cup B)\cup C$
2. ($\cup$ [[distributivity|distributes]] over $\cap$) $A\cup(B\cap C)=(A\cup B)\cap (A\cup C)$

## Finite Properties
For all positive [[integers]] $n\geq 1$, if $A$ and $B_1,\dots,B_n$ are sets, then $\cup$ distributes over [[finite intersection]]:
$$A\cup\left(\bigcap^n_{i=1}B_i\right)=\bigcap^n_{i=1}(A\cup B_i)$$
The same applies to [[arbitrary intersection]]s. 
