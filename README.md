# MSTGenerator

##Synopsis
This is a simple tool for generating test cases for Minimum Spanning Tree (MST) algorithms.

##How it works
The script starts by generating the MST itself. Then, it adds additional edges until the graph is fully saturated.

Edge weights are randomly generated. There may be duplicate edge weights, but there will only be 1 MST for the graph.

This works by the principle that adding an edge to the MST will not change it if the added edge's weight is greater than the weight of all edges in the path within the MST between the connected nodes.

##Link
You can view the full page <a href="https://dshepsis.github.io/MSTGenerator/">here</a>.
