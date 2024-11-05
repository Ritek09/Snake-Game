#Snake Game

The aim of this practical is to create a simple Snake Game using the Tkinter library in Python.
The game will have a snake that grows when it eats food, and the game will end if the snake
collides with itself or the game window's borders.


To implement the Snake Game using Tkinter, we will follow these steps:

1. Import Required Libraries:
   Use Python’s tkinter library for the GUI and random for food placement.

2. Initialize the Game Window:
   Create the game window using Tkinter and set its title and size.

3. Game Variables:
   Define variables to store the snake's body parts, food position, and direction of
   movement.

4. Snake Movement:
   Define the logic to move the snake using arrow keys (Up, Down, Left, Right).
   Ensure the snake grows when it eats the food and add new body segments.

5. Collision Detection:
   Check if the snake hits the window boundaries or collides with itself, which will
   end the game.

6. Game Over:
   Display a message when the game ends and provide an option to restart the game.

7. Main Game Loop:
   Use a loop to keep updating the snake’s position and continuously redraw the
   game canvas.
