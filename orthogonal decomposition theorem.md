---
alias:
tags: MATH_1B03
---
# Orthogonal Decomposition Theorem
Let $W$ be a [[subspace]] of $\mathbb{R}^n$. Then each $\vec{y}$ in $\mathbb{R}^n$ can be written **uniquely** in the form
$$\vec{y}=\widehat{\vec{y}}+\vec{z}$$
by [[orthogonal projection]], where $\widehat{\vec{y}}$ is in $W$ and $\vec{z}$ is in $W$'s [[orthogonal complement]] $W^\perp$.

```ad-abstract
title: Proof
1. If $\{\vec{u_1},\dots,\vec{u_p}\}$ is any [[orthogonal basis]] of $W$, then
$$\widehat{\vec{y}}=\frac{\vec{y}\cdot\vec{u_1}}{\vec{u_1}\cdot\vec{u_1}}\vec{u_1}+\dots+\frac{\vec{y}\cdot\vec{u_p}}{\vec{u_p}\cdot\vec{u_p}}\vec{u_p}$$
and $\vec{z}=\vec{y}-\widehat{\vec{y}}\in W^\perp$. 
2. Uniqueness:
If $\widehat{\vec{y}}+\vec{z}=\widehat{\vec{y'}}+\vec{z'}$, then $$\vec{v}\equiv\widehat{\vec{y}}-\widehat{\vec{y'}}=\vec{z'}-\vec{z}\in W \cap W^\perp\Rightarrow 0=\vec{v}\cdot\vec{v}=||\vec{v}||^2\Rightarrow\vec{v}=\vec{0}$$
```