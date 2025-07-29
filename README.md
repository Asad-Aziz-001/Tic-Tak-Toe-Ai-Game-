# **🧩Tic Tac Toe 🎮**

**Initialization:**

The game sets up a 600x600 pixel window with a green background. It initializes a 3x3 game board represented by a NumPy array filled with zeros.

Game Board: The board is drawn with two horizontal and two vertical lines, dividing the window into nine equal squares (3 rows x 3 columns).

**Game Mechanics:**

Players take turns clicking on squares to place their marks (Player 1 uses circles, Player 2 uses crosses).

The game tracks which squares are occupied and prevents overwriting.

After each move, it checks if the current player has won by getting three marks in a row (horizontally, vertically, or diagonally).

**Visual Feedback:**

Winning lines are drawn in the respective player's color (white for circles, dark gray for crosses).

Circles and crosses are drawn with specific styles (thickness, size) when players make their moves.

**Game States:**

The game continues until a player wins or the board is full (draw).

Players can restart the game at any time by pressing the 'R' key, which clears the board and resets the game state.

**User Interaction:**

Mouse clicks are used to select squares.

The 'R' key resets the game.

The window can be closed normally to exit the game.
