---
alias: 
tags: COMPSCI_1XC3
created: Thursday March 24, 2022; 17:41:35 
---
# Sed
`sed` is used to replace occurrences of text.

```ad-example
`sed 's/hello/world/' input.txt`
Reads `input.txt` and replaces the *first* occurrence of `hello` with `world` on every line.
```

Combining `sed` with [[pipe]]s:

`echo "test test hello" | sed "s/test/abc/"`

returns `abc test hello`

`echo "test test hello" | sed "s/test/abc/2"`

returns `test abc hello`

`echo "test test hello" | sed "s/test/abc/g"`

returns `abc abc hello`