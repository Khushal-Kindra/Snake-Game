# Snake Game

This is a classic Snake game implemented in Python using the Turtle graphics library. The game features a growing snake, food that animates when eaten, and obstacles that the snake must avoid.

## Features

- Classic snake movement controlled with the keyboard
- Food that the snake eats to grow longer
- Animated food upon collision
- Randomly placed obstacles
- Score tracking with a high score feature
- Game restarts upon collision with walls, obstacles, or the snake itself

## Prerequisites

- Python 3.x
- Turtle graphics library (usually included with Python's standard library)

## How to Play

- Use the `W`, `A`, `S`, `D` keys to control the snake:
  - `W` to move up
  - `A` to move left
  - `S` to move down
  - `D` to move right
- Avoid the walls, obstacles, and the snake's own body
- Eat the food to grow longer and increase your score
- The game will restart if the snake collides with the walls, obstacles, or itself

## Running the Game

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/snake-game.git
    ```
2. Navigate to the project directory:
    ```bash
    cd snake-game
    ```
3. Run the game:
    ```bash
    python snake_game.py
    ```

## Code Overview

### Main Components

- **Window setup**: Creates the game window and sets up the screen.
- **Snake head**: Represents the snake's head, which the player controls.
- **Food**: Represents the food that the snake eats to grow.
- **Obstacles**: Randomly placed objects that the snake must avoid.
- **Score tracking**: Displays the current score and high score.

### Key Functions

- `animate_food()`: Animates the food when it is eaten.
- `create_obstacle()`: Creates a single obstacle at a random position.
- `place_obstacles(num_obstacles)`: Places the specified number of obstacles on the screen.
- Movement functions (`go_up()`, `go_down()`, `go_left()`, `go_right()`): Control the snake's direction.
- `move()`: Moves the snake in the current direction.
- Game loop: Updates the screen, checks for collisions, and updates the score.

## Customization

You can customize various aspects of the game, such as:
- The speed of the snake (`delay` variable)
- The appearance of the snake, food, and obstacles (colors and shapes)
- The number of obstacles (`place_obstacles(5)`)



https://github.com/Khushal-Kindra/Snake-Game/assets/159249366/49cc0964-92cb-43ff-8ed2-1f986ff667ec




Enjoy the game and happy coding!

---
