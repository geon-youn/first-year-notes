---
alias: congruence class
tags: COMPSCI_1DM3
created: Thursday March 24, 2022; 10:44:16 
---
# Equivalence class
Let $R$ be an [[equivalence relation]] on a [[set]] $A$. The set of all elements that are related to an element $a$ of $A$ is called the **equivalence class of $a$** denoted by $[a]_R$. 

When only one relation is under consideration, we can write $[a]$.

> $$[a]_R=\{s\mid (a,s)\in R\land a\in A\land s\in A\}$$

If $b\in [a]_R$ then $b$ is called a **representative** of this equivalence class (that is, $[b]_R\equiv [a]_R$). Any element of a class can be used as a representative of the class.

The equivalence classes of the relation [[congruence|congruence]] modulo $m$ are called the **congruence classes modulo $m$**. The congruence class of an integer $a\operatorname{mod} m$ is denoted by $[a]_m,$ so 

> $$[a]_m=\left\{\dots,a-2m, a-m,a,a+m,a+2m,\dots\right\}$$

These statements for elements $a$ and $b$ for $A$ are equivalent:

1. $$aRb$$
2. $$[a]=[b]$$
3. $$[a]\cap[b]\neq\emptyset$$