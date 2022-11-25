---
alias: zero-one matrix, join, meet, boolean product
tags: COMPSCI_1DM3 
created: February 14, 2022 18:33
---
# Zero-One Matrix
A matrix where all of its entries are either $0$ or $1$.

## Operations
Let $A=[a_{ij}]$ and $B=[b_{ij}]$ be $m \times n$ matrices.

The **join** ($A\lor B$) is the zero-one matrix with the $(i,j)$th entry as $a_{ij}\lor b_{ij}$.

The **meet** ($A\land B$) is the zero-one matrix with the $(i,j)$th entry as $a_{ij}\land b_{ij}$.

## Boolean Product
[[matrix product|Matrix product]], where multiplication is treated as $\land$ and addition is treated as $\lor$. The boolean product is [[key logical equivalences|associative]]. Denoted by $A\odot B$.

### Boolean Power
Let $A$ be a square zero-one matrix and $r$ be a positive integer. The $r$th boolean power of $A$ is the boolean product of $r$ factors of $A$, denoted by $A^{[r]}=A\odot A\odot \dots \odot A$. We define $A^{[r]}$ to be $I_n$. 