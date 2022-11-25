---
alias: monoid
tags: COMPSCI_1JC3
---
# Axiomatic Theories
An **axiomatic theory** is a pair $T=(L,\Gamma)$ where:
1. $L$ is a **language** in some underlying [[logic]].
2. $\Gamma$ is a set of formulas of $L$ called the [[axiom]]s of $T$. 

A **model** of $T$ is an intepretation of $L$ in which all the axioms in $\Gamma$ are true.

```ad-example
$T_M=(L_M,\Gamma_M)$ is a theory of **monoids** where:
1. $L_M$ includes the symbols $e$ and $\operatorname{mul}$.
2. $\Gamma_M$ contains the following formulas:
	- $\forall x . \forall y . \forall z . (x \operatorname{mul} y) \operatorname{mul} z = x \operatorname{mul} (y \operatorname{mul} z)$.
	- $\forall x . (x \operatorname{mul} e) = x$.
	- $\forall x . (e \operatorname{mul} x) = x$.
```

A theory is a [[little language]] with a set of assumptions that can be viewed as a specification of its models. A [[type class]] is an axiomatic theory with implicit axioms. 