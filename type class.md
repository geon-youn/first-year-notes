---
alias:
tags: COMPSCI_1JC3
---
# Type Class
A **type class** is a family of [[type]]s with a common set of [[First Year/function]]s, possibly with some default implementation. An **instance** of a type class is a type that implements the methods of the class. The methods of a type class are a [[little language]] for utilizing the instances of the type class. For example,

```haskell
class C a where
	f1 :: t1
	...
	fn :: tn
	
	fi x1 ... xm = e
	...
```