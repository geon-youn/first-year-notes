---
alias: subgraph, proper subgraph, subgraph induced, union (graph)
tags: COMPSCI_1DM3
created: Thursday March 31, 2022; 10:41:08 
---
# New graphs from old
A **subgraph of a graph $G=(V,E)$** is a [[graph]] $(W,F)$, where $W\subset V$ and $F\subset E$. A subgraph $H$ of $G$ is a **proper subgraph** of $G$ is $H\neq G$.

Let $G=(V,E)$ be a [[graph|simple graph]]. The **subgraph induced** by a subset $W$ of the vertex set $V$ is the graph $(W,F)$, where the edge set $F$ contains an edge in $E$ iff both endpoints are in $W$. 

The **union** of two simple graphs $G_1$ and $G_2$ is the simple graph with the [[union]] of the vertex set and union of the edge set. The union of $G_1$ and $G_2$ is denoted by $G_1\cup G_2 = (V_1\cup V_2, E_1\cup E_2)$. 