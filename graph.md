---
alias: vertices, vertex, node, edge, endpoint, connect, infinite graph, finite graph, simple graph, multigraph, multiplicity, loop, pseudograph
tags: COMPSCI_1DM3
created: Thursday March 24, 2022; 11:09:32 
---
# Graph
A **graph** $G=(V,E)$ consists of a nonempty [[set]] $V$ of **vertices** (or **nodes**) and a set $E$ of **edges**. Each edge has either one or two vertices associated with it, called its **endpoints**. An edge is said to *connect* its endpoints.

A graph with an infinite vertex set is called an **infinite graph** and a finite vertex set is called a **finite graph**.

In a **simple graph**, each edge connects two different vertices and no two edges connect the same pair of vertices.

**Multigraphs** may have multiple edges connecting the same two vertices. When $m$ different edges connect the vertices $u$ and $v$, we say that $\left\{u, v\right\}$ is an edge of *multiplicity m*. 

An edge that connects a vertex to itself is called a **loop**.

A **pseudograph** may include loops, as well as multiple edges connecting the same pair of vertices.

```ad-warning
There's no standard terminology for graph theory. Other places may use different terms to describe graphs.
```