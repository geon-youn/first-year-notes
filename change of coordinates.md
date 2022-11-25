---
alias:
tags: MATH_1B03
---
# Change of Coordinates
Let $B$ be a [[basis]] for $\mathbb{R}^n$. Then, the **change of coordinates** matrix for $B$ is $P_B=[\vec{b_1}\dots\vec{b_n}]$ where $B=\{\vec{b_1},\dots,\vec{b_n}\}$ (ordered set of vectors) such that the change of coordinates matrix times the [[B-coordinate vector]] is $\vec{x}$. So,
$$\begin{align*}\vec{x}&=P_B[\vec{x}]_B\\[8pt]
[\vec{x}]_B&=P_B^{-1}\vec{x}\end{align*}$$

```ad-abstract 
title: Proof
$$\begin{align*}
\vec{x}&=c_1\vec{b_1}+\dots+c_n\vec{b_n}\\
	   &=[\vec{b_1}\cdots\vec{b_n}]\begin{bmatrix}c_1\\\vdots\\c_n\end{bmatrix}\\
	   &=P_B[\vec{x}]_B
\end{align*}$$
and $P_B$ is invertible by the [[invertible matrix theorem]].
```