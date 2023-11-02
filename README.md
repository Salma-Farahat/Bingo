# Bash Bingo Game

This is a simple command-line Bingo game implemented in Bash. The game reads input from a file that specifies a Bingo card and provides a Bingo caller interface for players to mark their cards as numbers are called. The game checks the player's card for winning patterns and declares a winner when one is found.

## Usage

To play the game, follow these steps:

1. Ensure you have a valid input file with a Bingo card format. The input file must meet the following requirements:
   - The input file must be provided as a command-line argument.
   - The input file should have 6 lines.
   - The first line of the input file should be a seed value for random number generation (to play with another person, you have to provide the same seed value).
   - The remaining lines should represent a 5x5 Bingo card with numbers within specific ranges for each column (L, I, N, U, X).
   
2. Run the game using the provided Bash script and specify the input file as a command-line argument.

3. The game will display a Bingo caller interface, allowing you to interact with the game. You can press any key to get a Bingo call or 'q' to quit the game.

4. The game will announce the drawn numbers and mark them on your Bingo card. It checks for winning patterns (horizontal, vertical, and diagonal) and declares a winner when found.

## Error Handling

The game includes error handling to validate the input file's format and ensures that it follows the Bingo card format rules. If any issues are detected, the game will display an error message and exit gracefully.


