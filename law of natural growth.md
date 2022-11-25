---
alias: law of natural decay, half-life
tags: MATH_1ZB3
created: Saturday March 12, 2022; 16:31:42 
---
# Law of natural growth
If $y(t)$ is the value of a quantity $y$ at time $t$ and if the rate of change of $y$ with respect to $t$ is proportional to its size $y(t)$ at any time, then we get the [[differential equation]]
$$\frac{dy}{dt}=ky$$
where $k$ is a constant. This equation is sometimes called the **law of natural growth** if $k>0$ and **law of natural decay** if $k<0$. 

Then, the solution is  $y(t)=Ce^{kt}$:
$$\frac{dy}{dt}=C(ke^{kt})=k(Ce^{kt})=ky$$

and, when $t=0$, $C=y(0)$:
$$y(0)=Ce^{k\cdot 0}=C$$

so, $C$ is the **initial value** of the function. Therefore, the solution is $y(t)=y(0)e^{kt}$.

What is $k$? In the context of population growth, where $P(t)$ is the size of the population at any time $t$, 
$$\frac{dP}{dt}=kP\Rightarrow \frac{dP/dt}{P}=k$$

The quantity
$$\frac{dP/dt}{P}$$
is the growth rate divided by the population size, which is called the **relative growth rate**. And so, instead of saying the "growth rate is proportional to population size", we can say the "growth rate is constant" and is $k$. 

## Decay
With decay, $k$ is negative and the rate of decay is expressed in terms of **half-life**, which is the time required for half of the quantity to decay. 