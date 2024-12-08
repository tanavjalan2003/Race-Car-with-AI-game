# Racing Game Simulator

Welcome to the **Racing Game Simulator**, an engaging arcade-style game designed for fun, challenges, and dynamic gameplay. Navigate through maps, avoid traffic, and race against time while collecting flags to boost your score.
![Screenshot of Rcaecar Game](racecar-game.png)
---

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [How to Play](#how-to-play)
- [Customization Guide](#customization-guide)
- [Acknowledgments](#acknowledgments)
- [Contact](#contact)

---

## Features
- **Dynamic Traffic Simulation**: AI-controlled traffic adds complexity to gameplay.
- **Flag Capture Mechanism**: Collect flags to increase your score and extend the timer.
- **Directional Guidance**: A rotating arrow guides players to the next flag.
- **Collision Mechanics**: Penalties for crashing into other cars or boundaries.
- **Real-Time Camera**: The game screen dynamically follows the player car.
- **Customizable Maps**: Easily modify map layouts and environments.

---

## Technologies Used
- **Python**: Core game logic and structure.
- **Pygame**: Game engine for rendering graphics, handling events, and animations.
- **Image Assets**: Custom sprites and visuals for vehicles, environment, and UI elements.

---

## File Structure
```
project-root/
│
├── __pycache__/                 # Compiled Python bytecode
├── media/                       # Media assets folder
│   ├── car_player.png           # Player car sprite
│   ├── traffic1.png             # Traffic car sprite 1
│   ├── traffic2.png             # Traffic car sprite 2
│   ├── timeout.png              # Timeout alert image
│   ├── direction.png            # Directional arrow
│   ├── finish.png               # Flag sprite
│   ├── tracks.png               # Tire tracks sprite
│   ├── bounds.png               # Out-of-bounds alert image
│   └── (other image files)      # Additional assets
│
├── MAIN.py                      # Entry point of the game
├── camera.py                    # Handles camera positioning and view
├── bounds.py                    # Out-of-bounds detection logic
├── direction.py                 # Directional arrow logic
├── gamemode.py                  # Game mode and score handling
├── loader.py                    # Image loader utility
├── maps.py                      # Map and environment logic
├── menu.py                      # Menu interface handling
├── player.py                    # Player car behavior
├── timeout.py                   # Timeout alert functionality
├── tracks.py                    # Tire tracks mechanics
├── traffic.py                   # AI-controlled traffic logic
└── README.md                    # This file
```

---

## How to Play
1. **Run the Game**  
   Execute the game by running the main script:  
   ```bash
   pip3 install pygame
   python MAIN.py
   ```
2. **Navigate Your Car**  
   Use arrow keys or WASD to steer your car.  
3. **Collect Flags**  
   Follow the directional arrow to reach flags and earn points.  
4. **Avoid Traffic**  
   Dodge AI-controlled traffic cars to maintain your score.  
5. **Manage Time**  
   Keep an eye on the countdown timer and collect flags to extend time.  

---

## Customization Guide
1. **Add New Maps**  
   Modify `maps.py` to create custom map layouts.  
2. **Change Assets**  
   Replace image files in the `media/` folder with your own assets (ensure filenames match).  
3. **Adjust Gameplay Settings**  
   Modify parameters like `COUNTDOWN_FULL` or `LIFETIME` in `gamemode.py` or `tracks.py` for a personalized experience.  
4. **Add New Features**  
   Expand game logic by editing Python files such as `player.py` or `traffic.py`.

---

## Acknowledgments
This project was built using open-source resources, including assets from OpenGameArt. Special thanks to contributors who designed the sprites and maps.
---

## Contact
For queries or suggestions, please reach out via email: **tjalan@asu.edu**  

Enjoy racing and good luck! 🏁
