---
alias:
tags: MATH_1B03
---
# Coordinate Mapping
If $B=\{\vec{b_1},\dots,\vec{b_n}\}$ (ordered set) is a [[basis]] for a [[vector space]] $V$, then if the **coordinate map** which takes $\vec{x}\in{V}\rightarrow [\vec{x}]_B\in\mathbb{R}^n$ is [[linear transformation|linear]], [[one-to-one]], and [[onto]], then the transformation matrix is $\mathbb{R}^n \rightarrow \mathbb{R}^n$ i.e. **[[isomorphism|isomorphic]]** such that $V$ "is" $\mathbb{R}^n$. 

## Proof
1. **Linear**:
Through [[change of coordinates]], if $\vec{x}=P_B[\vec{x}]_B$ and $\vec{y}=P_B[\vec{y}]_B$, then $\vec{x}+\vec{y}=\vec{z}$, where $\vec{z}=P_B[\vec{z}]_B$. Then,
$$\begin{align*}
\vec{z}&=P_B[\vec{z}]_B\\
\Leftrightarrow (\vec{x}+\vec{y})&=P_B[(\vec{x}+\vec{y})]_B\\
&=P_B([\vec{x}]_B+[\vec{y}]_B)
\end{align*}$$
2. **One-to-one**:
Only $\vec{0}\in{V}$ maps to $\vec{0}\in\mathbb{R}^n$ since $B$ is a [[linearly independent set]].
3. **Onto**:
$B$ [[span|spans]] all of $\mathbb{R}^n$. 

Therefore, the abstract vector space $V$ "is" $\mathbb{R}^n$. 