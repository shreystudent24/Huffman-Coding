<strong>Huffman Coding<br>
The Huffman Coding Algorithm was proposed by David A. Huffman in 1950.<br>

1. Huffman coding is a lossless data compression algorithm.<br>
2. A Huffman code is a particular type of optimal prefix code<br>
3. It is widely used in image (JPEG or JPG) compression.<br>


<strong>Huffman Tree<br>
Step 1: For each character of the node, create a leaf node. The leaf node of a character contains the frequency of that character.<br>

Step 2: Set all the nodes in sorted order according to their frequency.<br>

Step 3: There may exist a condition in which two nodes may have the same frequency. In such a case, do the following:<br>

Create a new internal node.<br>
The frequency of the node will be the sum of the frequency of those two nodes that have the same frequency.<br>
Mark the first node as the left child and another node as the right child of the newly created internal node.<br>
Step 4: Repeat step 2 and 3 until all the node forms a single tree. Thus, we get a Huffman tree.<br>

Website Used for reference: www.javatpoint.com 
