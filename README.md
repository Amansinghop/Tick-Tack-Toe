# Tic Tac Toe Android App

A classic Tic Tac Toe game built for Android using Java. Features simple gameplay, win detection, and automatic board reset after each game.

 
## Features
- 3x3 grid gameplay
- Player turns (X and O)
- Win detection for all possible combinations
- Draw detection
- Automatic board reset after 3 seconds when game ends
- Simple and intuitive UI

## Technical Implementation
- **Language**: Java
- **Minimum SDK**: API 21 (Android 5.0)
- **Architecture**: Single Activity
- **Key Components**:
  - `GridLayout` for the game board
  - `Button` views for each cell
  - `Timer` for delayed reset functionality

## Code Structure
```plaintext
MainActivity.java - Contains all game logic
activity_main.xml - Layout with 3x3 button grid
