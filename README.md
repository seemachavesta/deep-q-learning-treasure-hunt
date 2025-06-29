# deep-q-learning-treasure-hunt


This project implements a pirate intelligent agent that uses deep Q-learning to solve a treasure hunt maze game. The goal of the agent is to locate the treasure before the human player by learning the optimal path using reinforcement learning techniques. This README provides an overview of the work completed and a reflection on how it connects to core computer science concepts.

 Project Overview

What code were you given?

I was provided with starter Python files that included the environment (TreasureMaze.py), experience replay mechanism (GameExperience.py), and helper functions for running the simulation. A Jupyter Notebook was also provided with a partially completed structure and # TODO sections for implementing the deep Q-learning training logic.

What code did you create yourself?

I completed the qtrain() function that implemented the core deep Q-learning algorithm. I handled action selection using epsilon-greedy policy, managed the experience replay buffer, and trained the neural network using Keras. I also modified training hyperparameters to improve agent performance and debugged issues related to state handling, exploration strategies, and model evaluation.

 Connecting to Computer Science

What do computer scientists do and why does it matter?

Computer scientists solve complex, real-world problems by designing algorithms and developing software systems. In this project, I acted as a computer scientist by building an intelligent agent that learns autonomously through trial and error. This work matters because it contributes to developing smarter, more adaptive systems—skills that are essential in industries like game development, robotics, and autonomous navigation.

How do I approach a problem as a computer scientist?

I approached this project by:

Understanding the problem domain (pathfinding and reinforcement learning)

Breaking the problem into smaller components (training, exploration, environment interaction)

Iteratively coding, testing, and refining the solution

Debugging using logic and runtime analysis

This structured, modular, and data-driven approach is typical in computer science.

What are my ethical responsibilities to the end user and the organization?

As a developer, my ethical responsibilities include ensuring that the software behaves reliably, safely, and transparently. For intelligent systems like this agent, it's also important to consider fairness, data quality, and decision traceability. If applied in a real-world product, the agent must not make biased or harmful decisions and should be accountable for its actions within the game world.

How to Use This Project

Clone this repository

Open the Jupyter Notebook (TreasureHuntGame.ipynb)

Run all cells to train the pirate agent

Observe learning progress in terminal output

Run completion_check(model, TreasureMaze(maze)) to verify learning success
