---
alias: 
tags: COMPSCI_1DM3
created: Monday March 28, 2022; 11:18:59 
---
# Handshaking theorem
If $G=(V,E)$ is an undirected [[graph]] with $m$ edges, then
$$2m=\sum_{v\in V}\operatorname{deg}(v)$$

Proof:

Each edge contributes twice to the degree count of all vertices. Hence, both the left-hand and right-hand sides of this equation equal twice the number of edges.

---

An undirected graph has an even number of vertices of odd degree.

Proof:

Let $V_1$ be the vertices of even degree and $V_2$ be the vertices of odd degree, then

$$2m=\sum_{v\in V}\operatorname{deg}(v)=\sum_{v\in V_1}\operatorname{deg}(v)+\sum_{v\in V_2}\operatorname{deg}(v)$$