---
alias: stochastic matrix
tags: MATH_1B03
---
# Stochastic Matrix
A matrix $A=[\vec{a}_1,\vec{a}_2]$ is **stochastic** if both columns are [[probability vector]]s.

If $A$ is multiplied by a probability vector, the resulting vector is also a probability vector. 

$1$ is an [[eigenvalue]] for $A$. 

## Proof
1. The matrix multiplication $A\vec{v}$ returns a vector whose components sum is $v_1\vec{a_1}+v_2\vec{a_2}$. 
2. Since $\vec{a_1}$ and $\vec{a_2}$ are both probability vectors, $v_1\vec{a_1}=v_1$ and $v_2\vec{a_2}=v_2$. 
3. So, $v_1\vec{a_1}+v_2\vec{a_2}=v_1+v_2=1$.
4. Therefore, the resulting vector is also a probability vector.
