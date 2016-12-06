# MSTGenerator

##Synopsis
This is a simple tool for generating test cases for Minimum Search Tree algorithms.

##How it works
The script starts by generating the Minimum-Spanning Tree itself. Then, it adds additional edges until the graph is fully saturated.

Edge weights are randomly generated, but all exclusive (each specific edge weight appears just once in the graph).

This works by the principle that adding an edge to the MST will not change it if the added edge's weight is greater than the weight of all edges in the path within the MST between the connected nodes.
