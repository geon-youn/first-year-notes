---
alias:
tags: MATH_1B03
---
# Vector Space
A **vector space** is a nonempty set $V$ of objects, called [[vector|vectors]], on which are defined **two** operations, called *addition* and *multiplication by scalars*, subject to **ten axioms** listed below. The axioms must hold for all vectors $\vec{u}$, $\vec{v}$, and $\vec{w}$ in $V$ and for all scalars $c$ and $d$.

| Rule | Meaning                            | Rule                                                                                                                            |
| ---- | ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| 1    | Closure under addition             | the sum of $\vec{u}$ and $\vec{v}$, denoted by $\vec{u} + \vec{v}$, is in $V$                                                   | 
| 2    | Commutative with addition          | $\vec{u} + \vec{v}=\vec{v} + \vec{u}$                                                                                           |
| 3    | Associative with addition          | $(\vec{u} + \vec{v})+\vec{w}=\vec{u} + (\vec{v}+\vec{w})$                                                                       |
| 4    | Existence of a zero vector         | there exists a **unique** $\vec{0}$ such that $\vec{u} + \vec{0}=\vec{u}$                                                       |
| 5    | Additive inverses                  | for all $\vec{u}$ in $V$, there exists a **unique** $-\vec{u}$ such that $\vec{u}+(-\vec{u})=\vec{u}+(-1)\vec{u}=\vec{0}$ |
| 6    | Closed under scalar multiplication | the scalar multiple of $\vec{u}$ by $c$, denoted by $c\vec{u}$ is in $V$                                                        |
| 7    | Distributive by scalars            | $c(\vec{u}+\vec{v})=c\vec{u}+c\vec{v}$                                                                                          |
| 8    | Distributive by vectors            | $(c + d)\vec{u}=c\vec{u}+d\vec{u}$                                                                                              |
| 9    | Associative with scalars           | $c(d\vec{u})=(cd)\vec{u}$                                                                                                       |
| 10   | Identity of "one"                  | $1\vec{u}=\vec{u}$                                                                                                              |


Then, we can say that $V$ is a vector space: $(V, +, \cdot)$.

```ad-tip
The first 5 axioms deal with **addition**; 6, 9, and 10 deal with **scalar multiplication**; while 7 and 8 deal with **compatibility**.
```