# Gravity Game

This project implements a gravity-based game in Java. Players navigate through a grid, collect items, and avoid robots. The game keeps track of player scores and allows teleportation.

## Project Overview

The project consists of several Java classes:
- `Main.java`: The main class that runs the game.
- `Game.java`: The class that manages the game logic, including initializing the game, handling input, and updating the game state.
- `Player.java`: A class that represents the player, including movement and interaction with the game environment.
- `Robots.java`: A class that represents the robots in the game, including their movement logic.
- `CircularQueue.java`: A class that implements a circular queue to handle game inputs.
- `Stack.java`: A class that implements a stack to manage the player's backpack.

### Features

The game includes:
1. Generating a grid with random items and obstacles.
2. Placing and navigating a player character.
3. Spawning and moving robots.
4. Collecting items to increase score and energy.
5. Teleporting to random locations on the grid.
6. Displaying game stats such as time, score, and teleport count.

## Requirements

The project requires Java Development Kit (JDK) to compile and run the Java files. Additionally, the Enigma Console library is used for console output.

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/barissolcay/Gravity-Game.git
    cd Gravity-Game
    ```

2. Ensure you have the Enigma Console library in your classpath.

3. Compile the Java files:

    ```bash
    javac src/*.java
    ```

4. Run the game:

    ```bash
    java src/Main
    ```

## Game Flow

1. The game initializes a grid with random items and obstacles.
2. The player character is placed at a random position on the grid.
3. The player navigates through the grid using arrow keys, collecting items and avoiding robots.
4. The player can teleport using the spacebar.
5. The game ends when the player collides with a robot or runs out of energy.

## Contributing

Feel free to open issues or submit pull requests if you have suggestions for improvements or find any bugs.

## License

MIT License

```markdown
MIT License

Copyright (c) 2025 Baris Solcay

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
