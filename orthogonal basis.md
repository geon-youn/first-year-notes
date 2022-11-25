---
alias:
tags: MATH_1B03
---
# Orthogonal Basis
$S=\{\vec{u_1},\dots,\vec{u_p}\}\subset\mathbb{R}^n$ is an **orthogonal basis** for a [[subspace]] $W$ in $\mathbb{R}^n$ if $S$ is both an [[orthogonal set]] and a [[basis]] for $W$. 

If $S$ is an orthogonal basis for a subspace $W$, then if $\vec{y}\in W$, then $\vec{y}=c_1\vec{u_1}+\dots+c_p\vec{u_p}$, where $$c_k=\frac{\vec{y}\cdot\vec{u_k}}{||\vec{u_k}||^2}$$

```ad-abstract 
title: Proof
Similar to the proof given in [[linear dependence given set]], we can apply the [[inner product]] to both sides:
$$\begin{align*}
\vec{y}\cdot\vec{u_k}&=c_1\vec{u_1}\cdot\vec{u_k}+\dots+c_p\vec{u_p}\cdot\vec{u_k}\\
&=c_k\vec{u_k}\cdot\vec{u_k}\\
&=c_k||\vec{u_k}||^2\\
c_k&=\frac{\vec{y}\cdot\vec{u_k}}{||\vec{u_k}||^2}
\end{align*}$$
```

```ad-info
title: Important case
If $||\vec{u_k}||=1$, then 
$$\vec{y}=(\vec{y}\cdot\vec{u_1})\vec{u_1}+\dots+(\vec{y}\cdot\vec{u_p})\vec{u_p}$$
$\vec{y}$ is a [[linear combination]] of the orthogonal basis vectors, where the coefficients are the inner product of $\vec{y}$ and that vector.  
```