---
alias:
tags: MATH_1B03
---
# Cramer's rule for inverse
Given an $n \times n$ matrix $A$, its inverse is its [[adjugate matrix]] divided by its [[determinant]] such that
$$A^{-1}=\frac{\operatorname{adj} A}{\det A}$$

```ad-abstract
title: Proof
If
$$\mathbb{I}_n=AA^{-1}$$
Then let $A^{-1}=\begin{bmatrix}\vec{c_1} & \cdots & \vec{c_{j-1}} & \vec{x} & \vec{c_{j+1}} & \cdots & \vec{c_n}\end{bmatrix}$ such that 
$$\mathbb{I}_n=A\begin{bmatrix}\vec{c_1} & \cdots & \vec{c_{j-1}} & \vec{x} & \vec{c_{j+1}} & \cdots & \vec{c_n}\end{bmatrix}$$
Then, 
$$\vec{e_j}=A \vec{x}$$
So, the $i$th row $j$th column entry of $A^{-1}$ is $x_i$. Now, apply [[Cramer's rule]] to the equation $\vec{e_j}=A \vec{x}$:
$$
\begin{align*}
x_i&=\frac{\det A_i(\vec{e_j})}{\det A}\\
&=\frac{(-1)^{j+1}\det A_{ji}}{\det A}\\
&=\frac{(j,i)^\text{th}\;\text{entry of }C}{\det A}\\
&=\frac{(i,j)^\text{th}\;\text{entry of }C^{\text{T}}}{\det A}\\
&\Rightarrow A^{-1}=\frac{\operatorname{adj} A}{\det A}
\end{align*}
$$
```