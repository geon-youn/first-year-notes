---
alias:
tags: MATH_1B03
---
# Determinants
The **determinant** of a $n \times n$ matrix $A$ is a scalar that denotes how much the area or volume formed by the [[unit vector|unit vectors]] in $\mathbb{R}^n$ are scaled by a [[standard matrix]] $A$ such that $\det A=\det (A \mathbb{I}_n)=\det A \det \mathbb{I}_n = \det A \cdot 1$. 

Then, if the determinant of $A$ is 0, $A$ is not [[invertibility|invertible]] because it does not [[span]] $\mathbb{R}^n$ ([[invertible matrix theorem]]) since $A$ squishes $\mathbb{I}_n$ into a lower [[dimension]]. Conversely, a $n \times n$ matrix $A$ is invertible iff $\det A \neq 0$. 

```ad-info
The determinant operation can be expanded for a [[matrix product]]:
$$\det (AB) = \det A \det B$$
So, if $A$ or $B$ is not invertible, $AB$ or $BA$ is not invertible. But, given $AA^{-1}=\mathbb{I}_n$, then $\det A \det A^{-1} = \det \mathbb{I}_n = 1$. So,
$$\det{A^{-1}}=\frac{1}{\det A}$$
```

```ad-warning
title: [[elementary row operation|Elementary row operations]] affect the determinant!
Let $B$ be obtained from $A$ by an [[elementary matrix]] $E$ such that $B=EA$. 
Then, 
1. if $E$ is a [[replacement]]:
$$\det B = \det E\det A=\det A$$
2. if $E$ is an [[interchanging|interchange]]:
$$\det B = \det E\det A=-\det A$$
3. if $E$ is a [[scaling]] by $r$:
$$\det B = \det E\det A=r\det A$$
```

```ad-tip
The determinant of $A$ [[transpose]] is equal to the determinant of $A$:
$$\det A^{T}=\det A$$
We can then apply **column operations** and they behave the same way as row operations to the determinant. 
```

```ad-note
title: Quick formula for $2 \times 2$ matrix inverse
For a $2 \times 2$ matrix $A=\begin{bmatrix}a & b\\c & d \end{bmatrix}$, if $ad-bc\neq 0$, then $A$ is [[invertibility|invertible]] and $$A^{-1}=\frac{1}{ad-bc}\begin{bmatrix}d & -b\\-c & a \end{bmatrix}$$
Otherwise, $A$ is not invertible. 
```