---
alias: 
tags: COMPSCI_1XC3
created: Thursday March 24, 2022; 17:38:14 
---
# Pipe
Have the output of one command become the input of another command:

`command1 | command2`

The output of `command1` will become the input of `command2`.

```ad-example
`ls -l | more`
Takes the outputs of `ls -l` and shows it to the screen as pages instead of pure text.

`sort file.txt | uniq`
Sorts the lines of `file.txt` and only output the unique values.
```