---
alias: incident, connect, neighbourhood, neighbour, adjacent
tags: COMPSCI_1DM3
created: Monday March 28, 2022; 11:11:08 
---
# Adjacent
Two vertices $u, v$ in an undirected [[graph]] $G$ are called **adjacent** (or neighbours) in $G$ if there's an edge $e$ between $u$ and $v$. $e$ is called **incident** with the vertices $u$ and $v$ and $e$ is said to **connect** $u$ and $v$.

The set of all neighbours of a vertex $v$ of $G=(V,E)$, denoted by $N(v)$, is called the **neighbourhood** of $v$. If $A$ is a subset of $V$, we denote $N(A)$ the set of all vertices in $G$ that are adjacent to at least one vertex in $A$. So, $N(A)=\bigcup_{v\in A}N(v)$.