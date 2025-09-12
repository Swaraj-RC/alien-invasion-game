# 👾 Alien Invasion Game

A classic **Space Invaders–style game** built in **Python** using **Pygame**.  
This project is inspired by the book *Python Crash Course* by *Eric Matthes* and extended with custom tweaks.

---

## 🎮 Features
- 🚀 Player-controlled ship with smooth movement  
- 🔫 Bullets and collision detection  
- 👾 Alien fleet that moves and drops down  
- 🖥️ Score tracking and game states (active / game over)  

---

## 🛠️ Requirements
- Python 3.8+  
- [Pygame](https://www.pygame.org/)  

## How to Run the Game
```bash
pip install pygame
python alien_invasion.py

## 📁 Project Structure
alien-invasion-game/
│
├── alien_invasion.py   # main game loop
├── settings.py         # game settings
├── ship.py             # player ship class
├── bullet.py           # bullet class
├── alien.py            # alien class
├── game_stats.py       # game stats tracking
├── scoreboard.py       # scoring UI
├── button.py           # start/play button
├── images/             # game sprites (ship.bmp, alien.bmp, etc.)
└── README.md           
