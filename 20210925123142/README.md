# Greedy Strategy
Given n blocks of length 1.  
*Definition:* ri = amount by which ith block extends beyond the table.  

## Stability Constraint
*Definition:* The center of mass Ck of the top k blocks must lie on the K+1st block. (table = n+1)  

## Greeding stacking
Ck = r(k+1)  
The center of mass of kth block is rk - 1/2  
The center of ass of the top k block is: Ck = ((k-1)C(k-1) + rk - 1/2))/k  
rk - r(k+1) = 1/2k  

## Harmonic number
*Definition:* 1/2 ∑i=1-> n 1/i  
