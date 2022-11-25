---
alias:
tags: COMPSCI_1JC3
---
# Hypertext Transfer Protocol (HTTP)
HTTP enables a **web browser** (web [[client]]) to request documents from a **web [[server]]**. HTTP also allowes a client to offer documents to a server. It uses [[TCP]] for transport, usually listening at port 80, but may listen at other ports like 81, 8000, 8080, etc. A HTTP transaction consits of a **client request** followed by a **server response**. 

HTTP is **stateless**, so no information about the state of a client-server interaction is recorded. However, state can be tracked using **[[cookies]]**.

A requested document can be processed both **server side** (e.g. by PHP) and **client side** (e.g. by JavaScript).