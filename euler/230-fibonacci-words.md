Fibonacci Words
---------------

*Source: https://projecteuler.net/problem=230*


*Difficulty rating: 50%*

For any two strings of digits, A and B, we define F~A,B~ to be the
sequence (A,B,AB,BAB,ABBAB,...) in which each term is the concatenation
of the previous two.

Further, we define D~A,B~(n) to be the n<sup>th</sup> digit in the first term of
F~A,B~ that contains at least n digits.

Example:

Let A=1415926535, B=8979323846. We wish to find D~A,B~(35), say.

The first few terms of F~A,B~ are:\
 1415926535\
 8979323846\
 14159265358979323846\
 897932384614159265358979323846\
 1415926535897932384689793238461415**9**265358979323846\

Then D~A,B~(35) is the 35<sup>th</sup> digit in the fifth term, which is 9.

Now we use for A the first 100 digits of π behind the decimal point:

14159265358979323846264338327950288419716939937510\
 58209749445923078164062862089986280348253421170679

and for B the next hundred digits:

82148086513282306647093844609550582231725359408128\
 48111745028410270193852110555964462294895493038196 .

Find ∑~n\\ =\\ 0,1,...,17~   10<sup>n</sup>× D~A,B~((127+19n)×7<sup>n</sup>) .