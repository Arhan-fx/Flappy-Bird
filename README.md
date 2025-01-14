### Flappy Bird 

This project is a Python implementation of the classic Flappy Bird game using the Pygame library. Fly through the pipes and aim for the highest score!

---

### Features

- **Realistic Physics:** Smooth bird movements and gravity simulation.
- **Dynamic Gameplay:** Randomly generated pipes and varying gaps.
- **Interactive UI:** Start and game-over screens.
- **Sound Effects:** Flap, scoring, and game-over sounds included.
- **Score Tracking:** Keeps track of your current score.

---

### Installation

1. Clone or download this repository.
2. Install [Python](https://www.python.org/downloads/) (version 3.7+ is recommended).
3. Install Pygame using pip:
   ```bash
   pip install pygame
   ```
4. Ensure the following asset files are in the `assets/` directory:
   - `bird_down.png`, `bird_mid.png`, `bird_up.png`
   - `background.png`
   - `ground.png`
   - `pipe_top.png`, `pipe_bottom.png`
   - `game_over.png`, `start.png`
   - `flap.mp3`, `score.mp3`, `game_over.mp3`

---

### How to Play

1. Run the game:
   ```bash
   python flappy_bird.py
   ```
2. On the start screen, press **SPACE** to begin.
3. Press **SPACE** to make the bird flap its wings.
4. Avoid hitting the pipes and the ground.
5. Press **R** after a collision to restart.

---

### Controls

- **SPACE:** Flap wings.
- **R:** Restart after game over.
- **ESC:** Quit the game.

---

### Game Assets

All game assets are located in the `assets/` folder. Ensure the file paths and names are correct for the game to function properly.

---

### To-Do List

- Add a high-score tracking feature.
- Create additional game difficulty levels.
- Add a pause menu for gameplay control.

---

### **License**

This project is for educational and personal use only. Ensure compliance with the asset usage rights if redistributed.
