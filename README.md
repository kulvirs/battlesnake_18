# Battlesnake 2018 Snake
The main template for this snake was adapted from the sample snake code at https://github.com/sendwithus/battlesnake-python.
The snake uses Dijkstra's shortest path algorithm to find the shortest path to the closest food.
Some extra heuristics are added to avoid head-on-head collisions with larger snakes, as well as a fall-back
shortest-path finder if Dijkstra's algorithm is unable to find a path to the food. 

## Tips for next year:
* Don't write all the code in one day, start planning early
* Don't make the snake super greedy, think about when you actually need to go for food
* Add some logic to avoid the snake getting trapped by looping in on itself
* Try using an A* search algorithm intstead

