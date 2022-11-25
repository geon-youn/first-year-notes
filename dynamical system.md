---
alias: Markov chain
tags: MATH_1B03
---
# Dynamical System
A **system** where you start with a **vector** and a **procedure** (e.g. a [[linear transformation]]) for finding the next vector for an indefinite number of times. 

| Origin Name  | ([[modulus\|Absolute Value]]) of Eigenvalues | Behaviour                                                                  |
| ------------ | -------------------------------------------- | -------------------------------------------------------------------------- |
| Attractor    | All less than 1                              | Trajectory of the dynamical system tend toward $\boldsymbol{0}$            |
| Repeller     | All greater than 1                           | Trajectory of the dynamical system tend away from $\boldsymbol{0}$         |
| Saddle Point | Not all less than or greater than 1          | Some trajectories tend toward while others tend away from $\boldsymbol{0}$ |

# Markov Chain
A Markov chain is a dynamical system where the vectors $\boldsymbol{x}_0,\boldsymbol{x}_1,\boldsymbol{x}_2,\dots$ are probability vectors and the procedure $P$ is a stochastic matrix such that
$$\begin{array}{cccc}
\boldsymbol{x}_1=P\boldsymbol{x}_0,&
\boldsymbol{x}_2=P\boldsymbol{x}_1,&
\boldsymbol{x}_3=P\boldsymbol{x}_2,&
\dots\end{array}$$
The $\boldsymbol{x}_k$ probability vector is called the **state vector**.

## Long-term behaviour of urban-rural population
Suppose we have a [[probability vector]] $\vec{x_0}=\begin{bmatrix}.6\\.4\end{bmatrix}$ and a [[stochastic|stochastic matrix]] $A=\begin{bmatrix}.95 & .03\\.05 & .97\end{bmatrix}$. We observe
$\begin{align*}
\vec{x_1}&=A\vec{x_0}=\begin{bmatrix}.582\\.418\end{bmatrix}\\
\vec{x_2}&=A\vec{x_1}=\begin{bmatrix}.56544\\.43456\end{bmatrix}
\end{align*}$
So, $\vec{x_{k+1}}\equiv A\vec{x_k}$, for all $k\geq 0$. $\vec{x_{k+1}}$ is a **dynamical system**. 

To determine the long-term behaviour,

**Step 1**: [[solving eigenvalues and eigenvectors|Find]] the [[eigenvalue|eigenvalues]] and [[eigenvector|eigenvectors]].
$$\det \begin{bmatrix}.95-\lambda & .03\\.05 & .97-\lambda\end{bmatrix}=0$$
Then, $\lambda={1,.92}$ and the eigenvectors are $\left\{\begin{bmatrix}3\\5\end{bmatrix},\begin{bmatrix}1\\-1\end{bmatrix}\right\}\equiv\left\{\vec{v_1},\vec{v_2}\right\}$.

**Step 2**: Express $\vec{x_0}$ as a [[linear combination]] of the eigenvectors. 
$\begin{align*}
\vec{x_0}&=\begin{bmatrix}.6\\.4\end{bmatrix}\\
		 &=c_1\vec{v_1}+c_2\vec{v_2}\\
		 &=\begin{bmatrix}\vec{v_1} & \vec{v_2}\end{bmatrix}\begin{bmatrix}c_1\\c_2\end{bmatrix}\\
		 &\Rightarrow\begin{bmatrix}c_1\\c_2\end{bmatrix}=\begin{bmatrix}\vec{v_1} & \vec{v_2}\end{bmatrix}^{-1}\begin{bmatrix}.6\\.4\end{bmatrix}=\begin{bmatrix}.125\\.225\end{bmatrix}
\end{align*}$

**Step 3**: Compute $\vec{x_k}$ as a linear combination of constants (step 2) and eigenvalues and eigenvectors (step 1):
$\begin{align*}
\vec{x_1}&=A\vec{x_0}=c_1(1)^1\vec{v_1}+c_2(.92)^1\vec{v_2}\\
\vec{x_2}&=A\vec{x_1}=c_1(1)^2\vec{v_1}+c_2(.92)^2\vec{v_2}\\
\vec{x_3}&=A\vec{x_2}=c_1(1)^3\vec{v_1}+c_2(.92)^3\vec{v_2}\\
\vec{x_k}&=c_1(1)^k\vec{v_1}+c_2(.92)^k\vec{v_2}
\end{align*}$

**Step 4**: Find the long-term behaviour by evaluating $k\rightarrow\infty$. 
$c_2(.92)^k\vec{v_2}=0$
$c_1(1)^k\vec{v_1}=(.125)\begin{bmatrix}3\\5\end{bmatrix}=\begin{bmatrix}.375\\.625\end{bmatrix}$
So, $\vec{x_\infty}=\begin{bmatrix}.375\\.625\end{bmatrix}$. 
