---
alias: product rule, sum rule, subtraction rule, division rule
tags: COMPSCI_1DM3
created: Monday March 7, 2022; 10:45:02 
---
# Counting
## Product Rule
If a procedure can be broken down into a sequence of two tasks and there are $n_1$ ways to do the first task and $n_2$ ways to do the second task, then there are $n_1\cdot n_2$ ways to do the procedure.

### Division Rule
There are $n/d$ ways to do a task if it can be done using a procedure that can be carried out in $n$ ways, and for every way $w$, exactly $d$ of the $n$ ways correspond to way $w$. 

If the finite set $A$ is the union of $n$ pairwise disjoint subsets each with $d$ elements, then $n=|A|/d$

If $f$ is a function from $A$ to $B$, where both are finite sets, and for every $y\in B$ there are exactly $d$ values $x\in A$ such that $f(x)=y$, then $|B|=|A|/d$. 

## Sum Rule
If a task can be done either in one of $n_1$ ways or in one of $n_2$ ways, and none of the $n_1$ ways is the same as the $n_2$ ways (disjoint), then there are $n_1+n_2$ ways to do the task.

### Subtraction Rule
If a task can be done either in one of $n_1$ ways or in one of $n_2$ ways, then there are $n_1+n_2$ minus the number of ways to do the task that are common to the two different ways:
$$\mid A\cup B\mid = \mid A \mid + \mid B \mid - \mid A \cap B \mid$$