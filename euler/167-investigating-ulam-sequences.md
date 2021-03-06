Investigating Ulam sequences
----------------------------

*Source: https://projecteuler.net/problem=167*


*Difficulty rating: 75%*

For two positive integers a and b, the Ulam sequence U(a,b) is defined
by U(a,b)<sub>1</sub> = a, U(a,b)<sub>2</sub> = b and for k \> 2, U(a,b)<sub>k</sub> is the
smallest integer greater than U(a,b)<sub>(k-1)</sub> which can be written in
exactly one way as the sum of two distinct previous members of U(a,b).

For example, the sequence U(1,2) begins with\
 1, 2, 3 = 1 + 2, 4 = 1 + 3, 6 = 2 + 4, 8 = 2 + 6, 11 = 3 + 8;\
 5 does not belong to it because 5 = 1 + 4 = 2 + 3 has two
representations as the sum of two previous members, likewise 7 = 1 + 6 =
3 + 4.

Find ∑U(2,2n+1)<sub>k</sub> for 2 ≤ n ≤10, where k = 10<sup>11</sup>.
