# Asteroids Game

An Asteroids-style arcade game built with Python and Pygame. Control your spaceship, shoot down asteroids, and try to survive as long as possible!

## Table of Contents
- [Features](#features)
- [Controls](#controls)
- [Installation](#installation)
- [Running the Game](#running-the-game)
- [Project Structure](#project-structure)

## Features

- **Player Controls**: Navigate your spaceship and rotate to aim.
- **Shooting Mechanics**: Fire shots to destroy asteroids.
- **Asteroid Splitting**: Large asteroids split into smaller ones when hit.
- **Randomized Asteroid Spawning**: Asteroids spawn at random edges and move in random directions.

## Controls

- **W / S**: Move forward / backward
- **A / D**: Rotate left / right
- **Spacebar**: Shoot

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/1B05H1N/asteroids.git
   cd asteroids-game
   ```

2. **Install Dependencies**:
   Make sure you have [Python](https://www.python.org/downloads/) installed. Then install Pygame:
   ```bash
   pip install pygame
   ```

## Running the Game

Run the game by executing the following command in the terminal:

```bash
python main.py
```

## Project Structure

```plaintext
.
├── main.py              # Main game loop
├── player.py            # Player class for spaceship control
├── asteroid.py          # Asteroid class for individual asteroids
├── asteroidfield.py     # Manages asteroid spawning
├── shot.py              # Shot class for player bullets
├── constants.py         # Game constants (screen size, speed, etc.)
├── circleshape.py       # Base class for circular game objects
├── .gitignore           # Ignore __pycache__ and other unnecessary files
└── README.md            # Project documentation
```