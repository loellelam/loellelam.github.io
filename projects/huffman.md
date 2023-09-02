---
layout: project
type: project
image: img/huffman-1.png
title: "Huffman Coding"
date: 2021
published: true
labels:
  - Java
summary: "A compression algorithm based on Huffman trees."
---

This Huffman coding project was undertaken as part of my coursework in ICS 211. Its primary aim was to foster a comprehensive understanding of Huffman trees and their application in file compression. An additional objective was to gain proficiency in file input and output operations in the Java programming language.

<img class="img-fluid" src="../img/huffman-2.png">

Professor Edo Biagioni provided students with the BitStringInterface.java, BitString.java, and Huffman.java files. The BitStringInterface.java file contains the methods that must be implemented in BitString.java. The BitString.java file handles bits and bytes by representing it as an array of booleans. The Huffman.java file implements a Huffman tree, which is key to encoding and decoding. The tree is structured such that fewer bits are required to represent high-frequency characters, thus optimizing compression efficiency. 

In the course of this project, I successfully read a file, used the Huffman tree to encode the file, and wrote the output to another file. 

During encoding, the text file is transformed into a concise bit string representation. Subsequently, Huffman decoding utilizes the same Huffman tree employed in encoding, along with the encoded bit string, to reconstruct the original text. This process involves left traversal for zero bits and right traversal for one bits.

I validated the effectiveness of the compression algorithm on one file. The original text was 933 bytes and my algorithm reduced the file size down to 494 bytes. Success!

View the full project on my [GitHub](https://github.com/loellelam/Huffman-Coding).
