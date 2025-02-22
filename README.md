# First Game - Pygame Platformer

Welcome to **First Game**, a simple platformer game built using the Pygame library in Python. This game features a player character that can move left, right, and jump, as well as shoot projectiles at an enemy. The goal is to defeat the enemy while avoiding collisions to maintain your score.

## Features

- **Player Movement**: Move left, right, and jump using the arrow keys.
- **Shooting**: Shoot projectiles using the spacebar.
- **Enemy AI**: An enemy that patrols back and forth and can be defeated by shooting it.
- **Score System**: Gain points by hitting the enemy and lose points if the player collides with the enemy.
- **Animations**: Walking and standing animations for both the player and the enemy.

## Requirements

- Python 3.x
- Pygame library

## Installation

1. **Install Python**: If you don't have Python installed, download and install it from [python.org](https://www.python.org/).

2. **Install Pygame**: You can install Pygame using pip. Open your terminal or command prompt and run:
   ```bash
   pip install pygame
   ```

3. **Download the Game Files**: Clone or download this repository to your local machine.

4. **Run the Game**: Navigate to the directory containing the game files and run the script:
   ```bash
   python first_game.py
   ```

## Controls

- **Left Arrow Key**: Move the player to the left.
- **Right Arrow Key**: Move the player to the right.
- **Up Arrow Key**: Make the player jump.
- **Spacebar**: Shoot a projectile.

## Gameplay

- The player starts at a specific position on the screen.
- The enemy moves back and forth within a defined path.
- Shoot the enemy to gain points. Each hit increases your score by 1.
- Avoid colliding with the enemy, as it will decrease your score by 5 and reset your position.

## Code Structure

- **Player Class**: Handles player movement, jumping, and drawing the player on the screen.
- **Enemy Class**: Manages the enemy's movement, health, and drawing.
- **Projectile Class**: Handles the creation, movement, and drawing of projectiles.
- **Main Loop**: Manages game events, updates the game state, and redraws the game window.

## Assets

- **Player Sprites**: Walking and standing animations for the player.
- **Enemy Sprites**: Walking animations for the enemy.
- **Background**: A static background image.
- **Sounds**: Placeholder for bullet and hit sounds (currently commented out).

## Future Improvements

- Add more levels with increasing difficulty.
- Introduce more enemies with different behaviors.
- Implement power-ups and collectibles.
- Add a main menu and game over screen.
- Improve graphics and sound effects.

## Contributing

Feel free to fork this repository and submit pull requests with your improvements. If you find any bugs or have suggestions, please open an issue.

## License

This project is open-source and available under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- Thanks to the Pygame community for their excellent documentation and tutorials.
- Special thanks to [Tech With Tim](https://www.youtube.com/c/TechWithTim) for the inspiration and initial code structure.

Enjoy the game! 🎮
