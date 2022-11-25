---
alias:
tags: COMPSCI_1JC3
---
# SSH Architectural Layers
 SSH is a **secure shell** that is used for remote login to a remote [[server]].
 ## Transport Layer
 1. Initial session key exchange (using Diffie-Hellman).
 2. Server authentication.
 3. Encryption, compression, and [[integrity]] verification.
 4. Session key re-exchange.
 ## User Authentication Layer
 The user is authenticated using several available methods including **password** and [[public key encryption|public key]].
 ## Connection Layer
 Management of SSH communication channels (which may be encrypted). There are several steps to [[establishing an SSH connection]].
