# Dijkstra's algorithm
## Synopsis
Implementation of Dijkstra's Algorithm using Priority Queue Java API that can compute the Shortest path from a given source node. 
## Software Specifications
+ JDK 1.8 
+ JRE 1.8 
## Hardware Specifications
+ i7 3rd Generation Quad Core Processor 
+ 16 Gb of RAM 
## Input data format requirements
n

v1    v2  ew1,2

...

v3    v9  ew3,9

...
## How to run ? 
Create a new folder in your system. 
Download this repository's files into that folder.
Make sure the following commands are running from your terminal/command-line,
Windows 
~~~~sh
javac -version
java -version
~~~~
Ubuntu Linux
~~~~sh
javac --version
java --version
~~~~
Compile the Node.java file using the below command
~~~~sh
javac Node.java
~~~~
Compile the ShortestPathAlgorithm.java file using the below command
~~~~sh
javac ShortestPathAlgorithm.java
~~~~
2 class files gets generated, now run the main file with runtime arguments
~~~~sh 
java ShortestPathAlgorithm 0 Inputs/input16.txt
~~~~
## Average Running time
![Number of vertices vs Time (ms)](https://bytebucket.org/vaikunthsridharan/dijkstras-shortest-path-algorithm/raw/5f3d93c6d8d8ce2ed0a8d8fb14eb1c9680d77388/images/Untitled%20drawing.png)


##### Copyright © 2015 Vaikunth Sridharan