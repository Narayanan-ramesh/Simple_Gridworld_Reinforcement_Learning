# Simple_Gridworld_Reinforcement_Learning
![image](https://user-images.githubusercontent.com/94230074/173897923-abe42d6f-3825-43c5-a108-9a79b24945d4.png)


The agent has four possible actions in each state (grid square): west, north, south, and east. The actions are unreliable. They move the agent in the intended direction with probability 0.8, and with probability 0.2, they move the agent in a random other direction. If the direction of movement is blocked, the agent remains in the same grid square. The initial state of the agent is one of the five grid squares at the bottom, selected randomly. The grid squares with the gold and the bomb are terminal states. If the agent finds itself in one of these squares, the episode ends. Then a new episode begins with the agent at a randomly selected initial state.

You will use a reinforcement learning algorithm to compute the best policy for finding the gold with as few steps as possible while avoiding the bomb. For this, we will use the following reward function:  −1  for each navigation action, an additional  +10  for finding the gold, and an additional  −10  for hitting the bomb. For example, the immediate reward for transitioning into the square with the gold is  −1+10=+9 . Do not use discounting (that is, set  𝛾=1 ).

Q Learning
![image](https://user-images.githubusercontent.com/94230074/173897977-5161bd3b-fa10-4ea1-8e0d-cfb177d248df.png)
