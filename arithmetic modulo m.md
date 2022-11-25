---
alias: arithmetic modulo, mod
tags: COMPSCI_1DM3
created: February 17, 2022 18:48
---
# Arithmetic Modulo $m$
Let $Z_m$ be the set of nonnegative integers less than $m$: $\{0, 1, \dots, m-1\}$. 

**Addition modulo $m$**: The operation $+_m$ is defined as $a+_mb=(a+b)\operatorname{mod}m$.

**Multiplication modulo $m$**: The operation $\cdot_m$ is defined as $a\cdot_mb=(a\cdot b)\operatorname{mod}m$.

Using these operations is said to be doing *arithmetic modulo $m$*.

## Properties
Arithmetic modulo $m$ preserves closure, associativity, commutativity, identity elements, additive inverses, and distributivity.
```ad-warning
Multiplicative inverses does not always exist.
```
### Closure
If $a$ and $b$ belong to $Z_m$, then $a+_mb$ and $a\cdot_mb$ belong to $Z_m$. 
### Associativity
If $a,b,$ and $c$ belong to $Z_m$, then
$$(a+_mb)+_mc=a+_m(b+_mc)$$
and
$$(a\cdot_mb)\cdot_mc=a\cdot_m(b\cdot_mc)$$
### Commutativity
If $a$ and $b$ belong to $Z_m$, then
$$a+_mb=b+_ma$$
and
$$a\cdot_mb=b\cdot_ma$$
### Identity Elements
The elements $0$ and $1$ are identity elements for addition and multiplication modulo $m$, respectively:

$$a+_m0=a$$
$$a\cdot_m1=a$$
### Additive Inverses
If $a\neq0$ belongs to $Z_m$, then $m-a$ is the additive inverse of a modulo $m$ and $0$ is its own additive inverse.
$$a+_m(m-a)=0$$
and
$$0+_m0=0$$
### Distributivity
If $a,b,$ and $c$ belong to $Z_m$, then
$$a\cdot_m(b+_mc)=(a\cdot_mb)+_m(a\cdot_mc)$$
and
$$(a+_mb)\cdot_mc=(a\cdot_mc)+_m(b\cdot_mc)$$