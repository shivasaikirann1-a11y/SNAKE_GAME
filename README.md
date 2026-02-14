# SNAKE_GAME
Snake Game using Python Turtle

Project Overview
This project is a classic Snake Game developed using Python’s Turtle graphics module. The snake moves in four directions (up, down, left, right) to eat food. Each time the snake eats food, the score increases and the snake grows longer. The game ends when the snake collides with the wall or with its own body.

Project Structure

snake_game/
│
├── main.py
├── snake.py
├── food.py
└── scoreboard.py

File Description

main.py
This is the main controller file. It creates the screen, initializes all game objects, handles the game loop, detects collisions, and controls speed progression.

snake.py
This file contains the Snake class. It manages snake creation, movement, direction control, and body extension when food is eaten.

food.py
This file defines the Food class. It creates the food object and randomly refreshes its position whenever the snake eats it.

scoreboard.py
This file manages score display and shows the game over message when the game ends.

Features

Snake movement in four directions using arrow keys
Food spawning at random positions
Score increases when food is eaten
Snake body grows after eating food
Game over on wall collision
Game over on self collision
Speed increases as score increases

Controls

Up Arrow    – Move Up
Down Arrow  – Move Down
Left Arrow  – Move Left
Right Arrow – Move Right

Requirements

Python 3.x
Turtle module (comes preinstalled with Python standard library)

How to Run

1. Place all four files in the same folder.

2. Open terminal or command prompt in that folder.

3. Run the command:

   python main.py

4. The game window will open and you can start playing.

Game Logic Summary

The snake continuously moves forward. Direction changes are controlled by keyboard input. When the snake touches food, the food relocates, the snake grows, and the score increases. Collision with walls or the snake’s own body ends the game.

Result

The Snake Game was successfully created using Python Turtle graphics with modular file structure, real-time movement, collision detection, score tracking, and increasing difficulty through speed progression.
