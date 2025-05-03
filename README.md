# File-Compressor
---

A File-Compressor based on Huffman Coding (A lossless, bottom-up compression algorithm) built using C++ that can compress and decompress any text files.

```
To compress text file:

 g++ encode.cpp huffman.cpp -o main

./main input.txt compressed.huff

To generate output.txt

g++ decode.cpp huffman.cpp -o main

./main compressed.huff output.txt
```