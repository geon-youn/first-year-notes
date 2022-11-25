---
alias:
tags: MATH_1B03
---
# Matrix Similarity
Two $n\times n$ matrices $A$, $B$ are **similar** if 
1. $B=P^{-1}AP$, where $P$ is an [[invertible matrix theorem|invertible]] matrix **and** 
2. $A=(P^{-1})^{-1}BP^{-1}=PBP^{-1}$, where $P^{-1}$ is an invertible matrix.  

Similar matrices have the same [[solving eigenvalues and eigenvectors|characteristic polynomial]]. 

```ad-abstract
title: Proof
$\begin{align*}
\text{det}[B-\lambda\mathbb{I}_n]&=\text{det}[P^{-1}AP-\lambda P^{-1}P]\\
								 &=\text{det}[P^{-1}[A-\lambda\mathbb{I}_n]P]\\
								 &=(\text{det}P^{-1})(\text{det}[A-\lambda\mathbb{I}_n])(\det P)\\
								 &=(\text{det}[A-\lambda\mathbb{I}_n])(\text{det}P^{-1})(\det P)\\
								 &=\text{det}[A-\lambda\mathbb{I}_n]
\end{align*}$
```
