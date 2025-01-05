#Project Overview:
The Tic Tac Toe game is a simple, interactive, and engaging two-player game built using HTML, CSS, and JavaScript. It replicates the classic paper-and-pencil game, where players take turns marking spaces in a 3×3 grid. The objective is to align three of their symbols (either 'X' or 'O') horizontally, vertically, or diagonally to win. If all spaces are filled without a winner, the game ends in a draw.

#Key Features:
Interactive Gameplay:

Players click on the grid cells to make their move.
Alternating turns between 'X' and 'O'.
Win Detection:

The game checks for winning combinations after every move.
Alerts the winner or declares a draw if all spaces are filled.
Responsive Design:

The game is styled to fit various screen sizes using CSS.
Reset Mechanism:

The board resets automatically after a win or draw.
Technologies Used:
HTML:

Structures the game interface with buttons for the grid cells.
Includes semantic elements like <main> and <div> for organization.
CSS:

Styles the game board, buttons, and layout for a clean and appealing design.
Adds hover effects for an enhanced user experience.
JavaScript:

Implements game logic:
Alternates turns between players.
Detects winning combinations or draws.
Resets the game board.
Adds event listeners for user interaction.
How It Works:
The game starts with Player X making the first move.
Players take turns clicking on empty cells to place their symbol (X or O).
After each move, the game checks for:
Three matching symbols in a row (horizontal, vertical, or diagonal).
A full board with no winner (draw).
If a player wins or the game ends in a draw, an alert displays the result, and the game resets.
