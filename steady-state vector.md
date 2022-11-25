---
alias: equilibrium vector
tags: MATH_1B03
---
# Steady-State Vector
If $P$ is a [[stochastic|stochastic matrix]], then a **steady-state vector** for $P$ is a [[probability vector]] $\boldsymbol{q}$ such that
$$P\boldsymbol{q}=\boldsymbol{q}$$

## Why it's steady-state
If $P$ is an $n \times n$ regular stochastic matrix, then $P$ has a unique steady-state vector $\boldsymbol{q}$. Further, if $\boldsymbol{x}_0$ is any initial state and $\boldsymbol{x}_{k+1}=P\boldsymbol{x_k}$ for $k=0,1,2,\dots$, then the [[dynamical system|Markov chain]] $\left\{\boldsymbol{x}_k\right\}$ converges to $\boldsymbol{q}$ as $k\rightarrow\infty$. 

The initial state has *no effect* on the long-term behaviour of the Markov chain. 
