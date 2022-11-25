---
alias:
tags: MATH_1B03
---
# Linear Dependence Given Set
If $S$ is an [[orthogonal set]] and all vectors in $S$ are nonzero, then $S$ is [[linearly independent set|linearly independent]] and hence is a [[basis]] for the [[subspace]] [[span|spanned]] by $S$.

```ad-abstract 
title: Proof
Let $\vec{0}=c_1\vec{u_1}+\dots+c_p\vec{u_p}$, then if we apply an [[inner product]] to both sides, $0=\vec{0}\cdot\vec{u_k}=c_1\vec{u_1}\cdot\vec{u_k}+\dots+c_p\vec{u_p}\cdot\vec{u_k}=c_k\vec{u_k}\cdot\vec{u_k}=c_k||\vec{u_k}||^2\Rightarrow c_k=0$ since $||\vec{u_k}||^2\neq 0$. 
Since $c_k=0$, $S$ is linearly independent.  
```