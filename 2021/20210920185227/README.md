# Communication networks
*Definition:* Latency is the time required for a packet to travel an input to an output.  
*Definition:* Diameter of a network is the length of the shortest path between the input and output that are farthest apart.  
NxN -> Number of inputs and outputs.  
*Definition:* Congestion is equal to the largest number of paths that pass through a single switch.  

## Complete Binary Tree
- Diameter: 2.(1+log N).   
- Switch Size: 3x3.  
- Number of Switches: 2N - 1.  
- Congestion: N  

## 2D Array
- Diameter: 2N.  
- Switch Size: 2x2.  
- Number of Switches: N².  
- Congestion: 2.  

## Butterfly
Switches is uniquely identified by its row and column (b1, ..., b log N, l(level)).  
- Diameter: 2 + log N.  
- Switch Size: 2x2.  
- Number of Switches: N (1 + log N).  
- Congestion: √N or √(N/2).  

## Banes
- Diameter: 1  + 2 log N.  
- Switch Size: 2x2.  
- Number of Switches: 2N log N.  
- Congestion: 1.  

