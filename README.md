# Reinforcement Learning: Value Iteration & Q-Learning

Two classic RL algorithms applied to two different problem settings: exact planning via value iteration on a known MDP, and model-free Q-learning on a Gymnasium environment.

## What's inside

- `1_value_iteration_mdp.ipynb` — a hand-defined 4-state Markov Decision Process (explicit transition probabilities `P` and rewards `R`), solved exactly via the Bellman optimality equation to derive the optimal policy per state.
- `2_qlearning_taxi.ipynb` — a tabular Q-learning agent trained on Gymnasium's Taxi environment, with a hyperparameter sweep over learning rate (`alpha`), discount factor (`gamma`), and exploration rate (`epsilon`), followed by greedy-policy evaluation over 100 episodes.

## Tech stack

Python, NumPy, Gymnasium, Matplotlib

## Run it

```bash
pip install numpy gymnasium matplotlib
jupyter notebook 1_value_iteration_mdp.ipynb   # or 2_qlearning_taxi.ipynb
```
