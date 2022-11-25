---
alias:
tags: COMPSCI_1JC3
---
# Name Servers
Each server is responsible for part of the name space. They communicate with each other using both [[TCP]] and UDP. Name lookups are done by [[recursion|recursive]] search, sometimes starting at a **root server**. Answers to name lookups are cached by name servers to optimize lookup costs. 