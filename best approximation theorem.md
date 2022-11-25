---
alias:
tags: MATH_1B03
---
# Best Approximation Theorem
Let $W$ be a [[subspace]] of $\mathbb{R}^n$, $\vec{y}$ be any vector in $\mathbb{R}^n$, and $\widehat{\vec{y}}$ be the [[orthogonal projection]] of $\vec{y}$ onto $W$. Then, $\widehat{\vec{y}}$ is the closest point in $W$ to $\vec{y}$ such that 
$$||\vec{y}-\widehat{\vec{y}}|| < ||\vec{y}-\vec{v}||$$
for all $\vec{v}\in{W}$ distinct from $\widehat{\vec{y}}$.

```ad-abstract
title: Proof
We know
$$(\vec{y}-\widehat{\vec{y}})=\vec{z}\perp(\vec{y}-\vec{v})$$
By rearranging,
$$\vec{y}-\vec{v}=(\vec{y}-\widehat{\vec{y}})+(\widehat{\vec{y}}-\vec{v})$$
Then, by the [[Pythagorean theorem]],
$$||\vec{y}-\vec{v}||^2=||\vec{y}-\widehat{\vec{y}}||^2+||\widehat{\vec{y}}-\vec{v}||^2$$
Then,
$$||\vec{y}-\vec{v}|| > ||\vec{y}-\widehat{\vec{y}}||$$
Since 
$$||\vec{y}-\vec{v}||^2-||\widehat{\vec{y}}-\vec{v}||^2=||\vec{y}-\widehat{\vec{y}}||^2$$
```