---
alias:
tags: MATH_1B03
---
# Subspaces
A **subspace** of a [[vector space]] $V$ is a subset $H$ of $V$ that has three properties:

| Property # | Meaning                            | Property                                                                       |
| ---------- | ---------------------------------- | ------------------------------------------------------------------------------ |
| 1          | Existence of zero vector           | $\vec{0}\in{H}$                                                                |
| 2          | Closed under vector addition       | for each $\vec{u}$ and $\vec{v}$ in $H$, the sum $\vec{u}+\vec{v}$ is in $H$   |
| 3          | Closed under scalar multiplication | for each $\vec{u}$ in $H$ and each scalar $c$, the vector $c\vec{u}$ is in $H$ | 

If $H$ satisfies these three properties, then $H$ is a [[vector space]] with $+$,$\cdot$ **restricted** to $H$.

```ad-abstract
title: Proof
Properties (1) to (10) are obvious except for (5):
If $\vec{u}\in{H}$, then $(-1)\vec{u}\in{H}$, then by the [[identity of additive inverses]], $-\vec{u}=(-1)\vec{u}\in{H}$.
```

```ad-tip
If $\vec{v_1},\dots,\vec{v_p}$ are in a vector space $V$, then its [[span]] is a subspace of $V$.
```