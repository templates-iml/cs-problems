Dissonant Numbers
-----------------

*Source: https://projecteuler.net/problem=515*

Published on Sunday, 10th May 2015, 07:00 am; Solved by 260; Difficulty
rating: 40%

Let d(p,n,0) be the multiplicative inverse of n modulo prime p, defined
as n × d(p,n,0) = 1 mod p.\
 Let d(p,n,k) = \$\\sum\_{i=1}\^n\$d(p,i,k−1) for k ≥ 1.\
 Let D(a,b,k) = \$\\sum\$(d(p,p-1,k) mod p) for all primes
a ≤ p \< a + b.

You are given:

-   D(101,1,10) = 45
-   D(10<sup>3</sup>,10<sup>2</sup>,10<sup>2</sup>) = 8334
-   D(10<sup>6</sup>,10<sup>3</sup>,10<sup>3</sup>) = 38162302

Find D(10<sup>9</sup>,10<sup>5</sup>,10<sup>5</sup>).
