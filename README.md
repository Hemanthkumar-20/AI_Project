# AI_Project

## Overview

This project implements an interactive version of the classic Dots and Boxes game, offering both single-player and two-player modes. The goal is to draw lines between dots on a grid to form boxes, and the player who forms the most boxes wins. The game incorporates an AI opponent that uses the Minimax strategy with Alpha-Beta Pruning, providing a challenging and strategic gameplay experience.

# Problem Statement
The goal of this project is to develop an engaging version of the Dots and Boxes game, where:

Players compete by drawing lines to create boxes.
Each completed box awards a point to the player.
The game ends when all possible lines are drawn, and the player with the highest score wins.
The project includes AI-based gameplay for a challenging experience, featuring strategic opponents.

# Algorithm
Minimax Strategy with Alpha-Beta Pruning

Minimax Strategy:
Evaluates all possible moves for both the player and the opponent to ensure the best possible outcome.
Calculates the optimal move by simulating future moves and their consequences.

Alpha-Beta Pruning:
Optimizes the Minimax algorithm by skipping unnecessary branches in the search tree.
Reduces computational overhead, enabling the AI to think several steps ahead efficiently.
This combination ensures that the AI plays intelligently, adapting to the current state of the game.
