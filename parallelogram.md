---
alias:
tags: MATH_1B03
---
# Area of Parallelogram
The area of a parallelogram spanned by $\left\{\vec{v_1},\vec{v_2}\right\}$ is its **absolute** [[determinant]] such that
$$\text{Area}=\left|\det \begin{bmatrix}\vec{v_1} & \vec{v_2}\end{bmatrix}\right|$$

# Volume of Parallelepiped
The volume of a parallelepiped spanned by $\left\{\vec{v_1},\vec{v_2}, \vec{v_3}\right\}$ is its **absolute** [[determinant]] such that
$$\text{Volume}=\left|\det \begin{bmatrix}\vec{v_1} & \vec{v_2} & \vec{v_3}\end{bmatrix}\right|$$

```ad-abstract
title: Proof
Let $A$, an [[invertibility|invertible]] matrix, be the product of [[elementary matrix|elementary matrices]] such that
$$A=E_pE_{p-1}\dots E_1 \mathbb{I}_n \Rightarrow \det A=\det (E_pE_{p-1}\dots E_1 \mathbb{I}_n)$$
So, if we apply an [[elementary row operation]] $E$ on $A$, then if $\text{area}A=|\det A|$, then $\text{area}(EA)=|\det (EA)|$. Similarly, we can prove this claim is true for volume instead. 
```

The same is true for a [[linear transformation]] instead of an elementary row operation!

```ad-abstract
title: Proof
Let $T$ be a linear transformation and $S$ be the original matrix (the parallelegram/parallelepiped). 
Claim: $|\det(T(S))|=|\det A||\det S|$, where $A$ is the [[standard matrix]] of $T$.
Proof:
$$
\begin{align*}|\det(T(S))|&=|\det \begin{bmatrix}A \vec{v_1} & \cdots & A \vec{v_n}\end{bmatrix}|\\
						  &=|\det (A\begin{bmatrix}\vec{v_1} & \cdots & \vec{v_n}\end{bmatrix})|\\
						  &=|\det(A)\det(\begin{bmatrix}\vec{v_1} & \cdots & \vec{v_n}\end{bmatrix})|\\
						  &=|\det(A)\det(S)|
\end{align*}$$
```

```ad-warning
title: [[elementary row operation|Elementary row operations]] affect the area/volume (determinant)!
Let $B$ be obtained from $A$ by an [[elementary matrix]] $E$ such that $B=EA$. 
Then, 
1. if $E$ is a [[replacement]]:
$$|\det B| = |\det E\det A|=|\det A|$$
2. if $E$ is an [[interchanging|interchange]]:
$$|\det B| = |\det E\det A|=|-\det A|=|\det A|$$
3. if $E$ is a [[scaling]] by $r$:
$$|\det B| = |\det E\det A|=|r\det A|$$

Therefore, only scaling has an effect on the area/volume. 
```