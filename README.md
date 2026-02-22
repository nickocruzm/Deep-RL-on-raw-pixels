# Deep Reinforcement Learning with Raw pixel data

Reinforcement learning with visual data has significant implications for fields like robotics,
autonomous systems, and game AI, where agents need to act based on complex,
high-dimensional sensory input. Traditionally, Convolutional Neural Networks have been
employed in RL tasks for processing image data, but recent advancements in Vision
Transformers suggest they could also excel in visual RL tasks by capturing long-range
dependencies. This project aims to compare the effectiveness of CNNs and ViTs when fed raw
pixel data, with the goal of evaluating their ability to learn robust policies directly from visual
inputs.
We experiment with three different Atari games from the gym library: Pong, Breakout, and
Space Invaders. We experiment with a CNN and ViT architecture as the neural network
backbone for Double DQN and PPO. Through our experiments, we conclude that in their current
state, Vision Transformers are not suitable as the neural network backbone of a reinforcement
learning agent. We further hypothesize that transformers will not make good neural network
backbones for any agents with states not in pixel values due to many of the reasons that ViTs
fail.

For full report: [Project Report](RL%20Project%20Report.pdf)

