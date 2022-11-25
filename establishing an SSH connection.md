---
alias:
tags: COMPSCI_1JC3
---
# Establishing an SSH Connection
1. The [[client]] and [[server]] establish a [[TCP]] connection.
2. The client and server exchange protocol identification.
3. The server sends its ([[RSA algorithm|RSA]] or DSA) [[public key encryption|public host key]] to client.
4. The client generates a **session key**, encrypts it with the public host key, and sends it back to the server with a selected cipher type (e.g. DES or Blowfish).
5. The server decrypts the **session key** with its **private host key** and then sends an encrypted confirmation to the client. 
6. The client then authenticates the server.
	1.  The client checks if the server's **public host key** is in the user's **known host file**.
	2.  If no **public host key** for the server is present, the user is given the opportunity to add to to the known hosts file.
	3.  If the server's **public host key** has been changed, the user is warned that the server may have been [[integrity|compromised]].
7.  The client authenticates the user to the server using (RSA or DSA) public key encryption.
	1.  The server sends a challenge to the client encrypted with the **user's public key** stored on the server. 
	2.  The client decrypts the challenge with the **user's private key**, which is decrypted using the **passphrase** supplied by the user when the private/public key pair was generated.[^1]
	3.  The client sends the required response signed using the **user's private key** to the server.
	4.  The server verifies the response using the **user's public key**.
8.  The client makes several requests to finish setting up the secure channel.

[^1]: Depending on the version of SSH, other versions of user authentication methods can be supported, such as standard password authentication.
