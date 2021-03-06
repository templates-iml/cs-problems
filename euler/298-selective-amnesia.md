Selective Amnesia
-----------------

*Source: https://projecteuler.net/problem=298*

Published on Friday, 25th June 2010, 09:00 pm; Solved by 451; Difficulty
rating: 60%

Larry and Robin play a memory game involving of a sequence of random
numbers between 1 and 10, inclusive, that are called out one at a time.
Each player can remember up to 5 previous numbers. When the called
number is in a player's memory, that player is awarded a point. If it's
not, the player adds the called number to his memory, removing another
number if his memory is full.

Both players start with empty memories. Both players always add new
missed numbers to their memory but use a different strategy in deciding
which number to remove:\
 Larry's strategy is to remove the number that hasn't been called in the
longest time.\
 Robin's strategy is to remove the number that's been in the memory the
longest time.

Example game:\

  -----------------------------------------------------------------------------
  Turn
  Called\
  number
  Larry's\
  memory
  Larry's\
  score
  Robin's\
  memory
  Robin's\
  score
  ------------ ------------ ------------ ------------ ------------ ------------
  1            2            3            4            5            6
  1            2            4            6            1            8
  1            1,2          1,2,4        1,2,4,6      1,2,4,6      1,2,4,6,8
  0            0            0            0            1            1
  1            1,2          1,2,4        1,2,4,6      1,2,4,6      1,2,4,6,8
  0            0            0            0            1            1
  -----------------------------------------------------------------------------

Denoting Larry's score by L and Robin's score by R, what is the expected
value of |L-R| after 50 turns? Give your answer rounded to eight decimal
places using the format x.xxxxxxxx .
