Prime factors of n<sup>15</sup>+1
------------------------

*Source: https://projecteuler.net/problem=421*


*Difficulty rating: 50%*

Numbers of the form n<sup>15</sup>+1 are composite for every integer n \> 1.\
 For positive integers n and m let s(n,m) be defined as the sum of the
*distinct* prime factors of n<sup>15</sup>+1 not exceeding m.

E.g. 2<sup>15</sup>+1 = 3×3×11×331.\
 So s(2,10) = 3 and s(2,1000) = 3+11+331 = 345.\
\
 Also 10<sup>15</sup>+1 = 7×11×13×211×241×2161×9091.\
 So s(10,100) = 31 and s(10,1000) = 483.\

Find &Sum; s(n,10<sup>8</sup>) for 1 ≤ n ≤ 10<sup>11</sup>.
