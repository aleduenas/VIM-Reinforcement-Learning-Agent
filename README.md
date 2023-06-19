# Nim Game Learning Agent

This Python-based project is an implementation of a reinforcement learning agent to play the game of Nim.

## Overview
The game of Nim is a strategy game between two players. The game starts with a certain number of tokens and players alternate taking 1, 2, or 3 tokens. The player who takes the last token loses.

In this implementation, we have a learning agent that plays against a "random" player (who selects their action uniformly at random) for a specified number of episodes. The learning agent uses a Q-learning algorithm, which is a simple form of reinforcement learning to improve its performance over time.

The game environment and the results of each round can be visualized using `OpenCV`.

## Requirements

This project currently only requires access to a web browser to run as it is run over Google Colab. To run locally it requires Numpy, matplotlib, opencv-python, and PIL but the code would need to be adjusted to display the game. 

## How to Run

Simply open the link to the Google Colab and run. After training, the agent will play a game against the user, providing a visual representation of the game status and actions taken by both the player and the agent.

The user will be prompted to input their action at each turn. The game continues until all tokens are taken.

You can alter the number of training episodes and other parameters as per your requirements.

## License

This project is available under the [MIT License](https://opensource.org/licenses/MIT).

## Future Enhancements

- Improve the efficiency of the learning algorithm
- Show more insightful details during training
- Add a GUI for better visualization and user interaction
