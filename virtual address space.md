---
alias:
tags: COMPSCI_1JC3
---
# Virtual Address Space (VAS)
Each [[process]] is given a **VAS** to hold the program's code and data. When the process is not running on the CPU, its VAS is mapped to secondary storage. When the process is running on the CPU, its VAS is mapped to RAM as needed; it is not necessary that the entire VAS fits into RAM. 