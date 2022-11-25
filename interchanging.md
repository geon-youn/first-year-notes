---
alias:
tags: MATH_1B03
---
# Interchanging Rows
We can swap two rows in a matrix.

```ad-example
Here we swap the first and second rows:
$$\begin{bmatrix}
1 & 4 & 21\\
0 & 1 & -13\\
0 & 0 & 0
\end{bmatrix}\Leftrightarrow\begin{bmatrix}
0 & 1 & -13\\
1 & 4 & 21\\
0 & 0 & 0
\end{bmatrix}$$
```

```ad-info
title: As a [[linear transformation]]
$$T:\mathbb{R}^3 \mapsto \mathbb{R}^3$$
$$\begin{bmatrix}x_1\\x_2\\x_3\end{bmatrix} \mapsto \begin{bmatrix}x_3\\x_2\\x_1\end{bmatrix}$$
Then, the [[standard matrix]] of $T$ is
$$\begin{bmatrix}0 & 0 & 1\\0 & 1 & 0\\1 & 0 & 0 \end{bmatrix}$$
```
