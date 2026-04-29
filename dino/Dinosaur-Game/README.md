# 🦖 Dinosaur Game

A Python recreation of the classic Chrome Dinosaur Game using Pygame! Jump and duck to avoid obstacles and see how high you can score.

![Game Preview](https://img.shields.io/badge/Python-3.7+-blue.svg)
![Pygame](https://img.shields.io/badge/Pygame-2.0+-green.svg)

## 🎮 Features

- **Smooth animations** - Running, jumping, and ducking dinosaur sprites
- **Multiple obstacles** - Cacti and flying Pterodactyls to avoid
- **Dynamic difficulty** - Game speed increases as you progress
- **Score tracking** - See how far you can go!
- **Sound effects** - Jump, collision, and milestone sounds
- **Parallax scrolling** - Clouds and ground for immersive gameplay

## 📋 Requirements

- Python 3.7 or higher
- Pygame 2.0 or higher

## 🚀 Installation

1. **Clone or download this repository**

2. **Install Pygame** (if not already installed):
   ```bash
   pip install pygame
   ```

3. **Navigate to the game directory**:
   ```bash
   cd dino/Dinosaur-Game
   ```

4. **Run the game**:
   ```bash
   python main.py
   ```

## 🎯 How to Play

### Controls

- **SPACE** or **UP ARROW** - Jump over obstacles
- **DOWN ARROW** - Duck under flying pterodactyls
- **SPACE** (when game over) - Restart the game

### Gameplay

- Avoid cacti and pterodactyls by jumping or ducking
- The game speed increases as your score goes up
- You earn 1 point every 0.1 seconds
- Special sound plays every 100 points
- Try to beat your high score!

## 📁 Project Structure

```
Dinosaur-Game/
├── main.py                 # Main game file
├── README.md              # This file
└── assets/
    ├── Dino1.png          # Running animation frame 1
    ├── Dino2.png          # Running animation frame 2
    ├── DinoDucking1.png   # Ducking animation frame 1
    ├── DinoDucking2.png   # Ducking animation frame 2
    ├── DinoJumping.png    # Jumping sprite
    ├── Ptero1.png         # Pterodactyl animation frame 1
    ├── Ptero2.png         # Pterodactyl animation frame 2
    ├── cloud.png          # Cloud sprite
    ├── ground.png         # Ground texture
    ├── PressStart2P-Regular.ttf  # Game font
    ├── cacti/
    │   ├── cactus1.png    # Cactus variations
    │   ├── cactus2.png
    │   ├── cactus3.png
    │   ├── cactus4.png
    │   ├── cactus5.png
    │   └── cactus6.png
    └── sfx/
        ├── jump.mp3       # Jump sound effect
        ├── lose.mp3       # Game over sound
        └── 100points.mp3  # Milestone sound
```

## 🎨 Game Mechanics

### Classes

- **Dino** - The player character with running, jumping, and ducking abilities
- **Cactus** - Ground obstacles that must be jumped over
- **Ptero** - Flying obstacles that can be ducked under or jumped over
- **Cloud** - Background decoration for visual appeal

### Difficulty Progression

- Base game speed: 5 pixels/frame
- Speed increases by 0.0025 every frame
- Obstacles spawn randomly with cooldown periods
- Pterodactyls appear at varying heights

## 🐛 Troubleshooting

### Game won't start
- Make sure Python 3.7+ is installed: `python --version`
- Verify Pygame is installed: `pip show pygame`
- Check that you're in the correct directory with `main.py`

### No sound
- Ensure your system audio is working
- Check that all files in `assets/sfx/` are present
- The game will still run without sound if audio files are missing

### Graphics issues
- Verify all image files in `assets/` folder are present
- Make sure you have proper permissions to read the files

## 🎓 Learning Resources

This project demonstrates:
- Pygame sprite system and collision detection
- Game loop implementation
- Animation techniques
- Event handling
- Sound management
- Object-oriented programming in Python

## 📝 License

This is a fan recreation for educational purposes. Original Chrome Dinosaur Game by Google.

## 🤝 Contributing

Feel free to fork this project and add your own features! Some ideas:
- High score persistence
- Different dinosaur skins
- Power-ups
- Day/night cycle
- Mobile controls

## 🎉 Credits

- Original game concept by Google Chrome team
- Assets and sprites inspired by the original Chrome Dino Game
- Built with Python and Pygame

---

**Enjoy the game and happy coding!** 🦖✨
