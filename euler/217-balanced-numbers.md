Balanced Numbers
----------------

*Source: https://projecteuler.net/problem=217*


*Difficulty rating: 70%*

A positive integer with k (decimal) digits is called balanced if its
first ⌈<sup>k</sup>/~2~⌉ digits sum to the same value as its last ⌈<sup>k</sup>/~2~⌉
digits, where ⌈x⌉, pronounced ceiling of x, is the smallest integer ≥ x,
thus ⌈π⌉ = 4 and ⌈5⌉ = 5.

So, for example, all palindromes are balanced, as is 13722.

Let T(n) be the sum of all balanced numbers less than 10<sup>n</sup>.\
 Thus: T(1) = 45, T(2) = 540 and T(5) = 334795890.

Find T(47) mod 3<sup>15</sup>