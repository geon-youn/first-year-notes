---
alias:
tags: MATH_1B03
---
# Gram-Schmidt Process
Given a [[basis]] $\{\vec{x_1},\dots,\vec{x_p}\}$ for a nonzero [[subspace]] $W$ of $\mathbb{R}^n$, we can define using [[perspective projection]]
$$\begin{align*}
\vec{v_1}&=\vec{x_1}\\[10pt]
\vec{v_2}&=\vec{x_2}-\operatorname{proj}_\left\{\vec{v_1}\right\}\vec{x_2}\\[10pt]
\vec{v_3}&=\vec{x_3}-\operatorname{proj}_\left\{\vec{v_1},\vec{v_2}\right\}\vec{x_3}\\
&\vdots\\
\vec{v_p}&=\vec{x_p}-\operatorname{proj}_\left\{\vec{v_1},\dots,\vec{v_{p-1}}\right\}\vec{x_p}
\end{align*}$$

Then $\left\{\vec{v_1},\dots,\vec{v_p}\right\}$ is an [[orthogonal basis]] for $W$. In addition,
$$\operatorname{Span}\left\{\vec{v_1},\dots,\vec{v_p}\right\}=\operatorname{Span}\left\{\vec{x_1},\dots,\vec{x_k}\right\}$$
for $1\leq k \leq p$ with the [[reverse echelon property]].  If we divide each $\vec{v_k}$ by its length such that
$$\vec{u_k}=\frac{\vec{v_k}}{||\vec{v_k}||}$$
we obtain an [[orthonormal basis]] $\left\{\vec{u_1},\dots,\vec{u_p}\right\}$.

```ad-abstract
title: Proof
We already showed $\left\{\vec{v_1},\dots,\vec{v_p}\right\}$ is an [[orthogonal set]] in $W$. Now, we want to show the reverse echelon property by induction:
1. $k=1$: $\operatorname{Span}\left\{\vec{v_1}\right\}=\operatorname{Span}\left\{\vec{x_1}\right\}$ and $\vec{v_1}\neq\vec{0}$
2. $k=2$: 
$\operatorname{Span}\left\{\vec{v_1},\vec{v_2}\right\}\subseteq\operatorname{Span}\left\{\vec{x_1},\vec{x_2},\vec{v_1}\right\}=\operatorname{Span}\left\{\vec{x_1},\vec{x_2}\right\}$
$\operatorname{Span}\left\{\vec{x_1},\vec{x_2}\right\}\subseteq\operatorname{Span}\left\{\vec{v_1},\vec{v_2},\vec{v_1}\right\}=\operatorname{Span}\left\{\vec{v_1},\vec{v_2}\right\}$
$\Rightarrow\operatorname{Span}\left\{\vec{v_1},\vec{v_2}\right\}=\operatorname{Span}\left\{\vec{x_1},\vec{x_2}\right\}$ and $\vec{v_2}\neq\vec{0}$
$\vdots$
Eventually, we show that all $\vec{v_k}$ are nonzero and that the reverse echelon property holds for all $k$. 
```

```ad-tip
title: To be more specific...
$$\begin{align*}
\vec{v_1}&=\vec{x_1}\\[10pt]
\vec{v_2}&=\vec{x_2}-\frac{\vec{x_2}\cdot\vec{v_1}}{\vec{v_1}\cdot\vec{v_1}}\vec{v_1}\\[10pt]
\vec{v_3}&=\vec{x_3}-\frac{\vec{x_3}\cdot\vec{v_1}}{\vec{v_1}\cdot\vec{v_1}}\vec{v_1}-\frac{\vec{x_3}\cdot\vec{v_2}}{\vec{v_2}\cdot\vec{v_2}}\vec{v_2}\\
&\vdots\\
\vec{v_p}&=\vec{x_p}-\frac{\vec{x_p}\cdot\vec{v_1}}{\vec{v_1}\cdot\vec{v_1}}\vec{v_1}-\frac{\vec{x_p}\cdot\vec{v_2}}{\vec{v_2}\cdot\vec{v_2}}\vec{v_2}-\cdots-\frac{\vec{x_p}\cdot\vec{v_{p-1}}}{\vec{v_{p-1}}\cdot\vec{v_{p-1}}}\vec{v_{p-1}}\\
\end{align*}$$

And a great video 
![[gramschmidt.mp4]]
```