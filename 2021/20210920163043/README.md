# Minimum weight spanning tree  
*Definition:* The MST of an edge-weighted graph G is the ST of G, with the smallest possible sum of edge weights.  
*Algorithm:* Grow a subgraph one edge at a time, at each step: Add the minimum weight edge that keeps the subgraph acyclic.
*Theorem:* For any connected weighted graph G, the algorithm produces a MST.  

