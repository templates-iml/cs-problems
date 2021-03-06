Clock sequence
--------------

*Source: https://projecteuler.net/problem=506*

Published on Sunday, 8th March 2015, 04:00 am; Solved by 424; Difficulty
rating: 30%

Consider the infinite repeating sequence of digits:\
 1234321234321234321...

Amazingly, you can break this sequence of digits into a sequence of
integers such that the sum of the digits in the n'th value is n.

The sequence goes as follows:\
 1, 2, 3, 4, 32, 123, 43, 2123, 432, 1234, 32123, ...

Let v<sub>n</sub> be the n'th value in this sequence. For example, v<sub>2</sub> = 2,
v<sub>5</sub> = 32 and v<sub>11</sub> = 32123.

Let S(n) be v<sub>1</sub> + v<sub>2</sub> + ... + v<sub>n</sub>. For example, S(11) = 36120, and
S(1000) mod 123454321 = 18232686.

Find S(10<sup>14</sup>) mod 123454321.
