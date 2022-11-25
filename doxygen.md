---
alias: 
tags: COMPSCI_1XC3
created: Thursday March 24, 2022; 17:55:30 
---
# Doxygen
A popular [[documentation]] generator. Works with C, C++, and many other languages. Works by checking `.c` and `.h` files. 

Produces LaTeX and HTML outputs. Can also produce `man` pages. 

`doxygen -g` creates the Doxyfile configuration file. 

```ad-warning
`PROJECT_NAME` should be set.
```

By default, doxygen reads any `.c` and `.h` files in the current directory. 

`doxygen` and `doxygen Doxyfile` creates the documentation files and puts them into `html` and `latex` folders.

We can write doxygen comments like this:

```C
/**
    Requires two stars at the top.
*/
```