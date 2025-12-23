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

Snake/
  src/
    demo/
      GameFrame.java   # Creates the main window and sets up the game panel
      GamePanel.java   # Handles rendering, game loop, and keyboard input
      SnakeGame.java   # Contains the main method to launch the game
  module-info.java     # Java module declaration (if used)
  .classpath           # Eclipse/IDE config
  .project             # Eclipse/IDE config
  .gitignore           # Git ignored files
  README.md            # Project documentation


