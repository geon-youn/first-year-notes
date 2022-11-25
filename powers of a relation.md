---
alias: 
tags: COMPSCI_1DM3
created: Wednesday March 23, 2022; 11:12:42 
---
# Powers of a relation
Let $R$ be a [[binary relation]] on a set $A$. Then the powers $R^n$ of the relation $R$ can be defined [[mathematical induction|inductively]] by:

Base case: $R^1=R$

Inductive step: $R^{n+1}=R^n\circ R$ by [[composition relation|composition]]

The powers of a [[transitive relation]] are subsets of the relation.

The relation $R$ on a set $A$ is transitive iff $R^n\subseteq R$ for $n=1,2,3,\dots$

You end up performing [[transitive relation]] $n$ times when $n$ is the power.