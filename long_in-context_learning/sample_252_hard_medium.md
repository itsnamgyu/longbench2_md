# Metadata

- ID: 66f118e1821e116aacb26b79
- Domain: Long In-context Learning
- Subdomain: User guide QA
- Difficulty: hard
- Length: medium

# Question

All-pairs shortest-paths methods can be used to find shortest paths for all source-destinationpairs of nodes. Which of the following statemens about all-pairs shortest-paths methods are true?
Select one or more:
A. For computing all-pairs shortest-paths in a directed acyclic graph (DAG) which may have negative edgeweight, johnson's algorithm is a worse choice than an algorithm based on the single-source shortest-paths algorithm for DAGs.
B. lf the input graph has an edge (u, u) and the reverse edge (u, w), and both these edges have the same weight, then in johnson's all-pairs shortest-paths algorithm, the new weights of these two edges may not be different.
C. If the input graph has an edge (u, u) and the reverse edge (u, u), and both these edges have the same weight, then in johnson's all-pairs shortest-paths algorithm, the new weights of these two edges arealso the same.
D. By adding one large number to the weight of each edge, we can remove all negative edge weightswithout changing shortest paths.
E. Johnson's all-pairs shortest-paths algorithm does not terminate, if there is a negative cycle in the input graph.
F. None of the other statements is correct.
G. An all-pairs shortest-paths method cannot be an iterative application of the Bellman-Ford algorithm, ifthe graph contains negative weights.
H. Johnson's all-pairs shortest-paths algorithm can be used if the graph contains positive weight cycles.
I. An all-pairs shortest-paths method cannot be an iterative application of Dijkstra's algorithm, if thegraph contains negative weights.
J. For computing all-pairs shortest-paths in a directed acyclic graph (DAG) which may have negative edgeweight, johnson's algorithm is a better choice than an algorithm based on the single-source shortest-paths algorithm for DAGs.

# Choices

- A: B,E,I
- B: B,E
- C: E,I,J
- D: F

# Answer

A
