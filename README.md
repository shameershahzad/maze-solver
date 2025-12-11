# Maze Solver with Q-Learning

A simple reinforcement learning project where an agent learns to navigate a maze using **Q-Learning** and find the optimal path from start to goal.

## Features

- **Q-Learning Agent**  
  - Learns the best path through the maze over multiple episodes  
  - Updates Q-values based on rewards  

- **Optimal Path Finder**  
  - Uses learned Q-values to find the best path from start to goal  
  - Moves step-by-step towards the highest-value states  

- **Visualization**  
  - Shows the agent's path through the maze  
  - Maze grid plotted using `matplotlib`  

## How It Works

1. The agent explores the maze for multiple episodes.  
2. Q-values are updated based on rewards for reaching goal or hitting walls.  
3. Once trained, the agent can find the **optimal path** using the learned Q-values.  
4. The path can be visualized on a maze grid with start and goal positions.  

## Tech Stack

- **Language:** Python  
- **Libraries:** NumPy, Matplotlib  

This project demonstrates **reinforcement learning**, **Q-Learning**, and **pathfinding algorithms** in an easy-to-understand maze environment.
