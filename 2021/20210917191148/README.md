# Graph Coloring Problem

Given a graph G and K colors, assign a  color to each node, so adjacent nodes get different colors.  
*Definition:* The minimum value of K for which such a coloring exists is the chromatic number of G (ϗ (G)).  
*Definition:* If every node in G has degree ≤ d, the basic coloring algorithm uses at most d+1 colors for G.  


## Basic Coloring Algorithm for G = (V, E)
1. Oder the nodes v1, v2, ..., vn  
1. Oder the color c1, c2, ...,  
1. For i=1, 2, ..., n: Assign the lowest legal color to vi.  

