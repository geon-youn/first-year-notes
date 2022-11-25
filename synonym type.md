---
alias:
tags: COMPSCI_1JC3
---
# Synonym Types
A **synonym** [[type]] is a new name for an old type.

```haskell
-- without parameters
type new_name = old_type

--with parameters
type new_name p1 p2 p3 = (p1, p2, p3)
```

A type with parameters is called a **polymorphic type** and represents a family of types. The parameters `p1`, `p2`, and `p3` are called **type variables**.