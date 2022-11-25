---
alias: isomorphism, isomorphic, nonisomorphic, graph invariant
tags: COMPSCI_1DM3
created: Monday April 4, 2022; 10:27:33 
---
# Isomorphism of graphs
The [[graph|simple graph]]s $G_1=(V_1, E_1)$ and $G_2=(V_2,E_2)$ are [[isomorphism|isomorphic]] if there's a [[bijective]] [[First Year/function]] $f$ from $V_1$ to $V_2$ with the property that $a$ and $b$ are [[adjacent (graph)|adjacent]] in $G_1$ iff $f(a)$ and $f(b)$ are adjacent in $G_2$, for all $a,b\in V_1$. 

Such a function $f$ is called an **isomorphism**. 

Two simple graphs that aren't isomorphic are called *nonisomorphic*.

For each edge $(a, b)$ in $G_1$ if $f(a)=a$ and $f(b)=b$ the isomorphism means $G_1=G_2$. 

Determining whether two simple graphs with $n$ vertices are isomorphic using brute force requires at most $n!$ guesses of possible correspondences between the vertex sets of the two graphs.

Sometimes to show that two graphs are nonisomorphic, we can find a property, preserved by isomorphism that one of the two graphs lacks. Such a property is called **graph invariant**.
- Find vertices in each graph with the same degree and create [[new graphs from old|subgraph]]s. If the subgraphs of each graph are different, then the graphs are nonisomorphic. 