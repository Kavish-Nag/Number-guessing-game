

```md
# Number Guessing Game

This is a simple Python-based command-line Number Guessing Game. The computer randomly selects a number between 1 and 100, and the player has to guess the correct number. After each guess, the player is given a hint if the guess is too high or too low, and the game continues until the correct number is guessed.

## Features

- **Random Number Generation**: The computer picks a random number between 1 and 100.
- **User Input**: The player guesses the number.
- **Hints**: The game provides feedback whether the guess is too high or too low.
- **Win Condition**: The game ends when the player correctly guesses the number.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/number-guessing-game.git
    ```

2. Navigate to the project directory:
    ```bash
    cd number-guessing-game
    ```

## How to Run

1. Run the script:
    ```bash
    python number_guessing_game.py
    ```

2. The game will prompt you with:
    ```
    Welcome to the Number Guessing Game!
    I have selected a number between 1 and 100. Can you guess what it is?
    ```

3. Enter your guess and get feedback on whether it's too high or too low. Continue guessing until you find the correct number.

4. Once you guess correctly, the game will congratulate you:
    ```
    Congratulations! You guessed the number.
    ```

## Example

```
Enter your guess: 45
Too low! Try again.
Enter your guess: 75
Too high! Try again.
Enter your guess: 60
Congratulations! You guessed the number.
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
