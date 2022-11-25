---
alias:
tags: MATH_1B03
---
# Row-Column Expansion for Finding the Determinant
Let $A$ be an $n \times n$ matrix and $A_{ij}$ be the remaining $(n-1) \times (n-1)$ matrix when we "remove" the $i$th row and $j$th column. Then, the [[determinant]] of $A$ is the sum of $n$ terms of the form $\pm a_{ij}\det A_{ij}$. In other words, $\det A$ is the [[inner product|dot product]] of row $k$ of $A$ and row $k$ of the [[cofactor matrix]]. Or, in terms of columns, $\det A$ is the dot product of column $k$ of $A$ and column $k$ of the cofactor matrix. So,
$$
\begin{align*}
\det A &= \sum^{n}_{i=1}a_{ik}C_{ik}\\
	   &= \sum^{n}_{j=1}a_{kj}C_{kj}
\end{align*}$$

```ad-tip
title: For upper [[triangular]] matrices
The determinant of upper triangular matrices is very simple. Since the values below the [[main diagonal]] are 0, 
$$\det A = \prod^{n}_{i=1}a_{ii}$$
In other words, the determinant of an upper triangular matrix is the product of the entries of its main diagonal. 
```