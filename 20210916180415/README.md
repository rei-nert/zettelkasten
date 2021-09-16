# RSA

Before hand: receiver creates a public key and a secrete key.  
1. Generate two distinct primes p and q.  
1. Let n≡p.q.  
1. Select e, such that gcd (e, (p-1), (q-1))= 1 => public key is the pair (e,n)
1. Compute d, such that d.e≡1(mod (p-1)(q-1)).
The secret key is the pair (d, n).  
*Encryption:* m'= rem(m^e, n).  
*Decryption:* m = rem(m^d, n).  
