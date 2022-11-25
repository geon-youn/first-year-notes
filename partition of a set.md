---
alias: partition
tags: COMPSCI_1DM3
created: Thursday March 24, 2022; 11:01:06 
---
# Partition of a set
A **partition** of a [[set]] $S$ is a collection of [[probability|disjoint]] nonempty [[subset]]s of $S$ that have $S$ as their union. In other words, the collection of subsets $A_i$, where $i\in I$ (where $I$ is an index set), forms a partition of $S$ iff

1. $$\forall i\in I,\,\, A_i\neq\emptyset$$
2. $$A_i\cap A_j=\emptyset,\,\,i\neq j$$
3. $$\bigcup_{i\in I}A_i=S$$