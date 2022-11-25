---
alias: probability distribution
tags: COMPSCI_1DM3
created: Wednesday March 16, 2022; 10:47:07 
---
# Assigning probabilities
[[Pierre-Simon Laplace's classical theory of probability]] assumes that all outcomes are equally likely. Now we introduce a more general definition of probabilities that avoids this restriction.

Let $S$ be a sample space of an experiment with a finite number of outcomes. We assign a probability $p(s)$ to each outsome $s$, so that

> $$0\leq p(s)\leq 1\,\,\,\text{ for each }\,\,\,s\in S$$
> $$\sum_{s\in S}p(s)=1$$

The function $p$ from the set of all outcomes of the sample space $S$ is called a **probability distribution**