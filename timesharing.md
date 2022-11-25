---
alias:
tags: COMPSCI_1JC3
---
# Timesharing
1. A [[process]] is given control of the CPU for a time period, called a **time slice**.
2. The process is **suspended** at the end of its time slice, its context is saved, and then another process is given control of the CPU. This step is called the **process context switch**.
3. The process is given control of the CPU again when its next turn is scheduled. 