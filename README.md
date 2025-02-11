# 🎮 Gravity Game

A Java-based console game where players navigate through a dynamic environment while collecting items, avoiding robots, and managing resources.

## 📝 Description

Gravity Game is an interactive console-based game that combines elements of puzzle, strategy, and action gameplay. Players must navigate through a world affected by gravity, manage their inventory, avoid hostile robots, and collect valuable items while dealing with falling boulders and other obstacles.

## 🌟 Features

- **Dynamic Environment**
  - Gravity-affected boulders
  - Destructible terrain
  - Interactive objects
  - Real-time map updates

- **Player Mechanics**
  - Movement in four directions
  - Teleportation ability
  - Item collection system
  - Backpack management

- **Game Elements**
  - 🤖 Hostile robots with AI movement
  - 🪨 Rolling boulders
  - 🎒 Collectable items (1,2,3)
  - 🌍 Terrain modification

- **Scoring System**
  - Points for collecting items
  - Bonus points for robot elimination
  - High score tracking
  - Time-based challenges

## 🎯 Gameplay

### Controls
- ⬅️ Left Arrow: Move left
- ➡️ Right Arrow: Move right
- ⬆️ Up Arrow: Move up
- ⬇️ Down Arrow: Move down
- Space: Teleport
- Enter: Start game

### Game Objects
- `P`: Player
- `X`: Robot
- `O`: Boulder
- `#`: Wall
- `:`: Earth
- `1,2,3`: Collectible items

## 🔧 Technical Implementation

### Core Components
1. **Game Engine** (`Game.java`)
   - Main game loop
   - Map generation
   - Game state management

2. **Player System** (`Player.java`)
   - Movement controls
   - Inventory management
   - Collision detection

3. **Robot AI** (`Robots.java`)
   - Pathfinding
   - Movement patterns
   - Player interaction

4. **Data Structures**
   - `Stack.java`: Inventory management
   - `CircularQueue.java`: Input queue
   - `Status.java`: Game status tracking

## 🚀 Getting Started

### Prerequisites
- Java JDK 8 or higher
- Enigma Console Library
- IDE (Eclipse/IntelliJ IDEA recommended)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/barissolcay/Gravity-Game.git
