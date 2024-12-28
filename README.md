# Maze Explorer Game

A Python-based interactive maze game using OpenGL where players navigate through a randomly generated maze, collect gold, avoid obstacles, and reach the goal. The game implements custom graphics using Midpoint Line and Circle Drawing Algorithms.

## Features

- **Random Maze Generation**: Each game starts with a uniquely generated maze
- **Interactive Gameplay**: 
  - Navigate through the maze using arrow keys
  - Collect gold coins (yellow circles) by pressing Enter
  - Remove obstacles (red circles) by pressing J
  - Reach the red goal zone after collecting all gold to win
- **Custom Graphics**:
  - Implemented Midpoint Circle Algorithm (MCA) for drawing filled circles
  - Implemented Midpoint Line Algorithm (MLA) for drawing lines
  - Blue player character with dynamic rendering
  - Pink maze walls for better visibility
- **Game Elements**:
  - Gold coins to collect (yellow circles)
  - Obstacles to remove (red circles)
  - Goal zone (red square)
  - Player character (blue)
- **Game Mechanics**:
  - Time limit of 120 seconds
  - Pause/Resume functionality
  - Restart option
  - Game over conditions:
    - Time runs out
    - Attempting to collect an obstacle
  - Win condition: Collect all gold and reach the goal

## Controls

- **Arrow Keys**: Move the player character
- **Enter**: Collect gold when standing on it
- **J**: Remove obstacle when standing on it
- **ESC**: Exit game
- **Mouse**: Click pause/restart buttons

## Technical Details

- **Language**: Python
- **Graphics**: OpenGL/GLUT
- **Dependencies**:
  - NumPy
  - PyOpenGL
  - Python 3.x

## Installation

1. Ensure Python 3.x is installed
2. Install required packages:
```bash
pip install numpy PyOpenGL PyOpenGL-accelerate
