# ANN Scheduling Sensei 🧠📅  
Year: 2025  

_Built from scratch, this Artificial Neural Network (ANN) predicts task-to-employee mapping penalties to support smart scheduling decisions._

## Project Overview

This project implements an Artificial Neural Network (ANN) entirely from scratch in Python to support scheduling optimisation. It predicts penalties for assigning tasks to employees based on constraints like skill match, workload, deadlines, and difficulty.

## Key Technical Highlights

- ANN designed and trained without machine learning libraries (no TensorFlow, no PyTorch)
- Forward and backpropagation coded manually
- Constraint-driven penalty function guides learning
- Hyperparameter tuning and loss tracking across epochs
- Structured for experimentation with mapping strategies

## Features

- Compares multiple models to determine best architecture of ANN for this problem
- Outputs comparison graphs for user assessment

## Outputs

- Final trained model weights and predictions
- Penalty scores per task-employee mapping
- Comparison : 1. Epoch vs Loss, 2. Learning Rate vs Loss, 3. Activation Function vs Loss, 4. Batch Size vs Epoch Time
- CSV exports of population and predictions

## Dependencies

- Python 3.10+
- `numpy`
- `pandas`
- `matplotlib`

_All libraries used are standard and installable via `pip`._

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/nohat-noplay/ANN-scheduling-sensei.git
   cd ANN-scheduling-sensei
2. Open Jupyter Notebook and Run All cells

## Important Notes for the User:
This is a portfolio project. It's built to demonstrate understanding of machine learning fundamentals — especially building models from the ground up — not to serve as a production-grade tool.

## Credits
Saf Flatters

## Connect with Me

📫 [LinkedIn](https://www.linkedin.com/in/safflatters/)

## License and Usage

![Personal Use Only](https://img.shields.io/badge/Personal%20Use-Only-blueviolet?style=for-the-badge)

  

This project is intended for personal, educational, and portfolio purposes only.

You are welcome to view and learn from this work, but you may not copy, modify, or submit it as your own for academic, commercial, or credit purposes.