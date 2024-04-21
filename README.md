### Tic-Tac-Toe Game in Java

This is a simple implementation of the classic Tic-Tac-Toe game in Java. Players take turns marking cells in a 3x3 grid, aiming to get three of their symbols in a row, column, or diagonal.

### How to Play:

1. The game starts with an empty 3x3 grid.
2. Players enter their moves by specifying the row and column numbers where they want to place their symbol ('X' or 'O').
3. The game alternates between 'X' and 'O' until one player gets three of their symbols in a row, column, or diagonal, or the grid is filled without a winner (draw).
4. The game announces the winner or declares a draw.

### Implementation Details:

- The game board is represented by a 2D array of characters.
- The program checks for valid moves, updates the board, and determines the winner or draw condition.
- Players can enter moves via the command line interface.

### How to Run:

1. Compile the Java code using `javac TicTacToe.java`.
2. Run the compiled program using `java TicTacToe`.
3. Follow the prompts to enter your moves.
