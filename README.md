# Rock-Paper-Scissors Game [Live Link](https://jampana-jagadeesh.github.io/rock_paper_scissors/)

## Overview
This is a simple Rock-Paper-Scissors game implemented using HTML, CSS, and JavaScript. The user plays against the computer by selecting their choice, and the winner is determined based on the standard rules of the game. The game tracks the scores of both the user and the computer.

## Features
- Interactive gameplay with real-time results.
- Dynamic score tracking for both the user and the computer.
- Randomized computer choices.
- User-friendly messages for win, loss, or draw outcomes.

## Technologies Used
- **HTML**: For structuring the web page.
- **CSS**: For styling the user interface.
- **JavaScript**: For game logic and interactivity.

## How to Play
1. Clone or download this repository to your local machine.
2. Open the `index.html` file in your favorite web browser.
3. Click on one of the three choices: **Rock**, **Paper**, or **Scissors**.
4. The computer will make a random choice, and the result will be displayed on the screen.
5. Check your score and try to beat the computer!

## Game Rules
- **Rock beats Scissors.**
- **Scissors beat Paper.**
- **Paper beats Rock.**
- If both the user and the computer make the same choice, the game is a draw.

## Code Structure
- **`genCompChoice()`**: Generates a random choice for the computer.
- **`drawGame()`**: Handles the logic and message for a draw game.
- **`showWinner()`**: Updates the score and displays a win or loss message based on the outcome.
- **`playGame(userChoice)`**: Main game logic, comparing user and computer choices to determine the result.
- Event listeners are added to handle user clicks on the available choices.

## Customization
- You can modify the messages displayed to the user by editing the `msg.innerText` lines in the `drawGame()` and `showWinner()` functions.
- Change the styles in the CSS file to personalize the appearance of the game.

## Contribution
Feel free to fork the repository, make changes, and submit a pull request. Contributions are always welcome!

## License
This project is open-source and available under the [MIT License](LICENSE).

