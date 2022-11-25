---
alias: 
tags: COMPSCI_1DM3
created: Thursday March 31, 2022; 10:56:39 
---
# Adjacency matrix
Suppose that $G=(V,E)$ is a [[graph|simple graph]] where $|V|=n$. Arbitrary list the vertices of $G$ as $v_1,v_2,\dots,v_n$. The **adjacency matrix** $A_G$ of $G$, with respect to the listing vertices, is the $n \times n$ [[zero-one Matrix|zero-one matrix]] with 1 as its $(i,j)$th entry when $v_i$ and $v_j$ are [[adjacent (graph)|adjacent]], and 0 if they aren't. 

Alternative explanation:

$A_G=\left[a_{ij}\right]$ where

$$a_{ij}=\left\{\begin{array}{ll}1 & \text{if $\{v_i,v_j\}$ is an edge of $G$}\\0&\text{otherwise}\end{array}\right.$$

When a graph is sparse (few edges relative to the total number of possible edges), it's much more efficient to store it as an [[adjacency list]].

The adjacency matrix of an undirected simple graph is **symmetric** ($a_{ij}=a_{ji}$). Also, since there's no loops, each diagonal entry is 0. 

For a graph with multiple edges, instead of 1, have the number of identical edges. 