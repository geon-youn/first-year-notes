---
alias: invertible
tags: MATH_1B03
---
# Invertibility for Matrices
Let $A$ be a $n \times n$ matrix. $A$ is **invertible** if there exists a $n \times n$ matrix $A^{-1}$ with
$$A^{-1}A=\mathbb{I}_n=AA^{-1}$$
such that the [[matrix product]] of $A$ and $A^{-1}$ **in any order** results in the [[identity matrix]]. The [[invertible matrix theorem]] has several logically equivalent statements to show that a matrix is invertible. 

```ad-tip
title: Alternative explanation
An $n \times n$ matrix $A$ is invertible iff $A$ is [[row equivalent]] to $\mathbb{I}_n$, and in this case, any sequence of [[elementary row operation|elementary row operations]] that reduces $A$ to $\mathbb{I}_n$ also transforms $\mathbb{I}_n$ to $A^{-1}$. 
```

```ad-tip
title: **Another** explanation
Let $A$ and $B$ be $n \times n$ matrices. If $AB=\mathbb{I}_n$, then $A$ and $B$ are both invertible with $B=A^{-1}$ and $A=B^{-1}$. 
```