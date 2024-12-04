# snakegame

Features:
Classic Snake Gameplay: The snake moves around the screen, collecting food to grow longer while avoiding collisions.
Game Over: The game ends if the snake collides with the screen borders or itself.
Score Tracking: The score increases each time the snake eats food, and it is displayed at the top of the screen.
Restart or Quit: After the game ends, you can choose to restart or quit by pressing "C" or "Q" respectively.
Controls:
Arrow keys: Control the direction of the snake (Up, Down, Left, Right).
C: Restart the game.
Q: Quit the game.
Requirements:
Python 3.x
Pygame: You can install it via pip install pygame.
How to Play:
Run the Python script to start the game.
Use the arrow keys to control the snake's movement.
Eat food (red squares) to grow the snake.
Avoid hitting the walls or the snake itself.
When you lose, press "C" to play again or "Q" to quit.
Code Overview:
Game Window: A 600x400 pixel window with a dark background.
Snake: The snake is represented by a green square. The snake's body grows as it eats food.
Food: Food is randomly generated on the screen as a red square. Eating it increases the snake's length and score.
Game Loop: The main game loop continuously updates the game state, checking for user inputs and game-over conditions.




License:
This project is licensed under the MIT License - see the LICENSE file for details.
