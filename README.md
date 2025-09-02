> **Disclaimer:**  
> This project was developed as part of a **University of Liverpool** assignment.  
> It is for **educational purposes only** and must not be copied, reused, or distributed without permission, in accordance with the University's academic integrity policies.

# Deep Q-Networks (DQN) with PyTorch

A Jupyter Notebook project implementing a **Deep Q-Network (DQN)** to solve reinforcement learning tasks.  
It demonstrates how to train an agent to interact with and learn from an environment using **Q-learning with deep neural networks**, **experience replay**, and **epsilon-greedy exploration**.

---

## What it does
- **Environment setup**
  - Uses OpenAI Gym environments (e.g., CartPole, LunarLander)
  - Observes state spaces and action spaces dynamically
- **Model architecture**
  - Fully connected feedforward neural network with configurable hidden layers
- **Training loop**
  - Implements **epsilon-greedy policy** for exploration vs exploitation
  - Uses **experience replay** to stabilise training
  - Target network updated periodically for more stable Q-value updates
- **Evaluation**
  - Tracks and visualises episode rewards
  - Compares performance over training episodes
  - Plots moving averages of rewards to measure learning stability
- **Inference**
  - Runs a trained agent in the environment to demonstrate learned behaviour

---

## Files
- `Deep Q-Networks.ipynb` — main notebook with DQN implementation, training, and evaluation  
- `models/` — (optional) folder for saving and loading trained agent models

---

## How to Run
1. **Clone or download the project**
   ```bash
   git clone https://github.com/your-username/deep-q-networks.git
   cd deep-q-networks
