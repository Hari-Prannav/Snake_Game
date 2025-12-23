# Snake Game (Java)

A simple implementation of the classic **Snake** game built in Java using Swing.  
The player controls a snake that grows longer as it eats food, while avoiding collision with the walls and its own body.

## Features

- Classic grid‑based snake movement with smooth keyboard controls.
- Apple/food generation at random positions on the board.
- Score tracking based on the number of apples eaten.
- Game over detection when the snake hits a wall or itself.

## Technologies

- **Language:** Java  
- **GUI:** Swing (`JFrame`, `JPanel`, `Timer`, etc.)  
- **Concepts:** Basic OOP, event handling, game loop, collision detection.

## Project structure

src/
  SnakeGame.java   # Main class, creates the game window
  GamePanel.java   # Handles rendering, game loop, and keyboard input
  Snake.java       # Manages snake position, movement, and collision logic

