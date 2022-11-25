---
alias: necessity, sufficiency
tags: COMPSCI_1DM3
created: January 17, 2022 18:01
---
# Necessity and Sufficiency
**Necessity** and **sufficiency** are terms used to describe an [[First Year/implication]] relationship between two statements. 

Given $P\Rightarrow Q$, $Q$ is *necessary* for $P$, because the truth of $Q$ is guaranteed by the truth of $P$.  Another way is that $P$ cannot be true unless $Q$ is true (or if $Q$ is false, then $P$ is false). By [[contrapositive]], whenever $P$ is true, so is $Q$. 
 
Similarly, $P$ is *sufficient* for $Q$, because $P$ being true always implies that $Q$ is true, but $P$ not being true does not always imply that $Q$ is not true.

$$\begin{array}{|c|c|c|}
\hline
P & Q & P \Rightarrow Q\\
\hline
T & T & T\\
T & F & F\\
F & T & T\\
F & F & T\\
\hline
\end{array}$$