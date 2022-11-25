---
alias:
tags: MATH_1B03
---
# Orthonormal Projection
If $\{\vec{u_1},\dots,\vec{u_p}\}$ is an [[orthonormal basis]] for a [[subspace]] $W$ of $\mathbb{R}^n$, then 
$$\operatorname{proj}_W\vec{y}=(\vec{y}\cdot\vec{u_1})\vec{u_1}+\dots+(\vec{y}\cdot\vec{u_p})\vec{u_p}$$
If $U=\begin{bmatrix}\vec{u_1} & \cdots & \vec{u_p}\end{bmatrix}$, then
$$\operatorname{proj}_W\vec{y}=UU^T\vec{y}$$
for all $\vec{y}\in\mathbb{R}^n$. 

```ad-abstract
title: Proof
We essentially do the same thing as [[orthogonal projection]], but since we are dealing with [[orthonormal columns]], we don't need normalize the result. 
```