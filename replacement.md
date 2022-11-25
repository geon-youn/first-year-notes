---
alias:
tags: MATH_1B03
---
# Row Replacement
We can add a multiple of a row onto another row.

```ad-example
Given the following $3\times 3$ matrix, we can replace the first row by the first row plus negative four of the second row:
$$\begin{bmatrix}
1 & 4 & 21\\
0 & 1 & -13\\
0 & 0 & 0
\end{bmatrix}\Leftrightarrow\begin{bmatrix}
1 & 0 & 73\\
0 & 1 & -13\\
0 & 0 & 0
\end{bmatrix}$$
```

```ad-info
title: As a [[linear transformation]]
$$T:\mathbb{R}^3 \mapsto \mathbb{R}^3$$
$$\begin{bmatrix}x_1\\x_2\\x_3\end{bmatrix} \mapsto \begin{bmatrix}x_1+cx_2\\x_2\\x_3\end{bmatrix}$$
Then, the [[standard matrix]] of $T$ is
$$\begin{bmatrix}1 & c & 0\\0 & 1 & 0\\0 & 0 & 1 \end{bmatrix}$$
```
