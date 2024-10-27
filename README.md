# Reinforcement Learning Assignment

Welcome to the **Reinforcement Learning Assignment 24** repository. This project demonstrates the implementation of a Q-learning agent applied to an OpenAI Gym environment.

## Project Overview

The aim of this assignment is to understand and apply Q-learning to solve reinforcement learning tasks. This repository contains a Jupyter Notebook (`q_learning.ipynb`) which outlines the steps for setting up the environment, training the Q-learning agent, and analyzing its performance.

## Contents

- **`q_learning.ipynb`**: The main Jupyter Notebook file that includes:
  - Environment setup and configuration
  - Q-learning agent initialization and training loop
  - Evaluation and performance visualization

## Getting Started

### Prerequisites

- **Python 3.8+**
- **Jupyter Notebook** (or Jupyter Lab for an enhanced notebook experience)
- **Required Libraries**: `gym`, `numpy`, `matplotlib`

To install the necessary dependencies, use:

```bash
pip install -r requirements.txt
```

### Start Jupyter Notebook:

 ```bash
 jupyter notebook
```

### Running the Q-learning Agent:
Run the experience functions
 ```python
 run_experiment(
    env_name='Gym2OpEnv',               # Replace with the environment's class name as a string
    agent_name='QLearningAgent',         # The name of the Q-learning agent class
    train_func_name='train_agent',       # The name of the training function for the Q-learning agent
    allowed_actions=None,                # Pass allowed actions if required, else None
    max_steps=100                        # Set max steps per episode
)
```

### Running the Q-learning Agent:
run the main() function
```python
if __name__ == "__main__":
    main()
```

