# AI Program for Connect Four 

## Project Overview
This project explores the use of minimax algorithms in the real world.  The example Connect Four AI program in this project utilizes minimax algorithms to select the best decision when playing Connect Four against human players. The program is very successful and performs significantly better than creators. The study also investigates how the program performs against a random column selector and weak AI depending on the search depth of the algorithm, and the result reveals that the algorithm with depth of 3 would be the best model, considering its winning rate and run time costs. This research contributes to the understanding of the use of minimax algorithm and provides practical insight for creators and researchers of Ai programs for two player turn placed games.

## Purpose
The primary goal for this research is to develop a deep understanding of minimax algorithm, as well as to inform the utilization of the algorithm for game enthusiasts and programming learners.

## Algorithms
### Minimax Algorithm
The minimax algorithm is used to find the optimal strategy in a two-player game, and assumes that each player chooses his or her own moves while taking into account the best moves of the opponents. It recursively navigates the tree and evaluates the favorability of each game-state node, and then selects the optimal move that results in the best score for the AI player and worst score for the opponent. 

### Alpha-Beta Pruning
This is a technique that reduces the number of nodes that need to be explored. We utilized this optimization technique in order to increase computational efficiency. 

## Evaluation
We optimized the program by controlling the depth of the results tree analyzed. A higher depth will increase the number of future outcomes analyzed and result in smarter potential AI decisions but increase the computation time of the algorithm. To increase the sample size of our tests without needing human players we needed some dummy algorithms to test our AI against. One such dummy was an algorithm that randomly selected columns but was normally distributed to select middle columns more often. The second dummy algorithm was actually the most stripped down version of our AI algorithm to use a depth of one. This would allow us to see how the algorithm competed against itself. A key component is that we always forced our AI algorithm to go second. This is because going first is a big advantage and would overestimate the AI performance. It also allowed us to randomize the first move of the game to simulate different scenarios. 

## Result
It was showns that the best overall model would be to play with a search depth of 3. This provided a consistently winning automated player with small run time costs. It also felt the most comparable to going against a human player in terms of reaction speed and decision making. 

## Source Code
Open the Jupytor Notebook (https://github.com/ssunami/ConnectFour/blob/main/ConnectFour_Project_Code.ipynb) 
The Notebook should be loadable in browser. This can also be downloaded locally though requires installing Python and Jupyter.

## Project Report
Full project report is available here (https://github.com/ssunami/ConnectFour/blob/main/Project_Report_ConnectFour.pdf)

