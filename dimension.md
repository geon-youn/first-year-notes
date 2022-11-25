---
alias: dim
tags: MATH_1B03
---
# Dimension
If $V$ has a [[basis]] of $n$ vectors, then every basis has exactly $n$ vectors. The **dimension** of $V$, is then $n$.

By the [[spanning set theorem]], if $V$ is spanned by a finite set of vectors, then a subset is a basis. So, if $V$ is spanned by a finite set of vectors, then $\text{dim}(V)=n$ (# of vectors in any basis); otherwise $\text{dim}(V)=\infty$

```ad-example
title: Example
Prove that $\text{dim}\mathbb{P}_n=n+1$, where $\mathbb{P}_n= \left\{P(t)=a_0+a_1t+\dots+ a_nt^n, a_j\in\mathbb{R}\right\}$.
1. The set $\{1, t, \dots, t^n\}$ spans $\mathbb{P}_n$ (by def'n).
2. The set is independent because if $P(t) = a_01+a_1t+\dots a_nt^n=\vec{0}$, then:
	- $a_0=P(0)=0$
	- $a_1=P'(0)=0$
	- ...
	- $a_n=n!P^n(0)=0$
3. Therefore, the set is a basis. So, the dimension of $\mathbb{P}_n$ is $n+1$ since there are $n+1$ vectors in its basis.
```

Another way to think of the dimension of $V$ is the number of vectors needed to form a [[linearly independent set]] that spans $V$, which is the basis.

```ad-tip
title: Using the determinant to hint at the dimension
If the determinant of $V$ is $0$, then $V$ is linearly dependent so its dimension is less than $n$. 
```

## Nomenclature
The dimension of $V$ is equivalent to $\text{dim}(V)=n$.

## Proof
Let $B_1$ be a basis of $n$ vectors and $B_2$ be a basis of $p$ vectors. We want to show $n=p$.
1. If $B=B_1$ and $C=C_2$ and $C$ is an [[linear dependence given basis|independent]] set of vectors, then $p\leq{n}$. 
2. If we reverse the roles of $B_1$ and $B_2$, then $n\leq{p}$.
3. Therefore, $n=p$.