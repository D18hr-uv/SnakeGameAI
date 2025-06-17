# SnakeGameAI

This project involves implementing an AI agent that learns to play the classic Snake game using reinforcement learning techniques.

## 1. Programming Languages and Libraries

- **Python** is the main language used in this project.
- Key libraries and dependencies include:
  - `pygame` - for rendering and handling game mechanics and UI.
  - `numpy` - for efficient numerical operations.
  - `torch` (PyTorch) - for building and training the neural network model.
  - `matplotlib` and `IPython.display` - for plotting and visualizing training progress.

## 2. Project Overview

- The project features a Snake game environment (`game.py`) and an agent (`agent.py`) that interacts with the environment.
- The agent is trained using Deep Q-Learning (DQN) to learn optimal actions based on its state in the game.
- The agent observes the game state, takes actions, and receives rewards that encourage it to survive and eat food, while penalizing collisions.
- The learning process uses both short-term and long-term memory to improve performance over many games.
- Training progress and scores are visualized in real-time.

## 4. Main Features / Unique Aspects

- **Deep Reinforcement Learning:** The agent uses a neural network (implemented in PyTorch) to approximate Q-values for state-action pairs, enabling it to play the game autonomously.
- **Self-Improving Agent:** Through repeated play, the agent learns from its own experience, using memory replay and exploration strategies (epsilon-greedy).
- **Customizable Game:** The Snake game implementation allows for adjustable grid size, speed, and other gameplay settings.
- **Visualization:** Training performance (scores and mean scores) is visualized using matplotlib for easy monitoring.
- **Modular Code:** The codebase is structured into clear components: game logic, agent logic, model/training logic, and visualization helpers.
- **Sample Training Loop:** The project includes a ready-to-run training loop that continuously improves the agent’s performance.

---

## 5. Results

<p align="center">
  ![Screenshot (90)_](https://github.com/user-attachments/assets/2dd33a70-36bd-4f83-85e7-269a1d73e42c) 
  ![Screenshot (91)](https://github.com/user-attachments/assets/8f5cc56f-8f06-44dc-ab77-b6dba0f642c9)
  ![Screenshot (90)](https://github.com/user-attachments/assets/ebaa733d-fae1-4ea3-a6a2-ba835a22b1b5)
</p>

<p align="center">
  <img src=![Figure_1_1](https://github.com/user-attachments/assets/0e3602c9-590d-4128-86b6-887362558e6a) height="150"/>
  <img src=![Figure_1](https://github.com/user-attachments/assets/9d450144-f85c-43fa-b574-3c03fe595a97) height="150"/>
</p>

*Note: This summary is based on automatic analysis and may not cover all files or features. For a full overview, please explore the [project source code on GitHub](https://github.com/D18hr-uv/SnakeGameAI).*
