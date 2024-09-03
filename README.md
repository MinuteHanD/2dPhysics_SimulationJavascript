# 2D physics Simulator

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Game Modes](#game-modes)
- [Controls](#controls)
- [Technical Details](#technical-details)
- [Code Structure](#code-structure)
- [Customization](#customization)


## Introduction

This is an interactive web-based game where players navigate multiple balls through a complex maze using a virtual joystick. The game combines elements of skill, strategy, and physics to create an engaging and challenging experience.

## Features

- Interactive maze with multiple balls
- Physics-based ball movement
- Virtual joystick control
- Collision detection with walls
- Two game modes: Easy and Hard
- Responsive design
- Customizable appearance


## Installation

To run the Maze Game locally, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/your-username/maze-game.git
   ```

2. Navigate to the project directory:
   ```
   cd maze-game
   ```

3. Open the `index.html` file in a modern web browser.

No additional dependencies or build steps are required.

## How to Play

1. Click on the joystick to start the game.
2. Use the mouse to tilt the maze by moving the joystick.
3. Guide all the balls to the center of the maze.
4. Avoid black holes in hard mode.
5. Complete the game as quickly as possible!

## Game Modes

1. **Easy Mode**: Navigate all balls to the center without any obstacles.
2. **Hard Mode**: Navigate all balls to the center while avoiding black holes.

## Controls

- **Mouse**: Click and drag the joystick to tilt the maze.
- **Space**: Reset the game.
- **H**: Switch to Hard mode.
- **E**: Switch to Easy mode.

## Technical Details

The Maze Game is built using the following technologies:

- HTML5
- CSS3
- JavaScript (ES6+)

Key technical features include:

- Canvas-free rendering using DOM elements
- Physics simulation for ball movement
- Efficient collision detection algorithms
- Responsive design for various screen sizes

## Code Structure

The project consists of three main files:

1. `index.html`: Contains the game's HTML structure.
2. `styles.css`: Defines the game's appearance and layout.
3. `script.js`: Implements the game logic and physics.

Key components in the JavaScript code:

- `resetGame()`: Initializes and resets the game state.
- `main()`: The main game loop, handling physics and collision detection.
- `rollAroundCap()`: Simulates ball collision with wall corners.
- Event listeners for user input and game control.

## Customization

You can easily customize the game's appearance by modifying the CSS variables in the `styles.css` file:

```css
body {
  --background-color: #ede6e3;
  --wall-color: #36382e;
  --joystick-color: #210124;
  --joystick-head-color: #f06449;
  --ball-color: #f06449;
  --end-color: #7d82b8;
  --text-color: #210124;
}
```

To modify the maze layout, edit the `walls` array in the `script.js` file.

