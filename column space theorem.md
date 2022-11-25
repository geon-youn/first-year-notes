---
alias:
tags: MATH_1B03
---
# Column Space Theorem
Let $A$ be an $m \times n$ matrix. Then, the [[pivot column|pivot columns]] of $A$ form a [[basis]] for the [[column space]] of $A$. 

```ad-abstract
title: Proof
Let $U$ be an [[reduced row echelon form|RREF]] of $A$ such that $U=\begin{bmatrix}1&&&0&&&0&&\\0&&&1&&&0&&\\\vdots&&&0&&&1&&\\&&&\vdots&&&0&\\&&&&&&\vdots&\end{bmatrix}$.
Then, the pivot columns $\vec{e_1},\dots,\vec{e_n}$ are a basis (free columns are a [[linear combination]] of the pivot columns) for $\text{Col}U$. 
Therefore, the pivot columns of $A$ are a basis for $\text{Col}A$ since $A\vec{x}=\vec{0}$ iff $U\vec{x}=\vec{0}$ (i.e. because $A$ and $U$ are [[row equivalent]]). 
```