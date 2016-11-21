This code solves the 8-Puzzle problem using various kinds of searches.
We have a start state and a goal state for the 8-Puzzle and we use all the following 9 search strategies on it to reach the goal state.

This code has following searches:
1-> Brute Force DFS
2->Brute Force BFS
3->Iterative Depth First Search
4->Greedy Best First Search using Manhatten Heuristic
5->Greedy Best First Search using Out of Place Tile Heuristic
6->A Star Search using Manhatten Heuristic
7->A Star Search using Out of Place Tile Heuristic
8->IDA Star Search using Manhatten Heuristic
9->IDA Star Search using Out of Place Heuristic

The programs returns the time used, the total number of nodes visited, ram used and other statistics to help compare various search strategies and determine the best one.

The program can be run using command python search.py
Also, basic user interactivity has been provided and three sample inputs have been included in the code to check the results.