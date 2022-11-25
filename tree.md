---
alias: parent, child, sibling, ancestor, descendant, leaf, internal vertex, internal vertices, subtree
tags: COMPSCI_1DM3
created: Monday April 4, 2022; 11:02:21 
---
# Tree
A *tree* is a connected undirected [[graph]] with no simple circuits (only one path from one vertex to another).

The *parent* of a vertex $v$ is the unique vertex $u$ such that there's a directed edge from $u$ to $v$. $v$ is called the *child* of $u$. Vertices with the same parent are called *siblings*.

The *ancestors* of a vertex are the vertices in the path from the root to this vertex, excluding the vertex itself and including the root. The *descendants* of a vertex $v$ are those vertices that have $v$ as an ancestor. 

A vertex of a rooted tree with no children is called a *leaf*. Vertices that have children are called *internal vertices*.

If $a$ is a vertex in a tree, the *subtree* with $a$ as its root is the [[new graphs from old|subgraph]] of the tree consisting of $a$ and its descendants and all edges [[adjacent (graph)|incident]] to these descendants.