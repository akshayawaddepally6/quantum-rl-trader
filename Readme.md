# 💹 Quantum RL Trader

**Quantum RL Trader** is a deep reinforcement learning-based trading system designed to simulate and optimize cryptocurrency trading using a custom OpenAI Gym environment. The agent is powered by a Double Dueling Deep Q-Network (DDQN) and learns to make trading decisions (buy, sell, hold) with the objective of maximizing profits over time.

---

## 🚀 Key Features

* 🧠 **Deep Reinforcement Learning** using a Double Dueling DQN architecture
* 📈 **Custom Trading Environment** built with OpenAI Gym
* 💹 **Crypto OHLCV Data** for realistic market simulation
* 💰 **Sparse Rewards** encourage strategic, long-term decision-making
* ⚙️ **Modular Codebase** for easy customization and experimentation

---

## 🧰 Tech Stack

* Python 3
* TensorFlow / Keras
* Keras-RL
* OpenAI Gym
* NumPy, pandas
* Matplotlib / Seaborn (for visualizations)

---

## 📁 Project Structure

```
quantum-rl-trader/
├── data/                  # Historical crypto data (OHLCV)
├── env/                   # Custom trading environment (Gym-compatible)
├── model/                 # Trained model weights
├── ddqn_rl_trader.py      # Main script for training the agent
├── process_data.py        # Data preprocessing logic
├── visualize.ipynb        # Jupyter notebook for results analysis
├── requirements.txt       # Dependencies
└── README.md              # Project documentation
```

