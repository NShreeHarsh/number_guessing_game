# Number Guessing Game

A simple Python game where the player guesses a randomly chosen number between 1 and 100. The game provides feedback after each guess, helping the player refine their guesses until they win.

---

## Features

- The computer generates a random number between 1 and 100.
- The player guesses the number.
- Feedback is given for each guess:
  - **"Too high!"** if the guess is greater than the target number.
  - **"Too low!"** if the guess is less than the target number.
- The game tracks the number of attempts.
- The player is congratulated upon guessing correctly.

---

## Prerequisites

- Python 3.x installed on your computer.

---

## How to Run the Game

1. Clone or download this repository.
2. Open a terminal or command prompt.
3. Navigate to the folder where the script is located.
4. Run the script using the following command:

   ```bash
   python number_guessing_game.py

## How to Play

- The game will generate a random number between 1 and 100.
- Enter your guesses in the terminal.
- Use the feedback (**"Too high!"** or **"Too low!"**) to guide your next guesses.
- Continue guessing until you find the correct number.
- The game will display the total number of attempts you made.

---

## Concepts Used

- **Random Number Generation**: Using `random.randint()` to generate the target number.
- **User Input**: Taking guesses from the player.
- **Loops and Conditionals**: Handling repeated guesses and providing feedback.
- **Error Handling**: Ensuring valid inputs using `try` and `except`.

---

## Future Enhancements

- Add difficulty levels (easy, medium, hard) with different ranges.
- Record and display the best score (minimum attempts).
- Allow players to play again without restarting the program.
