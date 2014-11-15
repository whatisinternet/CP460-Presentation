Pros
----

- Built from very simple components
- Simple components allow for easy implementation in hard ware
- Simple components make the algorithm quick in both hardware and software
- Works as a drop in replacement of SHA2
- "the best attacks on Grøstl, JH, and Skein would require huge computational resources to implement, and cannot be fully verified"
- "Keccak has the largest security margin, with 79% of its hash function still unbroken; JH has the smallest security margin, with 38% unbroken"
- "there is no known way for an attacker to exploit the JH domain extension to find preimages, or second preimages more efficiently than a brute-force search"
- 256 Sboxes can be computed in parallel

Cons
----

- MAC is not the greatest in terms of efficiency
	- Push for dedicated MAC protocol in place of using hashing functions for MACs
