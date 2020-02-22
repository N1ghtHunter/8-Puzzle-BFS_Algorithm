# 8 Puzzle Solver

## Authors
Raj Prakash Shinde- 116852104- https://github.com/RajPShinde/
 
## Overview
This is a code to solve 8 Puzzle Problem using BFS(Breadth First Search) Algorithm.

## Description
The code solves any given state of a 8 Puzzle problem to reach the goal state of  1 2 3 4 5 6 7 8 0.
The data structure used in this code is a list, which is used to store all the node information.
The code also stores the required states to reach the goal in nodePath.txt, all explored nodes in Nodes.txt and
the node info in NodesInfo.txt. The maximum time required to solve can be upto 1hr 30mins

## Dependencies
1. python 3

## Run
1.Unzip the folder</br>
2.Run the python code 8_puzzle_bfs.py in Spyder</br>
            OR</br>
3.Open a terminal in folder containing code and type 'python 8_puzzle_bfs.py'</br>
4.After running, Enter a start node row wise (e.g 1 2 3 0 4 5 8 6 7) as specified in terminal/Console</br>
5.Wait till the action set and path is displayed (may take 1 hr 30 mins)</br>
6.text files will be generated in the same folder as the code</br>
 
## Documentation
1.BlankTileLocation(N)- Used to find the Location of a blank tile in the node

2.ActionMoveUp(b,N)- Used to move the blank tile Up
 
3.ActionMoveDown(b,N)- Used to move the blank tile Down

4.ActionMoveLeft(b,N)- Used to move the blank tile Left

5.ActionMoveRight(b,N)- Used to move the blank tile Right

6.generate_path(path,N)- Used to generate node path after goal node is reached

7.AddNode(P,Pf,iteration,child,j)- Performs the Up, Down, Left, Right Operations on Parent node

8.column(N)- Converts a node into coloumn wise string

9.run(N)- Runs the flow for BFS Algorithm

## Reference
1.https://www.w3schools.com/python/python_lists.asp</br>
2.https://massivealgorithms.blogspot.com/2015/06/how-to-check-if-instance-of-8-puzzle-is.html


