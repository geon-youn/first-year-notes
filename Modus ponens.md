---
alias:
tags: MATH_1C03
---
# Modus ponens
**Modus ponens** is the type of deductive argument used for [[direct proof]]s. If $P$ is true and we know that $P\Rightarrow Q$, then $Q$ is true. This method prevents us from reaching false conclusions.

## [[truth table|Truth Table]]

| $P$ | $Q$ | $P$ | $P\Rightarrow Q$ | $P\wedge (P\Rightarrow Q)$ | $Q$ | $(P\wedge (P\Rightarrow Q))\Rightarrow Q$ |
| --- | --- | --- | ---------------- | -------------------------- | --- | ----------------------------------------- |
| T   | T   | T   | T                | T                          | T   | T                                          |
| T   | F   | T   | F                | F                          | F   | T                                          |
| F   | T   | F   | T                | F                          | T   | T                                          |
| F   | F   | F   | T                | F                          | F   | T                                          |
