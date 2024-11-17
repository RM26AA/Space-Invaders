# Space Invaders Game

## Overview
The Space Invaders Game is a recreation of the classic arcade game using Java and Swing. Players control a spaceship to shoot down waves of aliens while avoiding losing to alien advances. The game features multiple levels, increasing difficulty, and classic arcade-style gameplay.

## Features
- **Spaceship Control**: Players can move the ship left and right and shoot bullets to eliminate aliens.
- **Alien Waves**: Aliens move across the screen and downwards, increasing difficulty with each level.
- **Multiple Levels**: Each cleared level spawns more aliens with increased difficulty.
- **Collision Detection**: Bullets collide with aliens to score points, and the game ends if aliens reach the ship.
- **Score Tracking**: Tracks player’s score based on eliminated aliens and cleared levels.
- **Restart Option**: Players can restart the game after a "Game Over" by pressing any key.

## Technologies Used
- **Java**: Implements the game’s logic, including object-oriented structures for the ship, aliens, bullets, and collision detection.
- **Swing Framework**: Manages the graphical user interface, rendering the game board and game elements.
- **Event Handling**: Captures keyboard inputs for controlling the ship and shooting bullets.
- **Timer and Graphics**: Updates the game state and animations at a smooth 60 frames per second.

## Files
- **App.java**: The entry point for the game, initializing the game window and launching the `SpaceInvaders` class.
- **SpaceInvaders.java**: Contains the main game logic, including ship and alien movement, bullet handling, collision detection, level progression, and score tracking.

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repository-name.git
2. Compile the Java files:
   ```bash
   javac App.java SpaceInvaders.java
3. Run the application:
   ```bash
   java App

## How to Play
- Use the Left Arrow and Right Arrow keys to move the spaceship.
- Press the Spacebar to shoot bullets at the aliens.
- Clear all aliens on the screen to progress to the next level.
- Avoid letting aliens reach the bottom of the screen to prevent a "Game Over."
- After a "Game Over," press any key to restart the game.

## License:
This project is open-source and available under the MIT License.

## Author:
Romeo Maunick - A developer passionate about recreating nostalgic games using modern programming techniques.












