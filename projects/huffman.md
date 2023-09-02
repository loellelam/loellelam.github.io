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

this huffman coding project was for my ICS 211 class. the main purpose was to get familiar with huffman trees and use them to compress a file. the other objective was to learn how to read and write to files in java. 

i implemented a Huffman tree which allows encoding and decoding using the tree. The tree is the key to encoding and decoding as it's structured so that fewer bits are required to represent high frequency characters.  my text file gets encoded into a bit string.

gets compressed into a bit string.

Huffman decoding takes the same Huffman tree as was used for encoding, and a bit string containing the encoding, and reproduces the original text by traversing the tree to the left for every zero bit and to the right for every one bit.



i tested my compression algorithm and it turned the original file was 933 bytes into the compressed file is 494 bytes.

View the full project on my [GitHub](https://github.com/loellelam/Huffman-Coding).
