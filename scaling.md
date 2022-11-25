---
alias:
tags: MATH_1B03
---
# Scaling a Row
We can scale a row by a constant $c\in\mathbb{R}$, but $c\neq 0$. 

```ad-example
We can scale the second row by $\frac{1}{2}$:
$$\begin{bmatrix}
1 & 4 & 21\\
0 & 2 & -26\\
0 & 0 & 0
\end{bmatrix}\Leftrightarrow\begin{bmatrix}
1 & 4 & 21\\
0 & 1 & -13\\
0 & 0 & 0
\end{bmatrix}$$
```

```ad-question
title: Why can't we scale by 0?
If we scale by 0, we don't preserve the set of solutions since we might be removing a [[pivot position]].
```

```ad-info
title: As a [[linear transformation]]
$$T:\mathbb{R}^3 \mapsto \mathbb{R}^3$$
$$\begin{bmatrix}x_1\\x_2\\x_3\end{bmatrix} \mapsto \begin{bmatrix}x_1\\cx_2\\x_3\end{bmatrix}$$
Then, the [[standard matrix]] of $T$ is
$$\begin{bmatrix}1 & 0 & 0\\0 & c & 0\\0 & 0 & 1 \end{bmatrix}$$
```
