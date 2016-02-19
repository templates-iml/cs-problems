Odd period square roots
-----------------------

*Source: https://projecteuler.net/problem=64*


*Difficulty rating: 20%*

All square roots are periodic when written as continued fractions and
can be written in the form:

√N = a~0~ +

1

 

a~1~ +

1

 

 

a~2~ +

1

 

 

 

a~3~ + ...

For example, let us consider √23:

√23 = 4 + √23 — 4 = 4 + 

1

 = 4 + 

1

 

1\
√23—4

 

1 + 

√23 – 3\
7

If we continue we would get the following expansion:

√23 = 4 +

1

 

1 +

1

 

 

3 +

1

 

 

 

1 +

1

 

 

 

 

8 + ...

The process can be summarised as follows:

  ---------- ---------- ---------- ---------- ---------- ---------- ----------
  a~0~ = 4,  a~1~ = 1,  a~2~ = 3,  a~3~ = 1,  a~4~ = 8,  a~5~ = 1,  a~6~ = 3,
                                                                     
  1\         7\         2\         7\         1\         7\         2\
  √23—4      √23—3      √23—3      √23—4      √23—4      √23—3      √23—3
   =          =          =          =          =          =          = 
  √23+4\     7(√23+3)\  2(√23+3)\  7(√23+4)\  √23+4\     7(√23+3)\  2(√23+3)\
  7          14         14         7          7          14         14
   = 1 +      = 3 +      = 1 +      = 8 +      = 1 +      = 3 +      = 1 + 
  √23—3\     √23—3\     √23—4\     √23—4      √23—3\     √23—3\     √23—4\
  7          2          7                     7          2          7
  ---------- ---------- ---------- ---------- ---------- ---------- ----------

It can be seen that the sequence is repeating. For conciseness, we use
the notation √23 = [4;(1,3,1,8)], to indicate that the block (1,3,1,8)
repeats indefinitely.

The first ten continued fraction representations of (irrational) square
roots are:

√2=[1;(2)], period=1\
 √3=[1;(1,2)], period=2\
 √5=[2;(4)], period=1\
 √6=[2;(2,4)], period=2\
 √7=[2;(1,1,1,4)], period=4\
 √8=[2;(1,4)], period=2\
 √10=[3;(6)], period=1\
 √11=[3;(3,6)], period=2\
 √12= [3;(2,6)], period=2\
 √13=[3;(1,1,1,1,6)], period=5

Exactly four continued fractions, for N ≤ 13, have an odd period.

How many continued fractions for N ≤ 10000 have an odd period?