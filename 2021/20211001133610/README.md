# Inclusion-Exclusion
- |M| = |M\E| + |M∩E|  
- |E| = |E\M| + |M∩E|  
- |M∪E| = |M\E| + |M∩E| + |E\M|  
- |M| + |E| counts M∩E twice  
- |M∪E| = |M| + |E| - |M∩E|  
- |M∪E∪S| = |M| + |E| + |S| - |M∩E| - |M∩S| - |E∩S| + |M∩E∩S|  
- |A1∪A2∪...∪An| = ∑i=1->n |Ai| - ∑1<=i1<i2<=n |Ai1∩Ai2| + ∑1<=i1<i2<i3<=n |Ai1∪Ai2∪Ai3| ... + (-1)^(n+1) |A1∩...∩An|= ∑k=1->n (-1)^(k+1) ∑S⊆{1...n} such that |S| = k |∩i∈S Ai|  

