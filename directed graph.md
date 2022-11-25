---
alias: digraph, undirected graph, simple directed graph, directed multigraph, initial vertex, terminal vertex, in-degree, out-degree
tags: COMPSCI_1DM3
created: Monday March 28, 2022; 10:29:19 
---
# Directed graph (digraph)
Each edge in this [[graph]] is associated with an **ordered pair of vertices**. The directed edge $(u, v)$ is said to start at $u$ and end at $v$. 

$u$ is the *initial vertex* and is [[adjacent (graph)|adjacent]] to $v$ and $v$ is the *terminal* (or *end*) vertex and is adjacent from $u$. The initial and terminal vertices of a loop are the same.

```ad-warning
$(v, u)$ is a different directed edge from $(u, v)$.
```

Graphs where the end points of an edge aren't ordered are said to be *undirected graphs*.

A *simple directed graph* has no loops and no multiple edges.

A *directed multigraph* may have multiple directed edges. When there're $m$ directed edges from the vertex $u$ to vertex $v$, we say that $(u, v)$ is an edge of *multiplicity $m$*.

The **in-degree of a vertex $v$** denoted $\operatorname{deg}^-(v)$, is the number of edges which terminate at $v$. 

The **out-degree of a $v$**, denoted $\operatorname{deg}^+(v)$, is the number of edges with $v$ as their initial vertex. 

A loop at a vertex contributes 1 to both the in-degree and the out-degree of the vertex.

> The number of edges in a directed graph is the sum of the in-degrees, which is equal to the sum of the out-degrees. 
$$|E|=m=\sum_{v\in V}\operatorname{deg}^-(v)=\sum_{v\in V}\operatorname{deg}^+(v)$$