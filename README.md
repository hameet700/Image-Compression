# Image-Compression
ABSTRACT

Huffman coding is one of the basic compression methods that have proven useful in image and video compression standards. Compression of the image is an important task as its implementation is easy and obtains less memory. The purpose of this is to analyse Huffman coding technique which is used to remove the redundant bits in data by analysing different characteristics or specifications. 


In Huffman coding, an input image is split into equal rows & columns, and at the final stage sum of all individual compressed images which not only provide better results but also the information, the content will be kept secure. It has been shown that image compression using Huffman coding provides better image quality, moreover Huffman coding is quite faster.

Data Compression

Data Compression can be defined as the coding of data to minimize its representation. The compression process is called lossless if the original one can be exactly reconstructed from the compressed copy; otherwise it is called lossy. The theoretical background of the data compression techniques is strong and well established. There is a limit to the amount of compression we can gain from a digital file and that this limit is the Shannon entropy. The highest the entropy is, the lowest the possibility of compressing data shall be.
Data compression is today essential for digital communication. Without data compression we would not have digital televisions, smart-phones, satellite communications, Internet, etc.
ALGORITHM 

1.start

2.Read the BMP Image into 2D array.

3.Create a Histogram of the pixel intensity values present in the Image.

4.Find the number of pixel intensity values having non-zero probability of occurrence

5.Calculating the maximum length of Huffman code words

6.Define a structure which will be used to store all the nodes of the Huffman Tree.

7.Define another structure which is used to store the position of new generated nodes.

8.Declare an array of structures.

9.Initialize the array of structure with information of the leaf nodes.

   10.Sort the array which is used to store the position of new generated 
       nodes.

  11. Build a Huffman Tree.
          
a.Combine the two lowest probability leaf nodes into a new node.

b.Replace the two leaf nodes by the new node and sort the nodes according to the new probability values.

c.Continue the steps (a) and (b) until we get a single node with probability value 1.0. We will call this node as root

d.Backtrack from the root, assigning ‘0’ or ‘1’ to each intermediate node, till we reach the leaf nodes


12. Encode the Image

13. end

