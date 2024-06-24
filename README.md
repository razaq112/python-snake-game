# Katking

Katking is a simple Snake game implemented using Pygame. The objective of the game is to control the snake to eat food, grow longer, and avoid running into itself or the walls.

## How to Run

1. Ensure you have Python and Pygame installed. If not, you can install Pygame using the following command:

    ```sh
    pip install pygame
    ```

2. Clone this repository to your local machine:

    ```sh
    git clone https://github.com/razaq112/katking.git
    cd katking
    ```

3. Run the game:

    ```sh
    python katking.py
    ```

## How to Play

- Use the arrow keys to control the direction of the snake:
  - `Left Arrow`: Move left
  - `Right Arrow`: Move right
  - `Up Arrow`: Move up
  - `Down Arrow`: Move down
- The snake will continue moving in the current direction until a new direction is chosen.
- The game ends if the snake runs into itself.
- The objective is to eat the food that appears on the screen, which will cause the snake to grow longer. The score increases by 1 point for each food eaten.

## Game Over

When the game ends, a "GAME OVER!!!" message is displayed along with your final score. The game then waits for 2 seconds before closing.

## References

This game was inspired by the tutorial video on creating a Snake game with Pygame. You can watch the tutorial here: [Snake Game Tutorial](https://www.youtube.com/watch?v=7TYqRgiRhG8&t=422s)

## License

This project is licensed under the MIT License.
