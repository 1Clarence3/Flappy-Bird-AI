# Flappy-Bird-AI

A Flappy Bird AI implementing reinforcement learning using Q-learning in Python. 

The reward function was defined to penalise -1000 for a death and 0 otherwise, such that the agent's focus is the get as high a score as possible. This ensures that the reward function has sufficient impact each episode vs an implementation where rewarding +1 for a score increase means that penalisation has little to no effect.

The agent was initially trained for around 10,000 episodes without any exploration and the learning rate alpha kept constant at 0.7. Eventually, the agent learns and is able to achieve scores over a thousand.

Modules:<br/>
anaysis.py: Analysis file for investigating agent performance <br/>
config.py: Config file for changing the agent training parameters<br/>
flappy_rl.py: FlapPyBird implementation with agent training/runner code included<br/>
q_learning.py: An implementation of a Q-learning agent class made with reference to rl-flappybird<br/>
