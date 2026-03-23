# AlphaZero-scratch-
# AlphaZero from Scratch (TicTacToe & Connect Four)

This project is a simplified implementation of the AlphaZero algorithm using Monte Carlo Tree Search (MCTS) and a neural network. It demonstrates how self-play reinforcement learning can be used to train an agent from scratch without human data.

## 🚀 Features
- AlphaZero-style training loop (self-play → training → iteration)
- Monte Carlo Tree Search (MCTS) implementation
- Neural network for policy + value prediction
- Supports multiple games:
  - TicTacToe
  - Connect Four
- Modular and extensible design (easy to plug in new games)

## 🧠 How It Works
1. The agent plays games against itself (self-play)
2. MCTS is used to explore possible moves
3. The neural network learns:
   - Policy (best move probabilities)
   - Value (winning chances)
4. The model improves over multiple iterations

## 🛠 Tech Stack
- Python
- NumPy
