---
alias: 
tags: COMPSCI_1DM3
created: Thursday March 31, 2022; 11:14:53 
---
# Incidence matrix
Let $G=(V,E)$ be an [[directed graph|undirected graph]] with vertices where $V-1,v_2,\dots,v_n$ and edges $e_1,e_2,\dots,e_m$. The **incidence matrix** with respect to the ordering of $V$ and $E$ is the $n\times m$ matrix $M=\left[m_{ij}\right]$ where

$$m_{ij}=\cases{1 & \text{when edge $e_j$ is incident with $v_i$}\\0 & \text{otherwise}}$$

That is, each column are the edges and each row is a vector and $m_{ij}$ is `true` when  $e_j$ is [[adjacent (graph)|incident]] with $v_i$. 

If there's only 1 true value in a column, then it's a loop. Otherwise, there will be 2 true values and those are the connected vectors for that edge. 