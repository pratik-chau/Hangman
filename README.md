# Hangman Game in C

Welcome to the **Hangman Game** implemented in C! This is a classic word-guessing game where you have to guess the hidden word before running out of attempts. The game is simple, fun, and a great way to test your vocabulary skills. 

This project is written in C and demonstrates basic programming concepts like arrays, loops, functions, and string manipulation. It also includes a visual representation of the hangman as you make incorrect guesses.

---

## How to Play

1. **Objective**: Guess the hidden word before you run out of attempts.
2. **Rules**:
   - You have **6 attempts** to guess the word correctly.
   - Each incorrect guess brings you closer to losing the game.
   - A hint is provided to help you guess the word.
3. **Gameplay**:
   - The game will display blanks (`_`) representing the letters of the word.
   - Enter a letter to guess. If the letter is in the word, it will be revealed.
   - If the letter is not in the word, you lose an attempt, and the hangman is drawn.

---

## Features

- **Random Word Selection**: The game randomly selects a word from a predefined list.
- **Hints**: Each word comes with a hint to help you guess.
- **Visual Hangman**: The game displays the hangman as you make incorrect guesses.
- **User-Friendly**: Simple and intuitive interface for players.

---

## Installation and Setup

To run this Hangman game on your local machine, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/hangman-game-c.git](https://github.com/pratik-chau/Hangman.git
   cd hangman-c
   ```

2. **Compile the Program**:
   Use a C compiler like `gcc` to compile the code:
   ```bash
   gcc hangman.c -o hangman
   ```

3. **Run the Game**:
   Execute the compiled program:
   ```bash
   ./hangman
   ```

---

## Code Structure

The code is organized into the following components:

- **Main Function**:
  - Handles the game loop, user input, and word selection.
  - Tracks the number of attempts and checks for win/loss conditions.

- **Helper Functions**:
  - `displayWord`: Displays the current state of the word with guessed letters revealed.
  - `drawHangman`: Draws the hangman based on the number of incorrect guesses.

- **Word List**:
  - A list of words and their corresponding hints is stored in a struct array.

---
## Contributing

Contributions are welcome! If you'd like to improve this project, feel free to:

1. Add more words and hints to the word list.
2. Enhance the user interface or add new features.
3. Optimize the code for better performance.

To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch for your changes.
3. Submit a pull request with a detailed description of your changes.

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- Inspired by the classic Hangman game.
- Thanks to the C programming community for resources and inspiration.

---

Enjoy the game, and happy guessing! 🎮
