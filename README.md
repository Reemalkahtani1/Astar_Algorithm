# Astar_Algorithm
A* algorithm implementation on 2*2 puzzle

## The puzzle
it is about a 2D list that contains 4 colors and the goal is to have these colors in the same order as the goal list the available move is :
up -> to swap the two upper tiles
down -> to swap the bottom two tiles
left -> to swap the left two tiles
right -> to swap the right two tiles and the heuristic is based on the misplaced tiles

##A*

A* Search algorithms, unlike other traversal techniques, is a smart and fastest algorithm. It is a combination of a Uniform-cost algorithm and a Greedy algorithm it used to calculate the shortest distance between the initial state and the final state, A* achieves optimality and completeness.
A* algorithm has 3 parameters: -g: the backward cost function -h: the forward cost function,/ and it is a function that estimates how close a state is to a goal -f: the sum of g and h So A* Search orders by the sum of: f(n) = g(n) + h(n)
The algorithm selects the smallest f-valued cell and moves to that cell. This process continues until the algorithm reaches its goal cell

We implemented A* algorithm to find the optimal solution.
for more details please check this link : https://colab.research.google.com/drive/1Cz_UQi-mjIGdx-5DFcLc01lIjgqR0_dL?authuser=1#scrollTo=d157d06c

## Prepared by
Reem abdulmohsen
Neehal 
Reenad
