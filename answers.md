# CMPS 2200 Recitation 7
## Answers

**Name:**___Riley Martin 
Maddie Bonanno______________________


Place all written answers from `recitation-07.md` here for easier grading.



- **d.**

File | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length
----------------------------------------------------------------------
f1.txt    |            1340         |     826           | 1.62 to 1
alice29.txt    |         1039367            |      676374          | 1.53 to 1
asyoulik.txt    |         876253            |        606448        | 1.44 to 1
grammar.lsp    |          26047           |     17356           | 1.5 to 1
fields.c    |        78050             |       56206         | 1.39 to 1

Yes, there is a clear trend in the data. Huffman coding decreases the cost of the code by at least 1/3, as most ratios are around 1.5:1 which is equivalent to 3:2. 


- **e.**

In this situation, Huffman coding is expected to result in a cost of nlog(n) assuming that there are n leaves in the balanced tree. This result should be consistent across documents. 