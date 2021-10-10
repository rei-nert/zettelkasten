# Large Deviations
*Corolary:* If R is a non-negative random variable, then ∀c>0, Pr(R>c.Ex(R))<=1/c.  
*Corolary:* If R<=u for some u ∈ ℝ, then ∀x<u, Pr(R<=x)<= (u-Ex(R))/u-x.  
*Chebyshev's Theorem:* ∀x>0 and any random variable R, Pr(|R-Ex(R)|>=x) <= Var(R)/x².  
*Corolary:* Pr(|R-Ex(R)|>=c.σ(R))<= 1/c².  
*Theorem:* For any random variable R, Pr(R-Ex(R)>=c.σ(R))<=1/(c²+1) and Pr(R-Ex(R)<=c.σ(R))<=1/(c²+1).  
*Theorem (Chernoff Bound):* Let T1, T2, ..., Tn be any mutually independent random variables, such that ∀i, 0<=Ti<=1. Let T= ∑j=1->n Tj, then for any c>1, Pr(T>=c.Ex(T))<=e^(-z.Ex(T)), where z=c.ln(c) + 1- c > 0.  

