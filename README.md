# legendary-othello
a strategy board game for two players, played on an 8×8 uncheckered board. 
It was invented in 1883. Othello, a variant with a fixed initial setup of the board, 
was patented in 1971. 
Here's An implementation of very old and Legendary Othello Which Helps You learn About Java OOPS related Approach.
You will first need to reverse-engineer the code provided. The code so far is used to:

Display the 8×8 grid using HTML and CSS.
Add a disc on the grid when the user clicks on a cell of the grid using the selectCell()
function in JavaScript.
Refresh the grid on the screen using the refreshGrid() function in JavaScript.
The code provided uses a variable called grid, use to store a two-dimensional array (8×8) of integer values. Within this array, a 0 represents an empty place, a 1 represents a white disc and a 2 represents a black disc.

Your task consists of:
Amend the selectCell() function in JavaScript in order to:
Check if user is allowed to place a disc on the selected cell.
Reverse any discs of the opponent’s color that are in a straight line and bounded by the disc just placed and another disk of the current player’s color.
Count the number of white and black discs and display the score on the page.
Check if the grid is full.
Add code to the resetGrid() JavaScript function to start a new game with an empty grid.
