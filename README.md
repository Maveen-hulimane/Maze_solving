# Maze_solving

Prepare the Bunnies' Escape

A function solution(map) that generates the length of the shortest path from the prison door to the escape pod, 
where you are allowed to remove one wall as part of your remodeling plans. The path length is the total number of nodes 
you pass through, counting both the entrance and exit nodes. The starting and ending positions are always passable (0). 
The map will always be solvable, though you may or may not need to remove a wall. The height and width of the map can be 
from 2 to 20. Moves can only be made in cardinal directions; no diagonal moves are allowed.


Test case:

    1.  Input:solution([[0, 1, 1, 0], 
                        [0, 0, 0, 1], 
                        [1, 1, 0, 0], 
                        [1, 1, 1, 0]])
        output:7
    2.  Input:solution([[0, 0, 0, 0, 0, 0], 
                        [1, 1, 1, 1, 1, 0], 
                        [0, 0, 0, 0, 0, 0], 
                        [0, 1, 1, 1, 1, 1], 
                        [0, 1, 1, 1, 1, 1], 
                        [0, 0, 0, 0, 0, 0]])
            output:11
    3.  Input:solution([[0, 1, 1, 1],
                        [0, 1, 0, 0],
                        [1, 0, 1, 0],
                        [1, 1, 0, 0]]) 
            output:7

