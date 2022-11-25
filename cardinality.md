---
alias:
tags: MATH_1C03
---
# Cardinality
The **cardinality** (how many distinct things there are; counting) of a [[set]] $X$ is denoted $|X|$. 

$|\emptyset|=0$

$|X|=n$ if there exists a [[bijective|bijection]] $f:X\mapsto\left\{1,2,\dots,n\right\}$. By counting, we define a bijective function where we assign each element a number. 

$X$ is **finite** if there exists a non-negative integer $n$ with $|X|=n$.

## Equality
Two cardinalities are **equal**, $|X|=|Y|$, if there exists a **bijection** $f : X \mapsto Y$. 


```ad-example
title: $|\mathbb{N}|=|\mathbb{Z}|$
Find a bijection $f:\mathbb{Z}\mapsto\mathbb{N}$
$$f(n)=\left\{\begin{array}{ll}2n & \text{if } n > 0\\
1 - 2n & \text{if }n \leq 0\end{array}\right.$$
So $|\mathbb{N}|=|\mathbb{Z}|$.
```

```ad-example
title: $|(0, 1)|=|\mathbb{R}|$
Let $f:(0,1)\mapsto(\frac{-\pi}{2},\frac{\pi}{2})$, where $f(x)=\pi x - \frac{\pi}{2}$, which is a bijection.

Let $g:(\frac{-\pi}{2},\frac{\pi}{2})\mapsto\mathbb{R}$, where $g(x)=\tan(x)$, which is a bijection. 

So, $g\circ f:(0,1)\mapsto\mathbb{R}$, where $g\circ f(x)=\tan(\pi x - \pi/2)$, which is a bijection. 

Therefore, $|(0, 1)|=|\mathbb{R}|$. 
```

```ad-example
title: $|(a, b)|=|\mathbb{R}|$
Let $f:(a,b)\mapsto(\frac{-\pi}{2},\frac{\pi}{2})$, where $f(x)=\pi \frac{x-a}{b-a} - \frac{\pi}{2}$, which is a bijection.

Let $g:(\frac{-\pi}{2},\frac{\pi}{2})\mapsto\mathbb{R}$, where $g(x)=\tan(x)$, which is a bijection. 

So, $g\circ f:(a,b)\mapsto\mathbb{R}$, where $g\circ f(x)=\tan(\pi \frac{x-a}{b-a} - \pi/2)$, which is a bijection. 

Therefore, $|(a, b)|=|\mathbb{R}|$. 
```

## Injection 
If there is an [[injective|injection]] from $A$ to $B$, the cardinality of $A$ is less or the same as the cardinality of $B$ and we write $|A|\leq |B|$.

If $A$ and $B$ have different cardinality, then we write $|A|<|B|$ instead.