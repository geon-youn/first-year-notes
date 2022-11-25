---
alias:
tags: COMPSCI_1JC3
---
# Recursive Type
A **recursive type** is an [[algebraic data type]] whose defined type is included in the constructor's types. For example,
```haskell
data Nat
	= Zero
	| Suc Nat

data Tree a
	= Empty
	| Leaf a
	| Node a (Tree a) (Tree a)

data Maybe a
	= Nothing
	| Just a

```

The set of values in a recursive type is always **countably infinite**. 