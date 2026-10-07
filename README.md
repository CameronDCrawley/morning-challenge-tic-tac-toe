**Tic-Tac-Toe JS**

A Tic-Tac-Toe game built with vanilla JavaScript.

**About The Project**
I built this project to sharpen my core JavaScript fundamentals—focusing on DOM manipulation, array iteration, object-oriented concepts, and event listeners.

**Key Features**
Interactive Grid: Clickable cells that handle turn-taking and prevent overwriting existing moves.

Win & Draw Detection: Evaluates horizontal, vertical, and diagonal winning conditions, as well as draw scenarios using array methods like .every().

State Management: Easily resets the board and resets the starting player back to default.

Class Structure: Features a basic Player class to encapsulate player identities (Cam vs. the Hater).

**Tech Stack**
- HTML5

- CSS3

- JavaScript 

**How It Works**
Player Assignment: Player 1 starts as 'X'.

Move Validation: The script checks if a cell is empty (element.innerText != "") before rendering a move.

Turn Swapping: Uses a ternary operator (playerOne = playerOne == 'X' ? 'O' : 'X') to switch active shapes smoothly after every valid click.

Game Checks: Runs iWon() and checkForDraw() after each turn to evaluate the state of the board.


<img width="1317" height="1511" alt="image" src="https://github.com/user-attachments/assets/6a63efcf-3883-40d3-b9c1-c93408ee32f6" />
