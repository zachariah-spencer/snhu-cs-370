# SNHU CS-370: Pirate Pathfinding Treasure Hunt

## Project Description
A reinforcement-learning agent (“the pirate”) learns to navigate a discrete grid toward hidden treasure. We compare classical human search strategies (landmarks, trial-and-error) to a Deep Q-Learning approach that treats the maze as an MDP, balancing exploration vs. exploitation via an ε-greedy policy.

## Code Provided vs. Code Developed
- **Provided**  
  - Tabular Q-learning scaffold  
  - Environment simulator (grid, reward structure)  
- **Developed**  
  - Deep Q-Network (DQN) architecture (input preprocessing, neural network model)  
  - Experience replay buffer and target network update  
  - ε-decay schedule and training loop  
  - Reward shaping and obstacle-collision handling  

## Connection to Computer Science

### What Computer Scientists Do & Why It Matters
- **Design algorithms** to solve real-world problems automatically  
- **Abstract and model** complex systems (e.g., treating a maze as an MDP)  
- **Build scalable solutions** that adapt without manual heuristics  
- Impact domains from robotics to gaming by making systems more intelligent and autonomous

### Problem-Solving Approach as a Computer Scientist
1. **Formalize** the problem (state, actions, rewards)  
2. **Select** an algorithmic framework (MDP + Deep Q-Learning)  
3. **Implement**, test, and iterate (neural network, replay buffer, ε-greedy policy)  
4. **Evaluate** performance, refine hyperparameters, and compare against baselines

### Ethical Responsibilities
- **End-User Safety & Transparency**  
  - Ensure the agent behaves predictably and document its learning limitations  
- **Data Integrity & Privacy**  
  - Use and store any user data (e.g., maps, logs) securely and responsibly  
- **Organizational Accountability**  
  - Clearly communicate capabilities and risks to stakeholders to avoid misuse  