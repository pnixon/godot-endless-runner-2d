# 🎮 Godot 4 Endless Runner 2D

**Classic side-scrolling endless runner with combat system, dynamic spawning, and chiptune soundtrack**

![Godot 4](https://img.shields.io/badge/Godot-4.x-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Platform](https://img.shields.io/badge/Platform-Cross--Platform-orange.svg)

## 🚀 Features

### 🎯 **Dual-Mode Gameplay**
- **Runner Mode** - Classic endless running with obstacles and pickups
- **Combat Mode** - Turn-based tactical combat on a grid system
- **Seamless transitions** - Switch between modes dynamically
- **Progressive difficulty** - Challenges increase over time

### 🎵 **Dynamic Audio System**
- **Random music selection** - Different chiptune track each playthrough
- **4 chiptune tracks** included for variety
- **Runtime track switching** - Press N to change music anytime
- **Seamless looping** - Continuous background music

### ⚔️ **Combat System**
- **Grid-based tactics** - 4x4 tactical combat grid
- **Turn-based strategy** - Plan your moves carefully
- **Enemy encounters** - Face various enemy types
- **Tactical positioning** - Use the grid to your advantage

### 🎮 **Classic Controls**
- **Arrow Keys/WASD** - Movement in both modes
- **Space** - Jump in runner mode, confirm in combat
- **M** - Toggle music, **+/-** - Volume, **N** - Next track

## 🎯 **Gameplay Modes**

### 🏃 **Runner Mode**
Classic endless runner mechanics:
- **Obstacle avoidance** - Jump over hazards
- **Pickup collection** - Coins, XP, and power-ups
- **Dynamic spawning** - Obstacles and enemies appear over time
- **Score progression** - Build up points and distance

### ⚔️ **Combat Mode**
Turn-based tactical combat:
- **4x4 grid battlefield** - Strategic positioning matters
- **Enemy encounters** - Face different enemy types
- **Tactical movement** - Plan your position and attacks
- **Combat resolution** - Win to continue running

## 🛠️ **Technical Details**

### Built With
- **Godot 4.x** - Modern game engine
- **GDScript** - Native scripting language
- **2D Physics** - CharacterBody2D with custom movement
- **Dynamic Audio** - MP3 streaming with random selection

### Architecture
- **Mode-based design** - Clean separation between runner and combat
- **Event-driven** - Signal-based communication
- **Modular systems** - Audio, input, and gameplay isolated
- **Scalable difficulty** - Dynamic enemy and obstacle spawning

### Game Systems
- **Biome progression** - Different areas with unique challenges
- **Enemy spawn system** - Distance and time-based encounters
- **Pickup system** - Coins, XP, and health items
- **UI management** - Score, health, and game state display

## 🎮 **Controls**

### Runner Mode
- **Arrow Keys/WASD** - Move left/right
- **Space** - Jump over obstacles
- **Automatic forward** - Character runs automatically

### Combat Mode
- **Arrow Keys/WASD** - Move on combat grid
- **Space** - Confirm action/attack
- **Strategic positioning** - Use grid tactically

### Audio Controls
- **M** - Toggle music on/off
- **+/-** - Volume up/down
- **N** - Next random track

### Game Controls
- **Arrow Keys** - Restart when game over

## 🎵 **Soundtrack**

Includes 4 high-energy chiptune tracks:
- **"chiptunes awesomeness.mp3"** - Energetic action theme
- **"chiptunes awesomeness 2.mp3"** - Alternative action track
- **"the brass and the blade (Remix) chiptunes.mp3"** - Epic remix
- **"background_music.mp3"** - Original theme

## 🚀 **Getting Started**

### Prerequisites
- **Godot 4.x** - Download from [godotengine.org](https://godotengine.org/)

### Installation
1. **Clone the repository**
   ```bash
   git clone https://github.com/pnixon/godot-endless-runner-2d.git
   cd godot-endless-runner-2d
   ```

2. **Open in Godot**
   - Launch Godot 4
   - Click "Import"
   - Navigate to project folder
   - Select `project.godot`

3. **Play**
   - Press F5 or click Play
   - Select `Main.tscn` as main scene

## 🎯 **Game Features**

### Progression System
- **Score tracking** - Points for distance and pickups
- **XP system** - Gain experience from combat and pickups
- **Coin collection** - Currency for future upgrades
- **Health management** - Take damage, find health items

### Dynamic Difficulty
- **Biome system** - 5 different biomes with unique challenges
- **Spawn rate scaling** - More obstacles over time
- **Enemy encounters** - Combat frequency increases
- **Hazard variety** - Different obstacle types per biome

### Visual Feedback
- **UI elements** - Score, coins, XP, health display
- **Mode indicators** - Clear visual distinction between modes
- **Combat grid** - Visual grid overlay for tactical mode
- **Smooth transitions** - Animated mode switching

## 🔧 **Development**

### Project Structure
```
endless_runner/
├── Main.tscn                # Main game scene
├── Player.gd                # Player controller
├── GameManager.gd           # Game logic and mode management
├── CombatGrid.gd            # Combat system
├── *.mp3                    # Chiptune soundtrack
└── README.md                # This file
```

### Key Systems
- **Player.gd** - Movement and abilities for both modes
- **GameManager.gd** - Mode switching, spawning, scoring
- **CombatGrid.gd** - Turn-based combat mechanics
- **Biome system** - Different areas with unique spawning patterns

### Game Modes
- **GameMode.RUNNER** - Endless running with obstacles
- **GameMode.COMBAT** - Turn-based tactical combat
- **Seamless switching** - Smooth transitions between modes

## 🎮 **Gameplay Tips**

### Runner Mode Strategy
- **Timing jumps** - Learn obstacle patterns
- **Collect everything** - Coins and XP are valuable
- **Watch for enemies** - Combat encounters appear over time
- **Use audio cues** - Music rhythm helps with timing

### Combat Mode Tactics
- **Positioning matters** - Use the grid strategically
- **Plan ahead** - Think several moves in advance
- **Control space** - Limit enemy movement options
- **Quick decisions** - Don't overthink simple encounters

### General Tips
- **Learn biomes** - Each area has different challenges
- **Manage health** - Don't ignore health pickups
- **Audio control** - Use N key to find your favorite track
- **Practice transitions** - Get comfortable switching between modes

## 🤝 **Contributing**

Contributions welcome! Areas for improvement:
- **More enemy types** - Variety in combat encounters
- **Power-up system** - Temporary abilities and boosts
- **Upgrade shop** - Spend coins on improvements
- **More biomes** - Additional themed areas
- **Visual effects** - Particles and screen effects
- **More music** - Additional chiptune tracks

## 📝 **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🎵 **Credits**

- **Game Engine**: Godot 4.x
- **Music**: Chiptune tracks (various artists)
- **Development**: Built with ❤️ for classic arcade gaming

---

**Ready for dual-mode action? Experience classic endless running with tactical combat!** 🎮⚔️
