### Training an AI Agent for SuperTuxKart Ice Hockey
Key Skills: Machine Learning, Deep Learning, Reinforcement Learning, Imitation Learning, Computer Vision, Data Augmentation, Python

# Overview:
Developed an intelligent game-playing agent for SuperTuxKart Ice Hockey, an environment similar to Rocket League. The project explored multiple learning approaches—vision-based learning, reinforcement learning, and imitation learning—to train an agent capable of maximizing goals scored.

# Technical Approach
- **Vision Learning:** Built a Convolutional Neural Network (CNN) to detect and track the puck in images. Despite achieving 90% accuracy in puck detection, real-time decision-making challenges led to pivoting towards state-based methods.
- **Reinforcement Learning (RL):** Implemented Proximal Policy Optimization (PPO) to learn optimal strategies based on rewards. However, tuning the reward function proved challenging, leading to suboptimal policies.
- **Imitation Learning (Final Approach):** Trained a model to mimic a high-scoring expert agent (Jurgen). Used a dataset of 8.7 million observations collected from 4000 games, feeding them into a shallow linear neural network to predict optimal actions (acceleration, steering, braking).

1-min video clip
https://github.com/user-attachments/assets/9873b547-6ef4-4d04-b8bf-3e5edbfbb638



# Results
- The imitation learning agent successfully learned to emulate expert behavior, achieving 28 goals across 32 games—nearly matching the expert's performance.
- Data augmentation techniques (increasing goal-adjacent frames and adding random noise) significantly improved consistency and goal-scoring ability.
- The project highlighted the power of leveraging expert data to efficiently train AI agents in complex environments.

# Key Takeaways
- Machine Learning Engineering: Hands-on experience with deep learning, reinforcement learning, and imitation learning methodologies.
- Big Data Processing: Managed and processed millions of training data points.
- Model Optimization: Applied data augmentation and hyperparameter tuning to enhance performance.
- AI for Games: Built a competitive AI agent, with applications extending to robotics and autonomous decision-making.
