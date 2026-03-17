# RL Q-Learning Assignment

## Overview

This project implements Q-Learning on the FrozenLake-v1 environment from Gymnasium.  
The agent learns a policy to navigate the frozen lake and reach the goal without falling into holes.

## How to Run

1. Open the notebook `qlearning_frozenlake.ipynb` in Jupyter or Google Colab.
2. Install dependencies:
   - `pip install gymnasium`
   - `pip install matplotlib seaborn`
3. Run all cells in order.

## Results

- Environment: `FrozenLake-v1` (is_slippery=True)
- Episodes: 5000
- Average reward over 100 evaluation episodes (greedy policy): *[your number here]*

The notebook includes:
- Exploration of the environment (random actions).
- Q-Learning training loop.
- Plot of reward per episode and moving average.
- Optional Q-table heatmap.
