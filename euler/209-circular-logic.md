Circular Logic
--------------

*Source: https://projecteuler.net/problem=209*


*Difficulty rating: 60%*

A k-input *binary truth table* is a map from k input bits (binary
digits, 0 [false] or 1 [true]) to 1 output bit. For example, the 2-input
binary truth tables for the logical AND and XOR functions are:

  ------------------------ ------------------------ ------------------------
  x                        0                        0
  y                        0                        1
  x AND y                  0                        0
  ------------------------ ------------------------ ------------------------

  ------------------------ ------------------------ ------------------------
  x                        0                        0
  y                        0                        1
  x XOR y                  0                        1
  ------------------------ ------------------------ ------------------------

\

How many 6-input binary truth tables, τ, satisfy the formula

τ(a, b, c, d, e, f) AND τ(b, c, d, e, f, a XOR (b AND c)) = 0

\

for all 6-bit inputs (a, b, c, d, e, f)?
