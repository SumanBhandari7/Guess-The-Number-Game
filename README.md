# Number Guessing Game

## Project Overview
This is a simple **Number Guessing Game** implemented using JavaScript. The game challenges the user to guess a predefined number (`gameNum`). Users will be prompted until they guess the correct number, making it an engaging and interactive way to practice conditional statements and loops in JavaScript.

## Features
- **Interactive Gameplay**: Users are prompted to guess the correct number.
- **Feedback on Incorrect Guesses**: Users are informed when they guess the wrong number and prompted to try again.
- **Winning Message**: When the correct number is guessed, a congratulatory message is displayed.

## Technologies Used
- **JavaScript**: Core logic of the game.
- **Browser Prompt**: Used for user interaction.

## How to Play
1. Open the `index.html` file containing your game script in any browser.
2. The game will prompt you with: "Guess the Number".
3. Enter a number.
4. If the number is incorrect, you will receive feedback: "You Guessed the Wrong Number, Guess Again".
5. Keep guessing until you find the correct number (`25` in this case).
6. Upon guessing correctly, the game will display a message: "Congratulations, You entered the right number".

## Installation
1. Clone or download this repository.
2. Open the project in your favorite text editor.
3. Ensure the JavaScript code is linked to an HTML file so it can be executed in a browser.

## Example Code
Here’s the code snippet for reference:
```javascript
let gameNum = 25;

let userNum = prompt("Guess the Number:");
while (userNum != gameNum) {
    userNum = prompt("You Guessed the Wrong Number, Guess Again:");
}
console.log("Congratulations, You entered the right number");
