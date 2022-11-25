---
alias: eigenvalues, eigenvectors, characteristic equation, characteristic polynomial
tags: MATH_1B03
---
# Solving for Eigenvalues and Eigenvectors
Generally, for an $n\times n$ matrix $A$, 
$$A\vec{v}=\lambda\vec{v}=\lambda\mathbb{I}_n\vec{v}\Leftrightarrow \left[A-\lambda \mathbb{I}_n\right]\vec{v}=\vec{0}$$

```ad-question
title: When does a solution exist?
There exists a nonzero solution $\vec{v}$ iff $\left[A-\lambda \mathbb{I}_n\right]$ is *not* [[invertible matrix theorem|invertible]] thus $\text{det}\left[A-\lambda \mathbb{I}_n\right]=0$. 
```

```ad-tip
title: Calculating [[eigenvalue|eigenvalues]]
From the previous block, we can just find the values of $\lambda$ that satisfy $\text{det}\left[A-\lambda \mathbb{I}_n\right]=0$.
```

```ad-tip
title: Calculating [[eigenvector|eigenvectors]]
After finding the [[eigenvalue|eigenvalues]], we can plug each eigenvalue individually into $\left[A-\lambda \mathbb{I}_n\right]\vec{v}=\vec{0}$ and solve for $\vec{v}$.  
```

```ad-note
title: Nomenclature
$\text{det}\left[A-\lambda \mathbb{I}_n\right]=0$ is the **characteristic equation**.
$\text{det}\left[A-\lambda \mathbb{I}_n\right]$ from the characteristic equation is the **characteristic polynomial**.
So, $\lambda$ is an eigenvalue of A that solves the characteristic equation; i.e., is a root of the characteristic polynomial. 
```
