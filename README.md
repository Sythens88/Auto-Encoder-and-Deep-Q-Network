# Auto-Encoder-and-Deep-Q-Network

This work combines auto-encoder and DQN to get a fast and stable reinforcement learning agent. I do experiments on CartPole and Atari Pong and I find this proposed method can not only help the agent get a higher score with fewer episodes but also make the training process more stable.

The idea of this project is very similar to this paper: [DAQN: Deep Auto-encoder and Q-Network](https://arxiv.org/abs/1806.00630). The differnece between this project and the paper is that I train the auto-encoder and Q network at the same time, but the paper's algorithm trains the auto-encoder first and then train the Q network.

When I implement algorimthms on Atari, I use this codes as reference: [codes](https://github.com/AmazingAng/deep-RL-elements).
