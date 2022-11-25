---
alias: 
tags: COMPSCI_1DM3
created: Thursday March 10, 2022; 10:42:58 
---
# Pascal's identity
If $n$ and $k$ are integers with $n\leq k\leq 0$, then
$$\begin{pmatrix}n+1\\k\end{pmatrix}=\begin{pmatrix}n\\k-1\end{pmatrix}+\begin{pmatrix}n\\k\end{pmatrix}$$

## Proof (combinatorial)
Let $T$ be a set where $|T|=n+1,a\in T$, and $S=T-{a}$. There are $\begin{pmatrix}n+1\\k\end{pmatrix}$ subsets of $T$ containing $k$ elements. Each of these subsets either
- contain $a$ with $k-1$ other elements, or
- contain $k$ elements of $S$ and not $a$.

There are
- $\begin{pmatrix}n\\k-1\end{pmatrix}$ subsets of $k$ elements that contain $a$, since there are $\begin{pmatrix}n\\k-1\end{pmatrix}$ subsets of $k-1$ elements of $S$,
- $\begin{pmatrix}n\\k\end{pmatrix}$ subsets of $k$ elements of $T$ that do not contain $a$, because there are $\begin{pmatrix}n\\k\end{pmatrix}$ subsets of $k$ elements of $S$.

Hence,
$$\begin{pmatrix}n+1\\k\end{pmatrix}=\begin{pmatrix}n\\k-1\end{pmatrix}+\begin{pmatrix}n\\k\end{pmatrix}$$