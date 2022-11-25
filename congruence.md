---
alias: congruent, equivalent
tags: COMPSCI_1DM3
created: February 17, 2022 14:10
---
# Congruence
If $a$ and $b$ are integers and $m$ is a positive integer, then $a$ is *congruent* to $b$ *modulo* $m$ if $m$ [[division|divides]] $a-b$. 

$a\equiv b(\operatorname{mod}m)$ says that $a$ is congruent to $b$ modulo $m$; we say it is a congruence and that $m$ is its modulus.

Two integers are congruent mod $m$ iff they have the same [[division algorithm|remainder]] when divided by $m$.

If $a$ is not congruent to $b$ modulo $m$, we write $a\not\equiv b(\operatorname{mod}m)$.

The integers $a$ and $b$ are congruent modulo $m$ iff there is an integer $k$ such that $a=b + km$. 

## Difference between ($\operatorname{mod} m$) and $\operatorname{mod}m$
In $a\equiv b(\operatorname{mod}m)$ is a relation on the set of integers, whereas in $a\operatorname{mod} b$, $\operatorname{mod}$ denotes a function.

```ad-example
Let $a$ and $b$ be integers, and let $m$ be a positive integer. Then $a\equiv b(\operatorname{mod} m)$ iff $a\operatorname{mod} m = b\operatorname{mod} m$. 
```

## Congruences of Sums and Products
If $a\equiv b(\operatorname{mod}m)$ and $c\equiv d(\operatorname{mod}m)$, then
$$a+c\equiv b + d(\operatorname{mod}m)$$
and
$$ac\equiv bd(\operatorname{mod}m)$$

## Algebraic Manipulation of Congruences
Multiplying or adding both sides of a valid congruence by an integer preserves validity. If $a\equiv b(\operatorname{mod}m)$, then $ca\equiv cb(\operatorname{mod}m)$ and $c+a\equiv c+b(\operatorname{mod}m)$, where $c$ is any integer. However, dividing a congruence by an integer does not always produce a valid congruence.
## Computing the $\operatorname{mod}m$ Function of Products and Sums
We can use the previous point to find the remainder of the product or sum of two integers when divided by $m$ from the remainders when each is divided by $m$:
$$(a+b)(\operatorname{mod}m)=((a\operatorname{mod}m)+(b\operatorname{mod}m))\operatorname{mod}m$$
and
$$ab\operatorname{mod}m=((a\operatorname{mod}m)(b\operatorname{mod}m))\operatorname{mod}m$$