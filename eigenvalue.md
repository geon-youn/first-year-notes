---
alias:
tags: MATH_1B03
---
# Eigenvalues
If the [[image]] of a vector $\vec{v}$ through the [[linear transformation]] by the matrix $A$ is equal to $\lambda\vec{v}$, then $\lambda$ is said to be the **eigenvalue** to the matrix, and $\vec{v}$ is the [[eigenvector]] corresponding to the eigenvalue $\lambda$.

## Alternative Explanation
Let $T$ be a linear transformation $T:V\mapsto V$ where $V$ is a [[vector space]], then if $A$ is the [[standard matrix]] of $T$, then $A\vec{v}=\lambda\vec{v}$, where $\lambda$ is the eigenvalue. 

## Alternative Definition
The eigenvalue of a matrix $A$ is a root to $A$'s [[solving eigenvalues and eigenvectors|characteristic polynomial]].

# Transpose
Let $\lambda$ be a root to the characteristic polynomial for a matrix $A$. So $\lambda$ is a root for $\det(A-\lambda\mathbb{I}_n)$. We know $\det A=\det A^T$ and $(A-\lambda\mathbb{I}_n)^T=A^T-\lambda\mathbb{I}_n$. So, the characteristic polynomial for $A^T$ is equal to that of $A$; therefore, if $\lambda$ is an eigenvalue for $A$, then it is also an eigenvalue for $A^T$. 