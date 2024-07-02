# Q-Learning <br>

## Project Overview <br>
This project uses Q-learning, a type of reinforcement learning algorithm, to solve a GridWorld pathfinding problem. Q-learning is a model-free algorithm that aims to learn the value of an action in a particular state in order to maximize the cumulative reward.

## GridWorld Representation <br>
GridWorld: The main part of the image displays a grid environment with various elements: <br>
White Cells: Represent the navigable spaces where the agent can move. <br>
Black Cells: Represent obstacles that the agent cannot pass through. <br>
Blue Cells: Likely indicate target or goal states that the agent aims to reach. <br>
Grid Labels: Each cell is marked with a "+" indicating that it’s a part of the grid. <br>

## Q-learning Parameters <br>
Alpha (Learning Rate): This parameter determines how much new information overrides the old information. A higher alpha means the agent places more emphasis on new information.
<br> <br>
Epsilon (Exploration Rate):  This parameter controls the exploration-exploitation trade-off. With a probability of epsilon, the agent will explore a random action, and with a probability of 1-epsilon, it will exploit the best-known action.
<br><br>
Gamma (Discount Factor): This parameter determines the importance of future rewards. A gamma of 1 means the agent values future rewards as much as immediate rewards.
<br> <br>
Iterations: This indicates the number of iterations or episodes the Q-learning algorithm will run. Multiple iterations help the agent learn the environment better.
<br><br>

## Q-learning Process
Initialization: The agent initializes the Q-values (quality values) for all state-action pairs to zero.
<br> <br>
State Exploration: The agent explores the grid environment starting from a random state. It moves to new states based on its policy, which is influenced by the Q-values and the exploration rate (epsilon).
<br> <br>
Action Selection: The agent selects actions based on the epsilon-greedy policy:
<br><br>
With probability epsilon, the agent selects a random action (exploration). <br>
With probability 1-epsilon, the agent selects the action with the highest Q-value (exploitation). <br>


Policy Update: The agent updates its policy based on the new Q-values, favoring actions with higher Q-values. <br>

Iteration: The process repeats for the number of iterations specified, allowing the agent to learn and refine its policy. <br>

## Grid Display and Controls <br> <br>
Environment Selection: The dropdown allows selecting different grid environments for the agent to navigate. <br>

Mouse Mode: Options such as "Print Values" allow users to interact with the grid and see the Q-values or other information. <br>


## Conclusion
This project demonstrates the application of Q-learning to solve a pathfinding problem in a GridWorld environment. The agent learns to navigate the grid, avoiding obstacles and aiming to reach goal states by maximizing cumulative rewards. The parameters allow for fine-tuning the learning process, balancing exploration and exploitation, and adjusting the importance of future rewards.


<img width="1200" alt="image" src="https://github.com/BilalNaseer7773/Q-Learning/assets/90666694/9a366b62-b5de-4963-a1f5-3eb79745d234">

<img width="1364" alt="image" src="https://github.com/BilalNaseer7773/Q-Learning/assets/90666694/35963b5b-3b2e-4300-91d4-79e58f66db4d">

