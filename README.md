
# Snake Game

A simple, classic Snake game implemented in Python using the Pygame library.

## Features
- Move the snake in four directions (up, down, left, right) using arrow keys.
- Eat the red food block to increase the snake's length and score.
- The game ends if the snake hits the screen boundaries or collides with itself.
- Display the player's score in real-time.
- Restart the game by pressing `P` after losing.

---

## Requirements
- Python 3.x
- Pygame library

### Installing Pygame
You can install Pygame using pip:
```bash
pip install pygame
```

---

## How to Run the Game
1. Save the game script (`snake.py`) to your local system.
2. Open a terminal or command prompt in the directory where the script is saved.
3. Run the script using Python:
   ```bash
   python snake.py
   ```

---

## Controls
- **Arrow Keys**: Control the snake's movement
  - **Left Arrow**: Move left
  - **Right Arrow**: Move right
  - **Up Arrow**: Move up
  - **Down Arrow**: Move down
- **P**: Restart the game after losing
- **Q**: Quit the game

---

## Scoring
- Every time the snake eats a food block, the score increases by 1.
- The current score is displayed at the top-left corner of the screen.

---

## Customization
You can customize the game by modifying the following variables in the code:
- **Screen dimensions**: `dis_width` and `dis_height`
- **Snake speed**: `snake_speed`
- **Snake block size**: `snake_block`

---

## Example Gameplay
When you start the game:
- The snake starts in the center of the screen.
- Move the snake to eat the food (red block).
- Avoid colliding with the screen boundaries or the snake's own body.

---

## Dependencies
Ensure you have the following dependency installed:
- [Pygame](https://www.pygame.org/)

---

## License
This project is for educational purposes. Feel free to modify and use it as you like.

---

Enjoy the game! 🐍🎮
