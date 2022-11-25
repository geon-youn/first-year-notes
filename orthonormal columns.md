---
alias:
tags: MATH_1B03
---
# Orthonormal Columns
An $m \times n$ matrix $U=[\vec{u_1}\dots\vec{u_n}]$ has **orthonormal columns** iff $U$ [[transpose]] times $U$ is equal to the [[identity matrix]] such that
$$U^TU=\mathbb{I}_n$$

```ad-abstract
title: Proof
$$
\begin{align*}
U^TU&=\begin{bmatrix}
\vec{u_1}^T\\\vdots\\\vec{u_n}^T
\end{bmatrix}\begin{bmatrix}
\vec{u_1} & \cdots & \vec{u_n}
\end{bmatrix}\\
    &=\left[\begin{array}{ccccc}
	u_{11}u_{11}&&&&\\
	&\ddots&&u_{ji}u_{ij}&\\
	&&\ddots&&\\
	&u_{ji}u_{ij}&&\ddots&\\
	&&&&u_{nn}u_{nn}
	\end{array}\right]\\
	&=\left[\begin{array}{ccccc}
	1&&&&\\
	&\ddots&&0's&\\
	&&\ddots&&\\
	&0's&&\ddots&\\
	&&&&1
	\end{array}\right]\\
	&=\mathbb{I}_n
\end{align*}
$$
```

If $U$ has orthonormal columns, then
1. $||U\vec{x}|| = ||\vec{x}||$;
2. $U\vec{x}\cdot U\vec{y}=\vec{x}\vec{y}$ for all $\vec{x},\vec{y}\in\mathbb{R}^n$;
3. $U\vec{x}\cdot U\vec{y}=0\Leftrightarrow \vec{x}\cdot\vec{y}=0$.

```ad-abstract
title: Proof
If (2) then (1), and (3) is "obvious" from (2):
$$\begin{align*}
U\vec{x}\cdot U\vec{y}&=[U\vec{x}]^T[U\vec{y}]\\[10pt]
					  &=[\vec{x}^TU^T][U\vec{y}]\\[10pt]
					  &=\vec{x}^T[U^TU]\vec{y}\\[10pt]
					  &=\vec{x}^T\vec{y}\\[10pt]
					  &=\vec{x}\cdot\vec{y}
\end{align*}$$
```

```ad-tip
title: Special case
If $m=n$, that is $U$ is a square matrix, since $U$ has orthonormal columns iff $U^TU=\mathbb{I}_n$, then $U$ is invertible and $U^{-1}=U^T$. 
```