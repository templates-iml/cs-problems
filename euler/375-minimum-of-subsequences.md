Minimum of subsequences
-----------------------

*Source: https://projecteuler.net/problem=375*


*Difficulty rating: 40%*

Let S~n~ be an integer sequence produced with the following
pseudo-random number generator:

  ------------------------ ------------------------ ------------------------
  S~0~                     S~n+1~
  =~ ~                     =~ ~
  290797~ ~                S~n~<sup>2</sup> mod 50515093
  ------------------------ ------------------------ ------------------------

Let A(i, j) be the minimum of the numbers S~i~, S~i+1~, ... , S~j~ for i
≤ j.\
 Let M(N) = ΣA(i, j) for 1 ≤ i ≤ j ≤ N.\
 We can verify that M(10) = 432256955 and M(10 000) = 3264567774119.

Find M(2 000 000 000).