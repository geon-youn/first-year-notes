---
alias: type 1, convergent, divergent, improper integral
tags: MATH_1ZB3
created: Saturday March 12, 2022; 10:25:05 
---
# Improper integral of type 1
If $\int^t_af(x)dx$ exists for every number $t\geq a$, then
$$\int^\infty_af(x)dx=\lim_{t\rightarrow\infty}\int^t_af(x)dx$$
provided this limit exists (as a finite number).

If $\int^b_tf(x)dx$ exists for every number $t\leq b$, then
$$\int^b_{-\infty}f(x)dx=\lim_{t\rightarrow-\infty}\int^b_tf(x)dx$$
provided this limit exists (as a finite number).

The improper integrals $\int^\infty_af(x)dx$ and $\int^b_{-\infty}f(x)dx$ are called **convergent** if the corresponding limit exists and **divergent** if the limit does not exist.

If both $\int^\infty_af(x)dx$ and $\int^b_{-\infty}f(x)dx$ are convergent, then we define

$$\int^\infty_{-\infty}f(x)dx = \int^a_{-\infty}f(x)dx + \int^\infty_af(x)dx$$
and any real number $a$ can be used.