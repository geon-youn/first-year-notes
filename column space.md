---
alias:
tags: MATH_1B03
---
# Column Space
Given an $n \times n$ matrix $A$, its **column space** is the set of all [[linear combination|linear combinations]] of the columns of $A$. If $A=[\vec{a_1}\cdots\vec{a_n}]$, then
$$\operatorname{Col}A=\{x_1\vec{a_1}+\cdots+x_n\vec{a_n}:x_j\in \mathbb{R}^n\}=\operatorname{Span}\{\vec{a_1},\dots,\vec{a_n}\}$$

```ad-note
The column space of an $m \times n$ matrix $A$ is a [[subspace]] of $\mathbb{R}^m$. 
Similarly, if the column space of $A$ spans all of $\mathbb{R}^n$ (or its column space is onto), then $A$ is [[onto]].
```

The [[span]] of the [[reduced row echelon form|RREF]] of a matrix is not always equal to the span of the original matrix if that matrix is not [[invertibility|invertible]]. 