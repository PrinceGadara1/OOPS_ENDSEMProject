# 🟡 Pac-Man Clone (C++ & OpenGL)

A simple but fun Pac-Man style game built using **C++** and **OpenGL**, created as part of our CSE 2050 semester project. This game features a classic grid-based maze, collectible pellets, player-controlled Pac-Man, and randomly-moving monsters.

---

## 🎮 Features

- Classic Pac-Man style movement
- Random monster AI movement logic
- Pellet collection mechanics
- Basic collision detection
- Grid-based level layout
- Simple graphics using OpenGL

---

## 🧠 How It Works

- **Player**: Controlled using arrow keys (or WASD), moves smoothly on a 2D grid.
- **Monsters**: Use a basic AI that chooses a random valid direction every few frames (as shown in `updateMonster()` function).
- **Maze**: Hardcoded or loaded from a map file. `isValid(x, y)` checks if a tile is walkable.
- **Pellets**: When collected, increase score.

---

## 🛠️ Dependencies

Make sure you have the following installed:

- C++ compiler (e.g., g++)
- OpenGL
- GLUT or FreeGLUT

To install on Ubuntu-based systems:
```bash
sudo apt-get install freeglut3-dev
