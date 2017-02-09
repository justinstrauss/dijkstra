Justin Strauss 
Columbia University
Dijkstra's Path Between Cities

This project uses Java to implement Dijkstra's algorithm to find the shortest paths between pairs of cities on a map. A graphical user interface lets users visualize both the map itself and the path the algorithm finds between two cities.

Files Included:
1. Dijkstra.java
2. Display.java, Edge.java, Vertex.java
3. citypairs.txt, cityxy.txt

What Problem They Solve:
1. Implement Dijkstra's algorithm to find shortest paths between pairs of cities on a map.
2. Contains the GUI, a graph implementation, and data files representing a map. Vertex.java and Edge.java represent the vertices and edges of a graph.
3. The file cityxy.txt contains a list of cities and their (X,Y) coordinates on the map. These are the vertices in the graph. The file citypairs.txt lists direct connections between pairs of cities. These links are bidirectional, if you can get from New York to Boston, you can get from Boston to New York. These are the edges of the graph.

How to Compile and Run Them:
1. compile: javac Dijkstra.java
   run: java Dijkstra
2. compile: javac *.java
   run: java Display
   a. click "Compute All Euclidean Distances"
   b. select a start and end city
   c. click "Draw Dijkstra's Path"
3. open in a text editor