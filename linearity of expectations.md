---
alias: 
tags: COMPSCI_1DM3
created: Monday March 21, 2022; 10:47:54 
---
# Linearity of expectations
If $X_i,i=1,2,\dots, n$ with $n$ a positive integer, are [[random variable]]s on $S$, and if $a$ and $b$ are real numbers, then the [[expected value]]s follow linear combinations:

> $$E(X_1+X_2+\dots+X_n)=E(X_1)+E(X_2)+\dots+E(X_n)$$

Proof (for $n=2$):

$$\begin{align*}
E(X_1+X_2)&=\sum_{s\in S}p(s)(X_1(s)+X_2(s))\\
&=\sum_{s\in S}p(s)X_1(s)+\sum_{s\in S}p(s)X_2(s)\\
&=E(X_1)+E(X_2)
\end{align*}$$

> $$E(aX+b)=aE(X)+b$$