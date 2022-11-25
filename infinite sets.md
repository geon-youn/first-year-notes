---
alias: infinite set
tags: MATH_1C03
---
# Infinite Sets
Let $X$ and $Y$ be [[set]]s and let $f:X\mapsto Y$ be a function.
- If $Y$ is finite and $f$ is [[injective]], then $X$ is finite.
	- If $X$ is infinite, then $Y$ is infinite or $f$ is not injective.
- If $X$ is finite and $f$ is [[surjective]], then $Y$ is finite. 
	- If $Y$ is infinite, then $X$ is infinite or $f$ is not surjective. 

```ad-example
title: $\mathbb{N}$ is infinite
Assume for the sake of contradiction that $\mathbb{N}$ is finite. Then, there exists $n$ and a [[bijective|bijection]] $f:\mathbb{N}\mapsto\left\{1,2,\dots,n\right\}$. 

Consider $g:\left\{1,\dots,n+1\right\}\mapsto\mathbb{N},g(i)=i$. This function is injective.

Then, $f(g(n))$ is injective since $g$ is injective and $f$ is bijective. 

But $n+1>n$ so by the [[pigeonhole principle]], $f(g(x))$ is not injective, which is a contradiction so $\mathbb{N}$ is infinite. 
```