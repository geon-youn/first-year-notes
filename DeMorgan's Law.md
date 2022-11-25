---
alias:
tags: MATH_1C03
---
# DeMorgan's Law
By DeMorgan's Law, 
$$\neg (P \vee Q)=\neg P \wedge \neg Q$$
and
$$\neg (P \wedge Q) = \neg P \vee \neg Q$$
that is, we can expand [[negation]] by applying negation to all [[statement]]s inside and turning all [[conjunction]]s to [[disjunction]]s and all disjunctions to conjunctions. 

## [[set|Sets]]
Let $A$ and $B$ be [[subset]]s of a [[universe]] U. Then
$$\overline{A\cap B}=\overline{A}\cup\overline{B}$$
and
$$\overline{A\cup B}=\overline{A}\cap\overline{B}$$
such that we can distribute the [[complement]] and turn all [[union]]s to [[intersection]]s and all intersections to unions. 

## [[finite union|Finite union]] and [[finite intersection]]
For all positive integers $n\geq 2$, if $A_1,\dots,A_n$ are subsets of a universe $U$, then
$$\overline{\left(\bigcup^n_{i=1}A_i\right)}=\bigcap^n_{i=1}\overline{A_i}$$
and
$$\overline{\left(\bigcap^n_{i=1}A_i\right)}=\bigcup^n_{i=1}\overline{A_i}$$
such that we can distribute the complement and turn all finite unions into finite intersections of the complement of the subsets and turn all finite intersections into finite unions of the complement of the subsets. 

The same principle applies to [[arbitrary union]]s and [[arbitrary intersection]]s. 