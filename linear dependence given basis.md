---
alias: linear dependence, linearly independence, linearly dependent, linearly independent
tags: MATH_1B03
---
# Linear Dependence Given Basis
Let $B=\left\{\vec{b_1},\dots,\vec{b_n}\right\}$ be a [[basis]] for $V$ and $C= \left\{\vec{u_1},\dots,\vec{u_p}\right\}\subset{V}$.
If $C$ is larger than $B$ ($p>n$), then $C$ must be [[linear dependence|linearly dependent]].

## Contrapositive
The number of vectors in an independent set is less than the size of $B$ ($p\leq{n}$).

## Proof
Let $\left[\vec{u_j}\right]_B=\begin{bmatrix}
c_{j1}\\\vdots\\c_{jn}
\end{bmatrix}\in\mathbb{R}^n$ be the [[B-coordinate vector]], such that $\vec{u_j}=c_{j1}\vec{b_1}+\dots+c_{jn}\vec{b_n}$. 
Then, $\left\{\left[\vec{u_1}\right]_B,\dots,\left[\vec{u_p}\right]_B\right\}$ is linearly dependent since $p > n$. 
Since the system has $(p-n)$ free variables, $\exists\vec{x}\neq{\vec{0}}\in{\mathbb{R}^p}$ such that $x_1\left[\vec{u_1}\right]_B+\dots+x_p\left[\vec{u_p}\right]_B=\left[x_1\vec{u_1}+\dots+x_p\vec{u_p}\right]_B=\vec{0}\in\mathbb{R}^n$.
Then, $x_1\vec{u_1}+\dots+x_p\vec{u_p}=0\vec{b_1}+\dots+0\vec{b_n}=\vec{0}\in{V}$.
Then, $\left\{\vec{u_1},\dots,\vec{u_p}\right\}$ is linearly dependent since $\vec{x}\neq\vec{0}$.
