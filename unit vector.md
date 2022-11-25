---
alias:
tags: MATH_1B03
---
# Unit Vectors
**Unit vectors** are [[vector|vectors]] that are given the notation $\vec{e_n}$, where $n$ is the row where there is a $1$ and thus there are $0$'s in every other row. A unit vector has a length of 1. 

```ad-example
$$\vec{e_1}=\begin{bmatrix}1\\0\\\vdots\\0\end{bmatrix},\vec{e_2}=\begin{bmatrix}0\\1\\0\\\vdots\\0\end{bmatrix},\dots$$
```

Any vector $\vec{v}=\begin{bmatrix}x_1\\\vdots\\x_n\end{bmatrix} \in \mathbb{R}^n$ can be written as a **unique** [[linear combination]] of $\vec{e_1},\dots,\vec{e_n}$:
$$\vec{v}=x_1\vec{e_1}+\dots+x_n\vec{e_n}$$