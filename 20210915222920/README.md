# Known-plain text attack: 
Know message m and encryption m' = rem(mk, p).  
m'≡ mk (mod p).  
gcd (m,p) = 1.  
- compute the m⁻¹ -> m.m⁻¹≡1(mod p)
- m'. m⁻¹≡ k m.m⁻¹≡ k (mod p)
- compute: k⁻¹ (mod p)
