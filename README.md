# Rocket Shooting Game - C Project

## Description:
This is a simple console-based **Rocket Shooting Game** developed using **C language**. The game features a **player-controlled rocket** that can shoot bullets at **enemy ships**. The game includes various functionalities such as movement, shooting, collision detection, and score management. Players can interact with the game via the keyboard (W, A, S, D for movement, Spacebar to shoot, Q to quit).

## Concepts Covered:
This project implements several core concepts of **C programming** including:

- **Functions**: Defined to modularize the program (e.g., menu navigation, game logic, etc.).
- **Structures**: Used to store the player’s rocket, bullets, and enemies' positions, as well as high scores.
- **Pointers**: Utilized to handle dynamic memory and structure manipulation.
- **Random Number Generation**: For spawning enemies at random positions.
- **File Handling**: Storing and retrieving high scores using file I/O.
- **Control Flow**: Implementation of conditionals, loops, and user inputs for dynamic game behavior.
- **Game Logic**: Collision detection between bullets and enemies, and the game-over condition.

## Features:
- **Player Movement**: The rocket moves left and right using the 'A' and 'D' keys.
- **Bullet Shooting**: Press the spacebar to shoot bullets at enemies.
- **Enemy Movement**: Enemies spawn at random positions and move downwards.
- **High Scores**: The top 5 highest scores are saved and displayed.
- **Game Instructions**: Clear instructions for player actions.
- **Sound Effects**: Background music and in-game sounds (via the `mciSendString` function, using MP3 files).

## How to Play:
- Use the **'A'** or **'D'** keys to move your rocket left or right.
- Press **Spacebar** to shoot bullets at the enemies.
- Enemies move downward, and each time you hit one, your score increases by 10.
- The game ends when an enemy collides with the player’s rocket.
- You can press **'Q'** to quit the game.

## Project Members:
- **Muhammad Arham Usman**
- **Muhammad Ibrahim**
- **Muhammad Hasnain**
- **Muhammad Obaid Ullah**

## Credits:
- **Game Logic Design**: Muhammad Arham Usman, Muhammad Ibrahim
- **Menu and Sound**: Muhammad Obaid Ullah
- **Filing and Score Management**: Muhammad Hasnain
