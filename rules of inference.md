---
alias: rules of inference, modus ponens, modus tollens, hypothetical syllogism, disjunctive syllogism, addition, simplification, conjunction, resolution, universal instantiation, universal generalization, existential instantiation, existential generalization, universal modus ponens
tags: COMPSCI_1DM3
created: January 31, 2022 13:31
---
# Rules of Inference
## [[Modus ponens| Modus Ponens]]
"If $p$ then $q$ and $p$ was true, then $q$ is true."
$$\begin{array}{rl}
& p \rightarrow q\\
& p\\
\hline
\therefore & q
\end{array}$$

## Modus Tollens
"If $p$ then $q$ and $q$ isn't true, then $p$ is also not true."
$$\begin{array}{rl}
& p \rightarrow q\\
& \neg q\\
\hline
\therefore & \neg p
\end{array}\Leftrightarrow 
\begin{array}{rl}
& \neg p \lor q\\
& \neg q\\
\hline
\therefore & \neg p
\end{array}$$

## Hypothetical Syllogism 
"One implication leads to another."
$$\begin{array}{rl}
& p\rightarrow q\\
& q\rightarrow r\\
\hline
\therefore & p\rightarrow r
\end{array}$$

## Disjunctive Syllogism
"$p$ or $q$ must have occurred, but it wasn't $p$, so it must be $q$."
$$\begin{array}{rl}
& p\lor q\\
& \neg p\\
\hline
\therefore & q
\end{array}$$

## Addition
"If $p$ is true, then it can be added (maintaining `true`) to another statement through disjunction."
"If $p$, then $p\lor q$."
$$\begin{array}{rl}
& p\\
\hline
\therefore & p\lor q
\end{array}$$ 

## Simplification
"If $p\land q$, then $p$ and $q$ are true."
$$\begin{array}{rl}
& p\land q\\
\hline
\therefore & p
\end{array}\Leftrightarrow
\begin{array}{rl}
& p\land q\\
\hline
\therefore & q
\end{array}$$

## Conjunction
"If $p$ and $q$, then $p\land q$."
$$\begin{array}{rl}
& p\\& q\\\hline\therefore & p\land q
\end{array}$$

## Resolution
"If $p$, then $r$ and $q$ can be anything, so $r\lor q$. If $\neg p$, then $q$ and $r$ can be anything so $q\lor r$. Either way, $q\lor r$."
$$\begin{array}{rl}
& \neg p \lor r\\& p\lor q\\\hline\therefore & q\lor r
\end{array}$$
# Rules of Inference for Quantified Statements
## Universal Instantiation
Allows us to talk about one element $c$ in the domain of "$\forall x$."
$$\begin{array}{rl}& \forall x \, P(x)\\\hline\therefore & P(c)\text{ for any }c\end{array}$$

## Universal Generalization
The opposite of universal instantiation. **But all $c\in x$ must be true**.
$$\begin{array}{rl}& P(c) \text{ for an arbitrary }c\\\hline\therefore & \forall x\, P(x)\end{array}$$

## Existential Instantiation
If $P(x)$ for some element $x$, then $P(c)$ for some element $c$.
$$\begin{array}{rl}& \exists x \, P(x)\\\hline\therefore & P(c)\text{ for some }c\end{array}$$

## Existential Generalization
If $P(c)$ for some element $c$, then there exists a domain with $x$ such that $P(x)$. 
$$\begin{array}{rl}& P(c)\text{ for some element }c\\\hline\therefore & \exists x\, P(x)\end{array}$$

## Universal Modus Ponens
$$\begin{array}{rl}
& \forall x \, (P(x)\rightarrow Q(x))\\
& P(a) \text{ where $a$ is a particular element in the domain}\\
\hline
\therefore & Q(a)
\end{array}$$