# Encryption

Before hand: Exchange keys.  
Encryption: m' = Ek (m).  
Decryption: m = Dk (m').  
If gcd (a,b) = 1, ∃s,t => sa + tb = 1  
*Definition:* x is congruent to y modulo n (x≡y(mod n)) if n|(x-y)  
*Definition:* the multiplicative inverse of x mod n is a number x⁻¹, in {0, 1, ..., n-1}, such that x.x⁻¹≡ 1 (mod n).  

## Turing's code V.1

m= Translate a word in a prime number (use the alphabet letter number (e.g. A=1, B=2), and add digits to create a prime number).  
Before hand: Exchange secrete prime k.  
Encryption: m'= k.m  
Decryption m'/k = m  
*Hard to factor a product of 2 large primes*  
However gcd(m'1, m'1)=k  

## Turing's code V.2
Before hand: exchange a public prime p and a secrete prime k.
m= message as number  m ∈ {0,1,..., p-1).  
Encryption: m'=rem(mk, p), rem(mk, p) ≡ mk (mod p).  
Decryption: If k.k⁻¹≡ 1(mod p), then m'.k⁻¹≡ mk.k⁻¹≡ m(mod p) => m = rem(m'.k⁻¹, p)
