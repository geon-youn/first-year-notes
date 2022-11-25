---
alias: diagonalizable, linearly independent eigenvectors
tags: MATH_1B03
---
# Diagonalization
If a matrix $D$ is a [[diagonal]] matrix, the [[eigenvalue]]s of $D$ are the [[triangular eigenvalue theorem|diagonal]] entries of $D$. 

$A$ is **diagonalizable** (i.e. $A$ is [[similarity|similar]] ($A=PDP^{-1}$) for some invertible matrix $P$ and diagonal $D$) iff $A$ has $n$ [[linear dependence|independent]] [[eigenvector]]s. Then, if $\vec{p_1},\dots,\vec{p_n}$ are the independent eigenvectors then $P=[\vec{p_1},\dots,\vec{p_n}]$. $P$ will then be invertible since its columns are linearly independent (#5 in the [[invertible matrix theorem]]). So, $D$ will be a diagonal matrix whose main diagonals is the corresponding eigenvalues to $\vec{p_1},\dots,\vec{p_n}$:
$$D=\begin{bmatrix}\lambda_1&&\text{0's}\\
&\ddots&\\
\text{0's}&&\lambda_n\end{bmatrix}$$
such that $A\vec{p_k}=\lambda_k\vec{p_k}$. 

## Proof ($\Rightarrow$)
$$\begin{align*}
A&=PDP^{-1}\\
AP&=PD\\
[A\vec{p_1}\dots A\vec{p_n}]&=[\lambda_1\vec{p_1}\dots\lambda_n\vec{p_n}]
\end{align*}$$
and since $A\vec{p_k}=\lambda_k\vec{p_k}$, then $AP=PD$ so $A=PDP^{-1}$. 

## Proof ($\Leftarrow$)
Suppose $A=PDP^{-1}$, then $AP=PD$. So, since $AP[A\vec{p_1}\dots A\vec{p_n}]$, we can use the fact that $A\vec{p_k}=\lambda_k\vec{p_k}$ to show $AP=[\lambda_1\vec{p_1}\dots\lambda_n\vec{p_n}]$ which is $PD$, so $P$ has $n$ linearly independent eigenvectors. 

## What if $p=n$?
If $A$ is an $n \times n$ matrix and has $n$ distinct eigenvalues, then $A$ is diagonalizable since the eigenvectors are [[distinct eigenvalues theorem|distinct]].

But, if $A$ does have some duplicates and has eigenvalues $\{\lambda_1,\dots,\lambda_p\}$, where $0 \leq p \leq n$, then
1. For each $1\leq k\leq p$, the [[dimension]] of the [[eigenspace]] for $\lambda_k$ is less than or equal to the [[multiplicity]] of $\lambda_k$. 
2. $A$ is diagonalizable
	- iff $\sum^{p}_{k=1}\dim(\operatorname{Eigenspace}(\lambda_k))=n$ ($A$ has $n$ eigenvectors).
	- iff the [[solving eigenvalues and eigenvectors|characteristic equation]] of $A$ can be factored as a product of linear factors where each root is real:
	$$\det[A-\lambda\mathbb{I}_n]=(-1)^n(\lambda-r_1)\dots(\lambda-r_n)$$
	- iff $\dim(\operatorname{Eigenspace}(\lambda_k))$ is equal to the multiplicity of $\lambda_k$ for all $1\leq k\leq p$. 
3. If $A$ is diagonalizable, let $B_k$ be the [[basis]] for $\operatorname{Eigenspace}(\lambda_k)$, then $\bigcup^n_{k=1}B_k$ is an eigenvector basis for $\mathbb{R}^n$. 