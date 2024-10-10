# Turtle Crossing Game

The Turtle Crossing Game is a simple and fun Python project where the player controls a turtle trying to cross a busy road filled with moving cars. The game keeps track of the player's level and detects collisions with cars or reaching the finish line.

## Features

- Control the turtle using the arrow keys to move up.
- Avoid collisions with moving cars.
- Level up by reaching the finish line.
- Displays a scoreboard that tracks the current level and shows a game-over message when a collision occurs.

## Technologies Used

- Python
- Turtle graphics for the game interface

## Prerequisites

- Python 3.x installed on your machine

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/Selorme/turtle_car_game.git
   cd turtle-crossing-game
   ```

2. Make sure to have the required files for the game:
   - `player.py`
   - `car_manager.py`
   - `scoreboard.py`
   - `main.py` (the code provided above)

3. Run the game:

   ```bash
   python main.py
   ```

## How It Works

1. The game initializes a `Screen` object for the game window and sets up the turtle player, car manager, and scoreboard.
2. The player can control the turtle's movement using the "Up" arrow key.
3. Cars are continuously generated and moved across the screen.
4. The game detects collisions between the player and cars, ending the game if a collision occurs.
5. If the player successfully reaches the finish line, the turtle resets to the starting position, and the level increases.

## Controls

- Press the "Up" arrow key to move the turtle forward.

## Game Over

If the turtle collides with a car, the game will display a game-over message on the scoreboard.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
