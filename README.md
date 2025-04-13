The maze programm that i created is written in java programming language, it basically executes two tasks: generating "perfect" maze
and solving it, both operations based on same 2 methods called recursion and backtracking. To generate perfect maze(it is an actual name
of a maze used in math and coding, and not my bragging about project) I firstly created a solid grid that only consists of walls, 
then using DFS(depth-first search), that is basically recurcson algorithm with backtracking, random directions maker and some conditions, so that my maze does not
have any loops and doesn't go through grid edges, this all gave me perfect maze generator(that also gives to user an ability to change size of maze). 
To make maze solver I just copied this DFS algorithm and used it again but in this case 
insead of carving all of the grid, it recurses and if it hits dead end backtracks to the start and deletes all pathes, recurses again, backtracks if hits dead end, repeats again up until it reaches 
finish then the path from the start to the end, that i marked with a number 2, turns into star signs and outputs to the user.
