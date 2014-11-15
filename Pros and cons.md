Pros
----

- Built from very simple components
- Simple components allow for easy implementation in hard ware
- Simple components make the algorithm quick in both hardware and software
- Works as a drop in replacement of SHA2
- The best attack on JH requires very large resources to implement and during the decision process were uable to be verified
- "Keccak has the largest security margin, with 79% of its hash function still unbroken; JH has the smallest security margin, with 38% unbroken"
- "there is no known way for an attacker to exploit the JH domain extension to find preimages, or second preimages more efficiently than a brute-force search"
- 256 Sboxes can be computed in parallel
- Of the finalists, BLAKE and JH were only tweaked to increase the number of rounds. This does not affect any cryptanalysis prior to the tweak and is, therefore, the most innocuous type of tweak. 
- While a pseudo-collision attack exists on the JH compression function (because of its ability to be reversed) it was deemed to be minor

Cons
----

- MAC is not the greatest in terms of efficiency
	- Push for dedicated MAC protocol in place of using hashing functions for MACs
