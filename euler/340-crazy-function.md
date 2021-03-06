Crazy Function
--------------

*Source: https://projecteuler.net/problem=340*

Published on Sunday, 29th May 2011, 07:00 am; Solved by 614; Difficulty
rating: 30%

For fixed integers a, b, c, define the *crazy function* F(n) as
follows:\
 F(n) = n - c for all n \> b\
 F(n) = F(a + F(a + F(a + F(a + n)))) for all n ≤ b.

Also, define S(a, b, c) =
![p340\_formula.gif](img/p340_formula.gif).

For example, if a = 50, b = 2000 and c = 40, then F(0) = 3240 and
F(2000) = 2040.\
 Also, S(50, 2000, 40) = 5204240.

Find the last 9 digits of S(21<sup>7</sup>, 7<sup>21</sup>, 12<sup>7</sup>).
