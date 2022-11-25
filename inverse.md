---
alias:
tags: MATH_1C03
---
# [[First Year/function|Function]] Inverse
$g:Y \mapsto X$ is **inverse** to $f:X \mapsto Y$ if 
$$\forall{x}\in{X},y\in{Y},\;\;\;\;y=f(x)\Leftrightarrow g(y) = x$$
- $g:Y \mapsto X$ is inverse to $f:X \mapsto Y$ iff $f:X \mapsto Y$ is inverse to $g:Y \mapsto X$.
- $f:X \mapsto Y$ is **invertible** if there exists a function $g:Y \mapsto X$ that is inverse to $f:X \mapsto Y$.
- If $f:X \mapsto Y$ is invertible, then the inverse is unique.
- For $f:X \mapsto Y$ to be invertible, $f$ *must* be [[bijective]].

## [[composition|Composition]] POV
When you compose an inverse onto the function, it returns the [[identity function]]: 	
$$g \circ f : X \mapsto X = \mathbb{I}_X$$
$$f \circ g : Y \mapsto Y = \mathbb{I}_Y$$
