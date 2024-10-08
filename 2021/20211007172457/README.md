# Expectations
*Theorem:* Given a probability space S and events A1, A2, ..., An ⊆ S the expected number of theses events to occur is ∑i=1->n Pr(Ai).  
*Theorem:* Pr(T>=1) <= Ex(T).  
*Corolary:* Pr(T>=1) = ∑i=1->n Pr(Ai).  
*Theorem (Murphy's Law):* Given mutually independent events A1, A2, ..., An, the Pr(T=0) <= e^-(Ex(T)).  
*Corolary:* If we expect 10 or more mutually independent events to occur, the probability that no event ocurrs is <= e^-10 < 1/22.000.  
*Theorem (product rule for expectation)*: For any independent random variables R1, R2, Ex(R1.R2) = Ex(R1).Ex(R2).  
*Corolary:* If R1, R2, ..., Rn are mutually independent, then Ex(R1.R2. ... . Rn) = Ex(R1).Ex(R2). ... . Ex(Rn).  
*Corolary:* For any constant a, b and any random variable R, Ex(aR + b) = a.Ex(R) + b.  
