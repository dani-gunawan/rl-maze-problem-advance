# rl-maze-problem-advance
An agent should find the optimal policy from the start to the endpoint in a maze. The maze consists of several walls, oils, and bumps. The state space of this maze is 248 cells. There are four possible actions such as up (U), down (D), right (R), and left (L). Taking an anticipated action will have a probability of 1-p, with an equal probability of p/3 for other actions to neighboring cells. Any action will be rewarded -1. Furthermore, if action is ended up in oil states and bump states will be rewarded -5 and -10, respectively. The reward for the goal state is +200.

The goal of this project was to understand some of the well-known reinforcement learning algorithms, such as Q-Learning, SARSA, and Actor-Critic. 
