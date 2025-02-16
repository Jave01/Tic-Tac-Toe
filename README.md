*Introduction*

This is a simple Tic-Tac-Toe game built using HTML, CSS, and JavaScript. The game allows two players to take turns marking spaces in a 3×3 grid. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row wins the game.

*How to Play*

The game starts with Player 1 (⭕).
Players take turns clicking on empty boxes.
⭕ and ❌ will appear alternatively based on the player's turn.
The first player to align three marks in a row (horizontally, vertically, or diagonally) wins the game.
Once a winner is determined, the game will disable further moves.
Click "New Game" or "Reset Game" to restart the game.

*Technologies Used*

HTML: Structure of the game
CSS: Basic styling (contained in index.css)
JavaScript: Game logic (contained in index.js)

*Code Overview*
HTML Structure
The game consists of a 3×3 grid made up of <button> elements.
There are two buttons:
New Game: Starts a fresh game after one ends.
Reset Game: Clears the board and restarts the game.

*JavaScript Logic*
Event Listeners are added to each button to register player moves.
turn0 variable keeps track of the current player (⭕ starts first).
Winning conditions are checked after each move.
Disable & Enable Functions to prevent further moves after a win.

*File Structure*
Tic-Tac-Toe/
│── index.html   # Main game structure
│── index.css    # Styling of the game
│── index.js     # Game logic & functionality
│── README.md    # Documentation

*Features*
✅ Simple and interactive UI
✅ Winning message display
✅ Reset and New Game options
✅ Basic animations using CSS
✅ Fully functional game logic


*Demo*

To play the game, simply open index.html in a web browser.


Enjoy Playing Tic-Tac-Toe!

