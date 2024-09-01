2048 Game in Pygame


This project is an implementation of the classic 2048 puzzle game using Pygame. The objective of the game is to slide numbered tiles on a grid to combine them to create a tile with the number 2048.

Features
Grid Layout: The game is played on a 4x4 grid.
Tile Movement: Tiles can be moved up, down, left, or right using the arrow keys.
Tile Merging: When two tiles with the same number touch, they merge into one with their combined value.
Random Tile Generation: After each move, a new tile (2 or 4) appears in an empty spot on the grid.
End Condition: The game continues until there are no possible moves left or the player creates a tile with the number 2048.
Installation
To run this project, ensure you have Python installed along with the Pygame library. If you don't have Pygame installed, you can install it using pip:

bash

pip install pygame
How to Run
Clone this repository or download the script.

Navigate to the directory containing the script.

Run the script using Python:

bash

python 2048.py
Gameplay Instructions
Use the arrow keys to move the tiles in the corresponding direction:
Left Arrow: Move all tiles left.
Right Arrow: Move all tiles right.
Up Arrow: Move all tiles up.
Down Arrow: Move all tiles down.
When two tiles with the same value collide, they merge into a tile with the combined value.
The game ends when there are no valid moves left.
Code Overview
Tile class: Handles the creation, movement, and merging of the tiles. It also manages the color and position of each tile.
Grid and Tile Rendering: The grid and tiles are drawn on the screen, with grid lines separating the tiles.
Game Logic: Handles tile movements in four directions, merging tiles, and generating new tiles after each move.
Main Loop: Manages the game loop, handling events like key presses and updating the display.
Customization
Grid Size: Modify ROWS and COLS to change the grid size.
Tile Movement Speed: Adjust MOVE_VEL to change how fast tiles move.
Colors: Customize tile colors by editing the COLORS list in the Tile class.
Dependencies
Python 3.x
Pygame
License
This project is licensed under the MIT License. Feel free to modify and distribute it as you wish.

Enjoy playing 2048!
