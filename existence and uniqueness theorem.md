---
alias:
tags: MATH_1B03
---
# Existence and Uniqueness Theorem
A linear system is **consistent** iff the rightmost column of the augmented matrix is *not* a [[pivot position|pivot column]]. 

```ad-tip
title: Alternative Explanation
A linear system is consistent if an [[row echelon form|echelon form]] of the augmented matrix has *no* rows of the form
$$\begin{bmatrix}0 & \cdots & 0 & b\end{bmatrix}$$
with $b$ nonzero. 
```

^8efd91

If a linear system is **consistent**, then the solution set contains either
1. A unique solution, where there are no free variables;
2. Infinitely many solutions, when there is at least one free variable.

If a linear system is **inconsistent**, then the solution set is empty. 
