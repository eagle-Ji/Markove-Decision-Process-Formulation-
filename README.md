# Markove-Decision-Process-Formulation-
The project contains a notebook containg MDP (State, Action, reward, next state, done) signals for applying reinofrcement learning algorithms. 
Code for Soft Actor Critic Algorithm. 
# "Reinforcement Learning-Based Microrobot Navigation Along Circular Paths Using Magnetic Field Control"


---

## 🚀 Features

- ✅ Microrobot environment with magnetic field actuation
- ✅ State, Action, Reward, Next State, Done (MDP)
- ✅ Continuous control with **Soft Actor-Critic (SAC)**
- ✅ Reward shaping to enforce circular trajectory
- ✅ Visual plots of path and performance

---

## 🧬 Environment Details

- **State Space**:
  - Current position `(x, y)`
  - Orientation (angle)
  - Distance to circular trajectory

- **Action Space**:
  - Magnetic field vector `(Bx, By)` (continuous)

- **Reward Function**:
  - Positive reward for staying on the circular path
  - Penalty for deviation
  - Termination reward when reaching goal

- **Done**:
  - Robot reaches within a threshold of final target point
  - Maximum steps exceeded

---

## 🧠 Algorithm: Soft Actor-Critic (SAC)

- Entropy-regularized RL algorithm for stable training
- Continuous action space (perfect for magnetic field control)
- Automatic temperature tuning

---

## 🧪 Requirements

Install dependencies with:

```bash
pip install -r requirements.txt

