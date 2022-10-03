# Flappy-Bird-AI

A Flappy Bird AI implementing reinforcement learning using Q-learning. 

The reward function was defined to penalise -1000 for a death and 0 otherwise, such that the agent's focus is the get as high a score as possible. This ensures that the reward function has sufficient impact each episode vs an implementation where rewarding +1 for a score increase means that penalisation has little to no effect.
