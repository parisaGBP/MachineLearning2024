# Mini Project 4: Deep Reinforcement Learning Adventures!

## Overview
This repository details my journey through **Mini Project 4** for the *Machine Learning (Spring 1403)* course. We dove headfirst into the exciting world of Deep Reinforcement Learning (DRL), implementing and comparing Deep Q-Networks (DQN) and Double Deep Q-Networks (DDQN). This project involved building agents, training them on environments, and analyzing their learning progress.

---

# What I Explored & Learned

## Deep Q-Networks (DQN)
*   **Implementation:** Developed a DQN agent from scratch, including the core components like a replay buffer and the DQN class itself.
*   **Training:** Trained the DQN agent, observing its learning curve.
    *   *Key Scores:*
        *   Episode 50: Average Score: -184.04
        *   Episode 100: Average Score: -152.41
        *   Episode 150: Average Score: -120.11
        *   Episode 200: Average Score: -97.79
        *   Episode 250: Average Score: -64.84
*   **Visualization:** Created a video demonstrating the DQN agent's performance during training. *(Video attached)*

## Double Deep Q-Networks (DDQN)
*   **Environment:** Tackled the more complex **LunarLander-v2** environment using DDQN.
*   **Advanced Training:** Trained the DDQN agent for up to 1000 episodes, noticing significant improvements.
    *   *Key Scores:*
        *   Episode 50: Average Score: -177.99
        *   Episode 100: Average Score: -169.63
        *   Episode 150: Average Score: -144.18
        *   Episode 200: Average Score: -98.62
        *   Episode 250: Average Score: -51.72
        *   Episode 300: Average Score: -38.95
        *   Episode 350: Average Score: -32.04
        *   Episode 400: Average Score: 4.08
        *   Episode 450: Average Score: 67.32
        *   Episode 500: Average Score: 146.89
        *   Episode 550: Average Score: 190.70
        *   Episode 580: Average Score: 200.60
        *   **Environment solved in 480 episodes!**
        *   Final Average Score at solving: 200.60
*   **Visual Evidence:** Generated a video showcasing the DDQN agent's successful learning process on LunarLander-v2. *(Video attached)*
---

## Tools & Libraries
- Python
- Deep Learning Framework (e.g., TensorFlow/PyTorch - *mention which one if you used a specific one*)
- Libraries for DRL implementation (e.g., custom classes for DQN/DDQN)
- Libraries for environment interaction (e.g., OpenAI Gym)
- NumPy, Matplotlib (for analysis and plotting)

---

## Author
**Parisa Ghorbanpour**  
Graduate Student, Machine Learning 2024  
K. N. Toosi University of Technology
