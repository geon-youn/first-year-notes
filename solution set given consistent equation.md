---
alias:
tags: MATH_1B03
---
# Solution Set Given Consistent Equation
Let $A\vec{x}=\vec{b}$ be [[existence and uniqueness theorem|consistent]] for some given $\vec{b}$, and let $\mathbb{I}$ be the solution set such that $\mathbb{I}=\left\{\vec{p}:A\vec{p}=\vec{b}\right\}$. Then, another way to represent the solution set of $A\vec{x}=\vec{b}$ is the set of all vectors of the form $\vec{w}=\vec{p}+\vec{h}$, where $\vec{h}$ is any solution of the [[homogeneity|homogeneous]] equation $A\vec{x}=\vec{0}$. If $\mathbb{H}=\left\{\vec{h}:A \vec{h}=\vec{0}\right\}$, then $\mathbb{I}=\left\{\vec{p}+\vec{h} : \vec{p} \in \mathbb{I} \wedge \vec{h} \in \mathbb{H}\right\}$.

```ad-example
The solution set of the equation
$$\begin{bmatrix}1 & -1 & 0 & 0\\
2 & -1 & 0 & 0\end{bmatrix}\begin{bmatrix}x_1\\x_2\\x_3\\x_4\end{bmatrix}=\begin{bmatrix}4\\6\end{bmatrix}$$
is $\left\{\vec{p}+\vec{v_3}x_3+\vec{v_4}x_4 : x_3,x_4\in\mathbb{R}\right\}$, where
- $\vec{p}$ is some solution of the inhomogeneous system;
- $\vec{v_3}x_3+\vec{v_4}x_4$ is the solutions of the associated homogeneous system.

So, $\left\{\begin{bmatrix}2\\-2\\0\\0\end{bmatrix}+\begin{bmatrix}0\\0\\1\\0\end{bmatrix} x_3+\begin{bmatrix}0\\0\\0\\1\end{bmatrix} x_4 : x_3,x_4\in\mathbb{R}\right\}$ is the solution set.
```