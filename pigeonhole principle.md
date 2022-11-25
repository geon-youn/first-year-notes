---
alias: 
tags: MATH_1C03 MATH_1DM3
---
# The Pigeonhole Principle
Let $X$ and $Y$ be finite [[set]]s with the [[cardinality]] of $X$ equal to $m$ and $|Y|=n$ and let $f:X\mapsto Y$ be a function.
- If $f$ is [[injective]], then $m\leq n$.  
- If $f$ is [[surjective]], then $m\geq n$. 
- If $f$ is [[bijective]], then $m=n$. 

```ad-note
If $k$ is a positive integer and $k+1$ objects are placed into $k$ boxes, then at least one box contains two or more objects.
```

## Contrapositive of Pigeonhole Principle
If $m>n$, then $f$ is not injective. 

Let $X$ be the set of pigeons and $Y$ be the set of pigeonholes. If $m > n$, then there are more pigeons than pigeonholes, so some poor pigeon is going to be stuffed into a pigeonhole that already contains a pigeon. Therefore, $f$ is not injective. 

![[Pasted image 20211129171232.png]]

```ad-abstract
Suppose none of the $k$ boxes has more than one object. Then the total number of objects would be at most $k$. This contradicts the statement that we have $k+1$ objects.
```

## Generalized Pigeonhole Principle
If $N$ objects are placed into $k$ boxes, then there is at least one box containing at least $\lceil N/k \rceil$ objects.

$$k\left(\left\lceil \frac{N}{k}\right\rceil - 1\right) < k \left(\left(\frac{N}{k} + 1\right) - 1\right) = N$$

```ad-example
Among 100 people there are at least $\lceil 100/12 \rceil = 9$ people who were born in the same month.
```