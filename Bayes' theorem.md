---
alias: 
tags: COMPSCI_1DM3
created: Thursday March 17, 2022; 10:38:24 
---
# Bayes' theorem
Suppose that $E$ and $F$ are [[Pierre-Simon Laplace's classical theory of probability|event]]s from a sample space $S$ such that $p(E)\neq0$ and $p(F)\neq 0$. Then:

> $$p(F\mid E)=\frac{p(F\cap E)}{p(E)}=\frac{p(E\mid F)p(F)}{p(E\mid F)p(F)+p(E\mid \overline{F})p(\overline{F})}$$

Numerator is from manipulating [[conditional probability]].

Denominator comes from the assumption that $(E\cap F)\cap(E\cap \overline{F})=\emptyset$ ($F$ and $\overline{F}$ are [[probability|mutually exclusive]]), then

$$\begin{align*}
E&=(E\cap S) &\text{where $S$ is the sample space}\\
E&=(E\cap (F\cup \overline{F}))\\
E&=(E\cap F)\cup (E\cap \overline{F})\\
p(E)&=p(E\cap F)+p(E\cap \overline{F})\\
p(E)&=p(E\mid F)p(F)+p(E\mid\overline{F})p(\overline{F})
\end{align*}$$  

> Similarly, the general Bayes' theorem is if $\bigcap^k_{j=1}E\cap F_j=\emptyset$ (the events $F_j$ are [[probability|mutually exclusive]]), then
$$p(F_i\mid E)=\frac{p(F_i\cap E)}{p(E)}=\frac{p(F_i\cap E)}{\sum^k_{j=1}p(E\cap F_j)}=\frac{p(E\mid F_i)p(F_i)}{\sum^k_{j=1}p(E\mid F_j)p(F_j)}$$
where $i\in\{1,\dots,k\}$.
