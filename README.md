# Kung Fu Game using Reinforcement Learning 
## Overview
This repository contains a Kung Fu game trained using reinforcement learning techniques, specifically the A3C (Asynchronous Advantage Actor-Critic) algorithm. The game is designed to demonstrate how AI can be used to master complex environments and learn optimal strategies for controlling a character in a dynamic game setting.
## Training Details
The AI agent is trained using the A3C algorithm, which is well-suited for environments where decisions must be made in real-time. The algorithm works by asynchronously running multiple instances of the game environment, allowing the agent to learn from different scenarios simultaneously.
## Tech Stack
### Programming Languages & Libraries
**Python 3**: The core language used for implementing the game environment, training algorithms, and simulation.<br>
**PyTorch**: Deep learning library used for building and training neural networks, particularly in the reinforcement learning model, offering dynamic computational graphs and easy debugging.<br>
**TensorFlow**: Utilized for deep learning tasks alongside PyTorch, specifically for comparison and experimentation with different frameworks.<br>
**Keras**: High-level neural network API running on top of TensorFlow, used for prototyping and fine-tuning models.<br>
**NumPy**: Fundamental package for scientific computing, handling large datasets and performing efficient mathematical operations.<br>
## Reinforcement Learning Framework
**OpenAI Gym**: Provides the environment interface and utilities for reinforcement learning, enabling the creation of custom environments for the game.<br>
**Stable Baselines3**: A set of improved implementations of reinforcement learning algorithms, integrated with custom modifications for enhanced performance in this project.<br>
**A3C (Asynchronous Advantage Actor-Critic)**: The primary reinforcement learning algorithm used, leveraging asynchronous parallel environments to stabilize learning in complex scenarios.<br>
# Game Development
**Pygame**: Python library used for creating the game's graphical interface, rendering sprites, and handling real-time user inputs.<br>
**Box2D**: 2D physics engine used to simulate the physical interactions and collisions within the game environment, providing a realistic combat experience.<br>
## Data Handling & Processing
**Pandas**: Data manipulation and analysis library, used for preprocessing input data, managing training logs, and analyzing performance metrics.<br>
**Matplotlib & Seaborn**: Visualization libraries used to plot training progress, reward trends, and other important performance metrics.<br>
