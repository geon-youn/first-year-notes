---
alias:
tags: MATH_1C03 MATH_1DM3
---
# Permutations
Given two non-negative [[integers]] $n$ and $k$, where $n$ is the number of elements in a [[set]] and $k$ is the size of the subsets we want, we denote the **permutation of k in n** as **n "p" k** such that
$$P(n,k)=\,^nP_k=\frac{n!}{(n-k!)}$$
Permutations preserve **order**. If we don't want our sets to be ordered, then we use [[combination]]s instead. 

```ad-note
A permutation of a set of distinct sets is an ordered arrangement of these objects. An ordered arrangement of $k$ elements of a set is called an $k$-permutation.
```

```ad-abstract
If $n$ is a positive integer and $k$ is an integer with $1\leq k \leq n$, then there are
$$P(n,k) = n(n-1)(n-2)\cdots(n-k+1)$$
$k$-permutations of a set with $n$ distinct elements.

If $n$ and $k$ are integers with $1\leq k\leq n$ then
$$P(n,k)=\frac{n!}{(n-k)!}$$

Proof:
The first element can be chosen in $n$ ways. The second in $n-1$ ways and so on until there are $(n-(k - 1))$ ways to choose the last element. 
```