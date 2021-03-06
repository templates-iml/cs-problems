Coresilience
------------

*Source: https://projecteuler.net/problem=245*

Published on Friday, 15th May 2009, 02:00 pm; Solved by 555; Difficulty
rating: 80%

We shall call a fraction that cannot be cancelled down a resilient
fraction.\
 Furthermore we shall define the resilience of a denominator, R(d), to
be the ratio of its proper fractions that are resilient; for example,
R(12) = <sup>4</sup>⁄<sub>11</sub>.

  ------------------------ ------------------------ ------------------------
  The resilience of a
  number d \> 1 is then
  φ(d)\
  d − 1
  , where φ is Euler's
  totient function.
  ------------------------ ------------------------ ------------------------

  ------------------ ------------------ ------------------ ------------------
  We further define
  the
  **coresilience**
  of a number n \> 1
  as C(n)
  = 
  n − φ(n)\
  n − 1
  .
  ------------------ ------------------ ------------------ ------------------

  ------------------ ------------------ ------------------ ------------------
  The coresilience
  of a prime p is
  C(p)
  = 
  1\
  p − 1
  .
  ------------------ ------------------ ------------------ ------------------

Find the sum of all **composite** integers 1 \< n ≤ 2×10<sup>11</sup>, for which
C(n) is a unit fraction.
