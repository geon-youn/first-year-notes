---
alias: 
tags: COMPSCI_1DM3
created: Wednesday March 16, 2022; 10:30:11 
---
# Probability of complements and unions of events
Let $E$ be an [[Pierre-Simon Laplace's classical theory of probability|event]]  in the sample space $S$. The probability of the event $\overline{E}=S-E$, the [[complement|complementary]] event of $E$ is given by

> $$p(\overline{E})=1-p(E).$$

Proof: using the fact that $|\overline{E}|=|S|-|E|$,
$$p(\overline{E})=\frac{|S|-|E|}{|S|}=1-\frac{|E|}{|S|}=1-p(E).$$

```ad-tip
We always use the cardinality of sets to prove probabilities.
```

Let $E_1$ and $E_2$ be events in the sample space $S$. Then the probability of their [[union]] is

> $$p(E_1\cup E_2)=p(E_1)+p(E_2)-p(E_1\cap E_2)$$

Proof:
$$\begin{align*}
p(E_1\cup E_2)
&=\frac{|E_1\cup E_2|}{|S|}\\
&=\frac{|E_1|+|E_2|-|E_1\cap E_2|}{|S|}\\
&=\frac{|E_1|}{|S|}+\frac{|E_2|}{|S|}-\frac{|E_1\cap E_2|}{|S|}\\
&=p(E_1)+p(E_2)-p(E_1\cap E_2)
\end{align*}$$