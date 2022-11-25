---
alias:
tags: COMPSCI_1JC3
---
# Uniform Resource Locators (URLs)
A **URL** is composed of six items:
1. **Protocol**: [[TCP]] protocol needed for transferring the information (e.g. [[HTTP]], https, ftp, file).
2. **Host**: the [[server]] that has the information.
3. **Port**: optional protocol port at which the server is listening (default=TCP port 80).
4. **Path**: the path to the file containing the information.
5. **Query**: optional query concerning the information.
6. **Fragment**: optional fragment identifier.

```ad-example
`<protocol>://<host>[:<port>]/<path>[?<query>][#<fragment>]`
`http://hygelac.cas.mcmaster.ca:80/wmfarmer/`
```


