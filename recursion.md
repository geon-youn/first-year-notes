---
alias:
tags: COMPSCI_1JC3
---
# Recursion
**Recursion** is a method of defining something (usually a function) in terms of itself. Its correctness is proved by [[mathematical induction]]. 

Recursion employs a [[divide and conquer]] strategy. 

A recursive [[First Year/function]] is **nonsensical** if the size of the input for the next call is larger than the size of the current input. That is, the inductive set must be in well-ordfer and be [[Noetherian]]. 

## Structural Recursion
Based on an inductive set (e.g., an [[algebraic data type]] in Haskell).

## Ordinal Recursion
Based on a [[well-order]]ed set (e.g., the [[natural numbers]]).

## Well-founded Recursion
Based on a well-founded relation. Structural and ordinal recursion are special cases of well-founded recursion and [[induction]].
