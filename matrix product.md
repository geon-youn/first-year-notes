---
alias:
tags: MATH_1B03
---
# Matrix Product
Let $A$ be a $m \times n$ matrix and $B=[\vec{b_1} \dots \vec{b_p}]$ be a $n \times p$ matrix column vectors $\vec{b_1},\dots,\vec{b_p} \in \mathbb{R}^n$. Then
$$AB = \left[A\vec{b_1}\dots A\vec{b_p}\right]$$
forms an $m \times p$ matrix.

```ad-tip
When you multiply a $\textbf{m} \times n$ matrix by a $n \times \textbf{p}$ matrix, the resulting matrix is a $\textbf{m} \times \textbf{p}$ matrix.

Also, when you multiply two matrices, $A$ must have the same number of **columns** as $B$ has **rows**.
```

```ad-info
title: Left/right multiplication
With matrices, when you multiply both sides by a matrix, you have to specify whether you multiply from the left or from the right. Matrix multiplication is not [[commutativity|commutative]]!
$$AB\not \Leftrightarrow BA$$
e.g. left multiplication:
$$B=C \Rightarrow AB=AC$$
e.g. right multiplication:
$$B=C \Rightarrow BA=CA$$
You **cannot** mix them around like so:
$$B=C \not \Rightarrow AB=CA$$
```