---
alias: linearly dependent, linearly independent
tags: MATH_1B03
---
# Linear Dependence
The columns of a matrix $A$ are **linearly independent** iff the equation $A\vec{x}=\vec{0}$ has *only* the [[trivial solution]]. Otherwise, the columns are **linearly dependent** since one of the columns is a [[linear combination]] of the other columns. 

```ad-tip
If a set $S=\left\{\vec{v_1},\dots,\vec{v_p}\right\}$ in $\mathbb{R}^n$ contains the zero vector, then the set is **linearly dependent**.
```

```ad-tip
If a set contains more vectors than there are entries in each vector, then the set is **linearly dependent**. That is, any set $\left\{\vec{v_1},\dots,\vec{v_p}\right\}$ in $\mathbb{R}^n$ is linearly dependent if $p>n$. 
```