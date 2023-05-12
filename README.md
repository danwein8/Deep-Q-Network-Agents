# Deep-Q-Network-Agents
Final project for Deep Learning independent study at CUNY Lehman. A few DQN Agents that beat different types of games.<br><br>
## Discrete Mountain Car Agent <br>
- beats classic control game Mountain Car with a discrete action space <br>
## Acrobot Agent <br>
- beats classic control game Acrobot with a discrete action space <br>
## CartPole Agent <br>
- beats classic control game CartPole with a discrete action space. <br>
## Pendulum Agent <br>
- Pendulum agent created with `ActionDiscretizeWrapper()` wrapper to make the continuous action space discrete allowing the DQN agent to work <br>
## Space Invaders Agent <br>
- Space Invaders agent created using a ROM from atarimania.com then defining the QNetwork based on the observation space, the action space, and taking into account the frame skipping inherent to old Atari games <br>
### Info <br>
- The DNQ Agents can only train on environments with a discreet action space, not a continuous action space, so continuous action spaces must be converted. <br>
- Action space is the range of moves you can make as the player. <br>
- Observation space is everything the agent will take into account when choosing its next action (environment). <br>
