---
alias:
tags: COMPSCI_1JC3
---
# Internet Protocol (IP)
IP provides a **connectionless** packet delivery service between internet hosts. It works with a best-effort delivery service (designed to deliver every packet), but is unreliable (packet delivery is not guarenteed). Because IP is connectionless, computers to not have to be connected; instead, packets bounce across a sea of computers and eventually get to its destination. 

IP defines a mechanism consisting of
1. A basic unit of data transfer called an **IP datagram**.
2. Software for routing datagrams using [[IP address]]es.
3. Rules for how hosts (and routers) should process datagrams. 