# Tic Tac Toe AI Implementations

## Overview

This Jupyter Notebook project demonstrates multiple artificial intelligence approaches to solving the Tic Tac Toe game, showcasing different reinforcement learning and game tree search algorithms. The implementations include:

1. Value Iteration
2. Policy Iteration
3. Monte Carlo Tree Search (MCTS)

## Algorithms Implemented

### 1. Value Iteration
- Calculates the optimal value for each game state
- Uses a reward function that considers:
  - Winning/losing states
  - Strategic position control (center, corners)
  - Potential win and block opportunities
- Provides a systematic way to evaluate game states

### 2. Policy Iteration
- Improves policy through iterative evaluation and improvement
- Develops a strategy that maximizes expected rewards
- Includes sophisticated state evaluation considering:
  - Win/loss conditions
  - Center and corner control
  - Potential win and blocking opportunities

### 3. Monte Carlo Tree Search (MCTS)
- Uses probabilistic game tree exploration
- Balances exploration and exploitation
- Performs multiple simulations to determine optimal moves
- Uses Upper Confidence Bound (UCB) for selecting actions

## Requirements

- Python 3.7+
- Jupyter Notebook
- NumPy library
- itertools library

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/tic-tac-toe-ai-notebook.git
cd tic-tac-toe-ai-notebook
```

2. Set up a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install required packages:
```bash
pip install jupyter numpy
```

## How to Run

1. Launch Jupyter Notebook:
```bash
jupyter notebook
```

2. Open the notebook in your browser

3. Run the cells sequentially for each AI implementation
   - Each implementation has an interactive gameplay section
   - You can modify parameters and run simulations

## Game Mechanics

- 3x3 grid
- X and O players
- Input moves as numbers 0-8 corresponding to grid positions

```
0 | 1 | 2
---------
3 | 4 | 5
---------
6 | 7 | 8
```

## Customization

You can modify parameters in each implementation:
- Discount factors
- Number of iterations
- Exploration weights
- Reward function details

## Learning Objectives

This project demonstrates:
- Reinforcement learning techniques
- Game tree search algorithms
- State space exploration
- Strategic decision-making in games

## Notebook Structure

- First cell: Tic Tac Toe Environment
- Second cell: Value Iteration implementation
- Third cell: Policy Iteration implementation
- Fourth cell: Monte Carlo Tree Search implementation

## Contributions

Contributions are welcome! Please submit pull requests or open issues to suggest improvements or additional AI techniques.

## License

MIT License

## Acknowledgments

Inspired by reinforcement learning and game theory research.
