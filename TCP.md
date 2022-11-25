---
alias:
tags: COMPSCI_1JC3
---
# Transmission Control Protocol (TCP)
TCP provides a **reliable stream delivery service**. It divides a stream of bits into a stream of packets called **TCP segments**. It establishes a virtual circuit **connection** called a **TCP connection** between host-port endpoints, which enables a **[[client]] process** to initiate communication with a **[[server]] process**. 

Reliability is obtained by an **acknowledgment and retransmission** system  that can handle lost, out-of-order, and duplicated data. TCP counts how long it takes for packets from A to go to B. If A doesn't receive an **acknowledgement** from B that the packet was received (or that it was out-of-order), it **retransmits** the packet to B after waiting (to not overload the router).