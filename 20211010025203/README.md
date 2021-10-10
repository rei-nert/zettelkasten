# Random Walks
Probability of up move = p; Probability of down move = 1-p -> mutually independent of past moves (martingale).  
If p =/= 1/2, random walk is biased. If p=1/2, random walk is unbiased.  
*Definition:* W*: event hit $T=n+m before hits 0; D = number of dollars at start; Xn = Pr(W* | D=n).  
*Claim:* Xn = {0 if n=0; 1 if n = T; p.Xn-1 + (1-p).Xn+1 if 0<n<T}     
*Characteristic Equation:* pr² - r + (1-p) = 0 -> r = (1+- (1-2p))/2p -> 1-p/p or 1.  
*Theorem:* If p<1/2, then Pr(win $m before lose $n)<= (p/1-p)^m.     
*Theorem:* If p=1/2, then Pr(win $m before loses $n) = n/n+m.   
*Definition:* S = number of steps until we hit boundry. En = Ex (S|D=n).   
*Claim:* En = {0 if n=0; 0 if n = T; 1+p.En+1 + (1-p).En-1 if 0<n<T}.  
*Theorem:* En = n/1-2p - T/1-2p. ((1-p/p)^n - 1)/((1-p/p)^T - 1).   
*Claim:* As m->∞, En ~ n/1-2p.  
*Theorem:* For p=1/2, En=n.m.  
*Theorem: (Quit while you're ahead):* If you start with $n and p=1/2, and you play until you go broke, then Pr(go broke) = 1.  

