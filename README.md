# P02D13

***== Quest received. Develop an src/game_of_life.c program in C – a visualization of The Game of Life. To display the graphics, only use ASCII characters (with output to the terminal). You need to implement interactive version of the Game of life. Also create the option for adjusting the speed of the "game". ==***

* ***Graphics***

Treat the playing field - a rectangle of 80 by 25 cells – as a matrix of the state of the "game". 
It is assumed that the field is "closed to itself", for example, in the lower right square, the neighbor on the right is the lower left square, and the neighbor on the bottom is the upper right.
Provide for original initialization of the "game" state via stdin. Prepare at least 5 files with initial states for quick launch and initialization through input redirection. 

## Important notes:

* The game must be written in C, have a structured style, and run from the terminal; 
  
* Your source code will be tested by the static analyzer `cppcheck`, as well as the style linter `cpplint`. 
  
* Do not use cumbersome functions, limit them up to 40 lines (excluding `main`).

* Check your program for memory leaks!

> When developing the game, follow the principles of structured programming of E. Dijkstra.


One from s21 pool

This game is an imitation of life. This is a cellular automaton invented by the English mathematician John Conway in 1970. This is a copy made by me and 2 students of school 21 pool.
