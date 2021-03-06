Special partitions
------------------

*Source: https://projecteuler.net/problem=333*


*Difficulty rating: 35%*

All positive integers can be partitioned in such a way that each and
every term of the partition can be expressed as 2<sup>i</sup>x3<sup>j</sup>, where i,j ≥
0.

Let's consider only those such partitions where none of the terms can
divide any of the other terms.\
For example, the partition of 17 = 2 + 6 + 9 = (2<sup>1</sup>x3<sup>0</sup> + 2<sup>1</sup>x3<sup>1</sup> +
2<sup>0</sup>x3<sup>2</sup>) would not be valid since 2 can divide 6. Neither would the
partition 17 = 16 + 1 = (2<sup>4</sup>x3<sup>0</sup> + 2<sup>0</sup>x3<sup>0</sup>) since 1 can divide 16.
The only valid partition of 17 would be 8 + 9 = (2<sup>3</sup>x3<sup>0</sup> + 2<sup>0</sup>x3<sup>2</sup>).

Many integers have more than one valid partition, the first being 11
having the following two partitions.\
11 = 2 + 9 = (2<sup>1</sup>x3<sup>0</sup> + 2<sup>0</sup>x3<sup>2</sup>)\
11 = 8 + 3 = (2<sup>3</sup>x3<sup>0</sup> + 2<sup>0</sup>x3<sup>1</sup>)

Let's define P(n) as the number of valid partitions of n. For example,
P(11) = 2.

Let's consider only the prime integers q which would have a single valid
partition such as P(17).

The sum of the primes q \<100 such that P(q)=1 equals 233.

Find the sum of the primes q \<1000000 such that P(q)=1.
