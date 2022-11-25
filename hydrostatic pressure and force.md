---
alias: 
tags: MATH_1ZB3
created: Saturday March 12, 2022; 16:47:31 
---
# Hydrostatic pressure and force
Suppose that a thin horizontal plate with an area $P$ square meters is submerged in a fluid of density $\rho$ kilograms per cubic meter at a depth $d$ meters below the surface of the liquid. The fluid directly above the plate has volume $V=Ad$, so its mass is $m=\rho V=\rho Ad$. The force exerted by the fluid on the plate is then
$$F=mg=\rho gAd$$
where $g$ is the acceleration due to gravity. The pressure $P$ on a plate is defined to be the force per square area:
$$P=\frac{F}{A}=\rho gd$$

An important principle of fluid pressure is that *at any point in a liquid the pressure is the same in all directions*. So the pressure in any direction at depth $d$ in a fluid with mass density $\rho$ is given by
$$P=\rho gd = \delta d$$

This equation lets us determine the hydrostatic force against a *vertical* plate. 

So, when solving for the force, we have 
$$F=\rho g\int^b_a xA\, dx$$
where the object is in the water from a depth of $b$ (high) to $a$ (low).

```ad-note
The density of water is $\rho=1000$ kg/m$^3$. 

When using imperial units, we write $P=\rho gd=\delta d$, where $\delta=\rho g$ is the *weight density* (as opposed to $\rho$, which is *mass density*). The weight density of water is $\delta=62.5$ lb/ft$^3$.  
```
