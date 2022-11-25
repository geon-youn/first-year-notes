---
alias:
tags: MATH_1B03
---
# Distinct Eigenvalues Theorem

If $\left\{\lambda_1,\dots,\lambda_r\right\}$ are distinct [[eigenvalue|eigenvalues]] of an $n\times n$ matrix $A$, then any corresponding [[eigenvector|eigenvectors]] $\left\{\vec{v_1},\dots,\vec{v_r}\right\}$ are [[linear dependence|linearly independent]].

```ad-abstract
title: Proof
1. Suppose in order to derive a contradiction that $\left\{\vec{v_1},\dots,\vec{v_r}\right\}$ is dependent. 
2. Then, there is a *least* integer $p$ such that $\vec{v_{p+1}}=c_1\vec{v_1}+\dots+c_p\vec{v_p}$. 
3. Then, $A\vec{v_{p+1}}=A(c_1\vec{v_1}+\dots+c_p\vec{v_p})$.
4. Which becomes $A\vec{v_{p+1}}=c_1A\vec{v_1}+\dots+c_pA\vec{v_p}$.
	- By the definition of eigenvalue|eigenvalues, $\lambda_{p+1}\vec{v_{p+1}}=c_1\lambda_1\vec{v_1}+\dots+c_p\lambda_p\vec{v_p}$.
	- Similarly, if $A=\lambda_{p+1}$, then $\lambda_{p+1}\vec{v_{p+1}}=c_1\lambda_{p+1}\vec{v_1}+\dots+c_p\lambda_{p+1}\vec{v_p}$.
5. Subtracting the two equations, $\lambda_{p+1}\vec{v_{p+1}}=c_1(\lambda_1-\lambda_{p+1})\vec{v_1}+\dots+c_p(\lambda_p-\lambda_{p+1})\vec{v_p}=\vec{0}$.
6. Then, each $c_k(\lambda_k-\lambda_{p+1})=0$ but each $\lambda_j$ is distinct, so each $c_k$ is $0$, thus a contradiction since not all $c_k$ can be $0$.  
6. Therefore, $\left\{\vec{v_1},\dots,\vec{v_r}\right\}$ must be linearly independent. 
```
