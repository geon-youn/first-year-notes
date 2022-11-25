---
alias: binomial coefficient
tags: MATH_1C03
---
# Combinations
Given two non-negative [[integers]] $n$ and $k$, where $n$ is the number of elements in a [[set]] and $k$ is the size of the subsets we want, we denote the **combination of k in n** as **n "choose" k** such that
$$^nC_k=\begin{pmatrix}n\\k\end{pmatrix}=\frac{n!}{k!(n-k!)}$$
The combination is different from [[permutation]] because we don't care about the **order** of elements in the new sets. 

```ad-note
A $k$-combination of elements of a set is an unordered selection of $k$ elements from the set. Thus, a $k$-combination is simply a subset of the set with $k$ elements.

The number of $k$-combinations of a set with $n$ distinct elements is denoted by $C(n,r)$. The notation is $\left(\begin{matrix}n\\c\end{matrix}\right)$ is also used and is called a **binomial coefficient**. 
```

```ad-abstract
The number of $k$-combinations of a set with $n$ elements, where $n\geq k \geq 0$, equals
$$C(n,k)=\frac{n!}{k!(n-k)!}$$

Proof:
By the product rule $P(n, k) = C(n, k) \cdot P(k, k)$, therefore 
$$C(n,k) = \frac{P(n,r)}{P(k,k)} = \frac{n!/(n-k)!}{k!/(k-k)!} = \frac{n!}{k!(n-k)!}$$
```

```ad-abstract
Let $n$ and $k$ be nonnegative integers with $k\leq n$. Then $C(n, k)=C(n, n-k)$.

Proof:
Denominator becomes the same (trust me). 
```