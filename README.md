# 🐍 Snake Game

A classic Snake game built with Python using the Turtle graphics library.

## Features

- **Directional Controls:** Responsive movement using arrow keys (`Up`, `Down`, `Left`, `Right`) with directional locking to prevent accidental self-reversals.
- **Dynamic Food Spawning:** Food appears at randomized locations on the board each time it is eaten.
- **Snake Growth:** Consuming food increases snake length and extends body segments seamlessly.
- **Score Tracking:** Real-time scoreboard displaying the current score at the top of the screen.
- **Collision Detection:** Triggers a "GAME OVER" screen when colliding with walls or the snake's own tail.

## Technologies & Concepts

- **Python 3**
- **Turtle Graphics:** Real-time canvas rendering, key listeners, and custom turtle entities.
- **Object-Oriented Programming (OOP):** Decoupled architecture across `Snake`, `Food`, and `Scoreboard` classes.
- **Game Loop:** Continuous animation cycle using position shifting and smooth screen updates via `tracer(0)`.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/techaseeb/snake-game.git
   cd snake-game
   ```

2. Run the game (no external dependencies required):
   ```bash
   python3 main.py
   ```

## About the Course

Built as part of Angela Yu's **100 Days of Code: The Complete Python Pro Bootcamp**.

## Author

- [techaseeb](https://github.com/techaseeb)
