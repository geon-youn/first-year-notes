---
alias:
tags: COMPSCI_1JC3
---
# Data Compression
**Compression** is used to reduce data size, while **decompression** recovers the original data. Data compression can either be **lossless** (reversible) or **lossy** (irreversible). 

## Two Compression Methods
1. **Huffman coding** (David Huffman, 1952) in which the higher the frequency of a symbol, the fewer bits are used to encode it.
	- The codes are given by a **Huffman tree** that can be automatically generated from a set of character-frequency pairs.
	- Provides lossless compression.
2. **LZ77 algorithm** (Abraham Lempel and Jacob Zib, 1977) replaces repeated strings by references to earlier occurrences. 
	- A reference of the form (`n`, `d`) means the string is replaced by `n`bytes that occur `d` bytes back.
	```ad-example
	The message `bgfgfgfgbggb` is encoded as `bgf(5,2)(2,8)gb` such that it becomes `bgf`+`gfgfg`+`bg`+`gb`=`bgfgfgfgbggb`.
	```
	- Provides lossless compression that is the basis for many common compression algorithms such as `zip`.