# dijkstra_fibonacci_heap
# Objective
This is a program written in Python language that implements Dijkstra’s single-source shortest path algorithm, 
using a Fibonacci heap. The fibonacci heap is implemented entirely from the scratch as a separate class. 
The time complexity of Dijkstra's shortest path algorithm is:
O(|E| |decrease-key(Q)| + |V| |extract-min(Q)|)
where Q is the min-priority queue ordering vertices by their current distance. 



## Code Information
- Argument to the program: 
An input file containing the (non-negative) weighted
undirected graph information (in space-separated three columns format, see below):
Input format: First line contains the total number of vertices n. Subsequent
lines contain information of the edges (between pairs of vertices that are adjacent
to each other) and their corresponding weights, in the following three-column format:

      <vertex_u> <vertex_v> <weight_of_edge_between_u_and_v> 

Note: Vertices are always numbered 1 to n.always consider vertex 
number 1 to be the ‘source’ vertex, from which the shortest 
distances to the remaining vertices (2 to n) are being computed.

- An example input graph file:

      5
      2 4 3
      2 3 6
      1 5 1
      4 5 8
      3 5 7


- Output format: 

Each line of the output file contains two columns of the form: 

    <vertex number> <shortest distance from the source vertex 1>
    
The file will contain one line for each vertex in the graph, in the ascending order
of vertex numbers.


- Example output for the above example input graph:

      1 0
      2 12
      3 8
      4 9
      5 1



- Command line usage of the script:

      dijkstra.py <input graph filename>





