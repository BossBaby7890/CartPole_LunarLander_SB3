# PPO Reinforcement Learning on CartPole & LunarLander

This project demonstrates the implementation of **Proximal Policy Optimization (PPO)** using [Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3) to solve two classic reinforcement learning environments:

- **CartPole-v1**
- **LunarLander-v2**

The included Jupyter Notebook (`PPO_CartPole_LunarLander_SB3.ipynb`) trains agents on both environments and evaluates their performance.

---

## 📌 Project Overview
Reinforcement learning (RL) is a machine learning paradigm where agents learn to interact with environments by maximizing cumulative rewards. PPO is a policy-gradient method that strikes a balance between simplicity, sample efficiency, and performance stability.

This project applies PPO to:
- **CartPole**: A simple control environment where the agent must balance a pole on a cart.
- **LunarLander**: A more challenging environment where the agent must land a spacecraft safely.

---

## ⚙️ Requirements
Install the dependencies with:
```bash
pip install stable-baselines3[extra] gym matplotlib
```

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```
2. Open the notebook:
```bash
jupyter notebook PPO_CartPole_LunarLander_SB3.ipynb
```
3. Run the cells to:
    - Train PPO agents on CartPole & LunarLander
    - Evaluate and visualize results

## 📊 Results
### CartPole

- PPO agent quickly learns to balance the pole.

- Achieves near-perfect performance after sufficient training.

### LunarLander

- PPO agent successfully learns to land the spacecraft.

- More training required compared to CartPole due to higher complexity.

## 🔮 Future Work

- Extend to continuous action spaces (e.g., Pendulum, BipedalWalker).

- Compare PPO with other RL algorithms (DQN, A2C, SAC).

- Implement custom reward shaping for improved training performance.

## 📚 References

- [Stable-Baselines3 Documentation](https://stable-baselines3.readthedocs.io/)

- [OpenAI Gym](https://gymnasium.farama.org/)

- [PPO Paper: "Proximal Policy Optimization Algorithms"](https://arxiv.org/abs/1707.06347)
