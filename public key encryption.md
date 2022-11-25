---
alias:
tags: COMPSCI_1JC3
---
# Public Key Encryption
We need a way to share keys used for conventional encryption and a way for digital signatures to be verified. Thus, public key encryption uses two keys: a **private key** that is kept private and a **public key** that is made public. It uses the same algorithm for going from plaintext to ciphertext and from ciphertext to plaintext; it just depends on which key you use. One of the most popular algorithms for this method of encryption is the [[RSA algorithm]].

## Encryption
Given a plaintext, you use the destination's public key to turn it into ciphertext.
## Decryption
Given a ciphertext, you use your own private key to turn it into plaintext.
## Signature Writing
Given a plaintext, you use your own private key to turn it into ciphertext.
## Signature Reading
Given a ciphertext, you use the source's public key to turn it into plaintext.
## Applications
### [[confidentiality|Confidentiality]]
1. The sender encrypts the plaintext message with the receiver's public key. 
2. The receiver decrypts the ciphertext message with their private key.
### [[integrity|Integrity]], Digital Signature, and Nonrepudiation
1. The sender encrypts the message digest of the sent text with their private key. 
2. The receiver decrypts the encrypted message digest with the sender's public key and compares it with the message digest of the received text. 
### Confidentiality and Integrity
1. The sender encrypts the plaintext message with their private key. 
2. The sender encrypts the ciphertext message with the receiver's public key.
3. The receiver decrypts the ciphertext message with their private key.
4. The receiver decrypts the ciphertext message with the sender's public key. 
### Secret Key Exchange
Using a combination of public key and private key encryptions, you can share your keys for [[conventional encryption]] with no problem.
## History
Public key encryption was discovered but held secret by USA **NSA** and UK **Communications-Electronic Security Group** in 1960s. It was discovered and publicized by **Whitfield Diffie** and **Martin Hellman** at Stanford University in 1976. 