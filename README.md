# Breadth-first search implementation in Python

![alt_text](http://www.greatandlittle.com/studios/public/blowup-images/Dart/.directed_graph_m.jpg)

Breadth-first search (BFS) is an algorithm for traversing or searching tree or graph data structures. It starts at the tree root (or some arbitrary node of a graph, sometimes referred to as a 'search key'[1]), and explores all of the neighbor nodes at the present depth prior to moving on to the nodes at the next depth level [Wikipedia].

As described above, the script finds the shortest path from node A to B iff A and B are nodes (or vertices) in a given file where A is considered the "root" or source node and B, the destination node. Indicative of BFS, adjacent nodes are visited first until the destination node has been reached or there is no path to the destination node at all.

For demonstration purposes, the files "Wiki-Vote.txt" and "edges.txt" contain node pairs that can be used when testing the script. The "Wiki-Vote.txt" file is a rather large compendium that contains all the Wikipedia voting data from the inception of Wikipedia till January 2008. Nodes in the network represent wikipedia users and a directed edge from node i to node j represents that user i voted on user j. [https://snap.stanford.edu/data/wiki-Vote.html]

