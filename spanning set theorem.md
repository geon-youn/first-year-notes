---
alias:
tags: MATH_1B03
---
# Spanning Set Theorem
Let $S\equiv\{\vec{v_i}\}^{p}_{i=1}\subset{V}$ vector space.
If $H=\text{Span}S$, then
1. If some $\vec{v_k}$ is a [[linear combination]] of other $\vec{v_j}$'s, then $H=\text{Span}S'$, where
$$S'=S\setminus\{\vec{v_k}\}=\{\vec{v_1},\dots,\vec{v_{k-1}},\vec{v_{k+1}},\dots,\vec{v_p}\}$$

```ad-abstract
title: Proof
If $$\vec{v_k}=d_1\vec{v_1}+\dots+d_{k-1}\vec{v_{k-1}}+d_{k+1}\vec{v_{k+1}}+\dots+d_p\vec{v_p}$$ 
then, if $$\vec{x}=c_1\vec{v_1}+\dots+c_p\vec{v_p}$$
then, when we substitute in $\vec{v_k}$, $$\vec{x}=(c_1+c_kd_1)\vec{v_1}+\dots+(c_{k-1}+c_kd_{k-1})\vec{v_{k-1}}+(c_{k+1}+c_kd_{k+1})\vec{v_{k+1}}+\dots+(c_p+c_kd_p)\vec{v_p}$$
which shows that we don't need $\vec{v_k}$. 
```

2. If $H\neq\{\vec{0}\}$, then some subset of $S$ is a [[basis]] for $H$. 

```ad-abstract
title: Proof
If $S$ is [[linearly independent set|linearly independent]], then it is already a basis for $H$. 
Otherwise, you can make $S$ linearly independent by (1). 
```