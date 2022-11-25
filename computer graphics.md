---
alias:
tags: MATH_1B03
---
# Computer Graphics
To translate a set of coordinates in $\mathbb{R}^n$, write [[homogeneous coordinates]] in $\mathbb{R}^{n+1}$.

```ad-example
$\mathbb{R}^2\rightarrow \mathbb{R}^3$
$$
\begin{pmatrix}x\\y \end{pmatrix}\rightarrow 
\begin{pmatrix}x+a\\y+b\end{pmatrix} :
\left[\begin{array}{cc|c}
1 & 0 & a\\
0 & 1 & b\\
\hline
0 & 0 & 1
\end{array}\right]
\begin{pmatrix}x\\y\\1\end{pmatrix}=
\begin{pmatrix}x+a\\y+b\\1 \end{pmatrix}$$
So, $\begin{pmatrix}x+a\\y+b\end{pmatrix}$ is equivalent to $\begin{pmatrix}x+a\\y+b\\1 \end{pmatrix}$, but $\begin{pmatrix}x+a\\y+b\\1 \end{pmatrix}$ is in a higher [[dimension]].
```

```ad-abstract
title: If $A$ is a $n \times n$ matrix, then
$$\left[
\begin{array}{ccc|c}
& & & c_1\\
& A & & \vdots\\
& & & c_n\\
\hline
0 & \cdots & 0 & 1
\end{array}
\right]
\begin{bmatrix}x_1\\\vdots\\x_n\\\hline 1\end{bmatrix}=
\begin{bmatrix}A \left(\begin{array}{c}x_1\\\vdots\\x_n\end{array}\right)+\left(\begin{array}{c}c_1\\\vdots\\c_n\end{array}\right)\\\hline 1\end{bmatrix}$$
```