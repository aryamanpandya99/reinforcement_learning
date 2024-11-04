# Reinforcement Learning

This repository contains implementations of various reinforcement learning algorithms in Python. These implementations are part of my self-study journey through the UCL/Deepmind course on Reinforcement Learning available on YouTube, coupled with insights from Sutton and Barto's textbook "Reinforcement Learning: An Introduction."

## Directory Structure

- **DynamicProgramming**: Contains Jupyter notebook implementations of dynamic programming algorithms. Dynamic programming techniques often involve breaking down a problem into simpler subproblems and optimizing solutions. Examples might include algorithms like Policy Iteration and Value Iteration.

- **MonteCarloMethods**: Focuses on implementations of Monte Carlo methods which use randomness to solve problems that might be deterministic in principle. Methods such as On-policy Monte Carlo Control could be included.

- **TDLearning**: Centers around Temporal Difference (TD) learning algorithms. TD learning methods combine the ideas of Dynamic Programming and Monte Carlo methods, and might feature topics such as eligibility traces.

- **ActorCriticMethods**: This directory likely houses Actor-Critic algorithms, a type of RL method where both policy (actor) and value estimate (critic) are learned. This can include different variations of the Actor-Critic methods.

- **ModelBasedRL**: Consists of reinforcement learning algorithms that employ a model of the environment to make decisions. This means they try to predict the next state and the expected reward from the current state and action.

- **PolicyBasedMethods**: Focuses on reinforcement learning algorithms that optimize the policy directly, such as Proximal Policy Optimization (PPO) or REINFORCE.

- **ValueBasedMethods**: Encompasses algorithms that try to optimize the value function, from which the policy can be derived. Examples might be Q-learning or Deep Q Networks (DQN).

The implementations are primarily available as Jupyter notebooks.

## Requirements

To run the Jupyter notebooks, ensure you have Python 3.9+ installed, as well as the following libraries:

- numpy
- matplotlib
- gym
- mujoco 

You can install these libraries using pip.

## How to Use

1. Clone the repository.
2. Navigate to the desired directory.
3. Run the Jupyter notebooks present. Each notebook provides a comprehensive explanation of the algorithm and its usage.


## Acknowledgments

- UCL/Deepmind course on Reinforcement Learning
- Sutton and Barto: Introduction to Reinforcement Learning
- OpenAI gym
