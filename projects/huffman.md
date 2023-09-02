---
layout: project
type: project
image: img/vacay/vacay-square.png
title: "Huffman Coding"
date: 2021
published: true
labels:
  - Java
summary: "A compression algorithm based on Huffman trees."
---

<img class="img-fluid" src="../img/vacay/vacay-home-page.png">

This Huffman coding project was undertaken as part of my coursework in ICS 211. Its primary aim was to foster a comprehensive understanding of Huffman trees and their application in file compression. An additional objective was to gain proficiency in file input and output operations in the Java programming language.

In the course of this project, I successfully implemented a Huffman tree, which is key to encoding and decoding. The tree is structured such that fewer bits are required to represent high-frequency characters, thus optimizing compression efficiency. 

During encoding, the text file is transformed into a concise bit string representation. Subsequently, Huffman decoding utilizes the same Huffman tree employed in encoding, along with the encoded bit string, to reconstruct the original text. This process involves left traversal for zero bits and right traversal for one bits.

I validated the effectiveness of the compression algorithm on one file. The original text was 933 bytes and my algorithm reduced the file size down to 494 bytes. Success!

View the full project on my [GitHub](https://github.com/loellelam/Huffman-Coding).
