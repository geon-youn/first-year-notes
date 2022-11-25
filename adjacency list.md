---
alias: 
tags: COMPSCI_1DM3
created: Thursday March 31, 2022; 10:50:55 
---
# Adjacency list
An **adjacency list** can be used to represent a [[graph]] with no multiple edges by specifying the vertices that are adjacent to each vertex in the graph.

e.g.

| Vertex | Adjacent Vertices |
| ------ | ----------------- |
| a      | b,c,e             |
| b      | a                 |
| c      | a,d,e             |
| d      | c,e               |
| e      | a,c,d             |

| Initial Vertex | Terminal Vertices |
| -------------- | ----------------- |
| a              | b,c,d,e           |
| b              | b,d               |
| c              | a,c,e             |
| d              |                   |
| e              | b,c,d             |
