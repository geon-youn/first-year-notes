---
alias: experiment, sample space, event, probability
tags: COMPSCI_1DM3
created: Thursday March 10, 2022; 10:58:49 
---
# Pierre-Simon Laplace's classical theory of probability
## Experiment
A procedure that yields one of a given set of possible outcomes.

## Sample space
The [[set]] of possible outcomes of an experiment.

## Event
A [[subset]] of the sample space.

## Laplace's definition of the probability of an event
If $S$ is a finite sample space of equally likely outcomes, and $E$ is an event ($E\subseteq S$), then the *probability* of $E$ is
$$p(E)=\frac{|E|}{|S|}$$
For every event $E$, we have $0\leq p(E) \leq 1$. 

```ad-note
This inequality follows from 
$$0\leq p(E)=\frac{|E|}{|S|} \leq \frac{|S|}{|S|} \leq 1$$ since $0\leq |E| \leq |S|$. 
```