# Chess Bot with Neural Network
This repository contains code for a machine learning chess bot implemented in Python using Jupyter Notebook. The bot utilizes neural networks to make decisions during gameplay.

## Requirements
Before running the code, make sure to install the required Python packages:

```python
!pip install python-chess
```


## Overview
The chess bot consists of the following components:

Data preprocessing: The training data is loaded from a CSV file containing chess board positions and corresponding scores.
Model training: Three separate neural network models are trained based on different phases of the game (opening, midgame, and endgame).
Model evaluation: The trained models are evaluated using validation data to ensure their effectiveness.
Gameplay: The bot is capable of playing against human opponents, making decisions based on the current board position and the trained neural networks.
Usage

## To use the chess bot, follow these steps:

Clone the repository and navigate to the project directory.
Prepare your training data in CSV format.
Run the Jupyter Notebook file containing the code.
Train the neural network models using your training data.
Play against the bot using the provided gameplay function.

## Code Structure
chess_bot.ipynb: Jupyter Notebook containing the code for the chess bot.
train.csv: Sample training data in CSV format.# Chess-AI-Machine-Learning

## Credit
Credit to "Global Hack Week Games: Train an AI to Play Chess" for the foundation code

https://www.kaggle.com/competitions/train-an-ai-to-play-chess
