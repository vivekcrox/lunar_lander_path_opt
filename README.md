# 🚀🌘 Lunar Lander Trajectory Optimization

<img src="https://github.com/vivekcrox/lunar_lander_trajectory_optimization_-vivek-/assets/133307528/b1a6cbe5-a277-4c7b-b740-3aafc31bedd6" width="500" alt="lander_img">
<img src="https://github.com/vivekcrox/lunar_lander_trajectory_optimization_-vivek-/assets/133307528/869a73e2-0722-4fdb-88e3-af5ff099ac71" width="500" alt="lander_img">

## Implements a reinforcement learning algorithm to train a rocket landing agent using the LunarLander-v2 environment.
- The code defines the environment, the agent, and the training parameters.
- The agent is trained for a specified number of episodes and the training progress is logged using TensorBoard and CSV files.
- After training, the agent is evaluated on the environment and a video of the evaluation is saved.

## ✨ The code is structured as follows:

### 1. Environment and Agent Setup:
- The code defines the environment as LunarLander-v2 and sets the random seed.
- The agent is defined as a Rocket class, which is a neural network that outputs the probability of taking each action.

### 2. Training:
- The code defines the training parameters such as the batch size, learning rate, and gamma.
- The code creates a trainer object that manages the training process.
- The agent is trained for a specified number of episodes.

### 3. Evaluation:
- The code evaluates the trained agent on the environment and saves a video of the evaluation.

### 4. Summary:
- The code provides a summary of the training process and the performance of the trained agent.

  <img src="https://github.com/vivekcrox/lunar_lander_trajectory_optimization_-vivek-/assets/133307528/16ee2af5-082c-4094-b256-c7d5fad463ce" width="500" alt="lander_img">

## ✨ Conclusion
- This code demonstrates how to train a reinforcement learning agent to solve a challenging control problem.
- The code can be easily adapted to other environments and agents.
