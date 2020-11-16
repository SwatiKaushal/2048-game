# 2048-game

About:
2048 is a single-player sliding block puzzle game designed by Italian web developer Gabriele Cirulli. The objective of the game is to slide numbered tiles on a grid to combine them to create a tile with the number 2048; however, one can continue to play the game after reaching the goal, creating tiles with larger numbers

Requirement:

 Create a replica of the game 2048: 
•	Create a simple 4x4 grid that is randomly populated with two tiles 
•	Move the tiles when user presses arrow keys 
•	Generate new tiles for every turn 
•	Merge two colliding tiles into one 
•	Apply the same colour to tiles of same value 
•	Display a message when the game is ‘won’ or when no more moves can be made
•	Add transitions when tiles are moved and merged 
•	Add touch/mobile support – swipe to move the tiles 
•	Add your own flavour and features as time permits 

Solution:
The solution has three files: 
1)	Game2048.js – JavaScript file containing all the logic code.
2)	Main.html – html file containing all the html code.
3)	StyleSheet.cs – all the CSS code.

Rules to play the game online:

2048 is often played on a 4×4 grid, with numbered tiles that slide when a player moves them using the four arrow keys. Every turn, a new tile will randomly appear in an empty spot on the board with a value of either 2 or 4. Tiles slide as far as possible in the chosen direction until they are stopped by either another tile or the edge of the grid. If two tiles of the same number collide while moving, they will merge into a tile with the total value of the two tiles that collided. The resulting tile cannot merge with another tile again in the same move. Higher-scoring tiles emit a soft glow.
If a move causes three consecutive tiles of the same value to slide together, only the two tiles farthest along the direction of motion will combine. If all four spaces in a row or column are filled with tiles of the same value, a move parallel to that row/column will combine the first two and last two. 
A scoreboard on the upper-right keeps track of the user's score. The user's score starts at zero, and is increased whenever two tiles combine, by the value of the new tile. As with many arcade games, the user's best score is shown alongside the current score.
The game is won when a tile with a value of 2048 appears on the board, hence the name of the game. After reaching the 2048 tile, players can continue to play (beyond the 2048 tile) to reach higher scores. When the player has no legal moves (there are no empty spaces and no adjacent tiles with the same value), the game ends.

Strategy:
In general, most players will keep the tile with the highest value in the corner. They then add tiles sliding into the biggest tile to make higher tiles.
