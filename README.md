# Simon Says - Memory Game

A simple **Simon Says Memory Game** built using **HTML, CSS, and JavaScript**.  
The game generates a random sequence of button flashes, and the player must repeat the sequence correctly to progress to the next level. The highest score is tracked automatically.

---

## Features

- **Dynamic Level System:** Each round adds a new step to the sequence.
- **Highest Score Tracking:** Displays the highest level achieved in the session.
- **Event Delegation:** Efficiently handles user button clicks.
- **Smooth Flash Animation:** Buttons flash with a color and "grows" effect.
- **Game Over State:** Displays the final score and allows restart with any key.

---

## How to Play?

1. **Press any key** to start the game.
2. **Watch carefully** as a button flashes (color + grow effect).
3. **Click the buttons in the same order** as shown.
4. Each correct round increases the level.
5. If you make a mistake, the game ends, and you’ll see your score and highest score.
6. Press **any key again** to restart.

---

## 📂 Project Structure
├── index.html # Main HTML file
├── style.css # Styles for the game UI
└── script.js # Game logic (sequence, level, flash, etc.)


---

## 🧑‍💻 JavaScript Logic Overview

- `gameSeq[]`: Stores the randomly generated sequence by the game.
- `userSeq[]`: Stores the sequence entered by the user.
- `level`: Tracks the current level.
- `highest`: Tracks the highest score in the session.
- `buttonFlash(id)`: Flashes a button by temporarily removing and re-adding its color class.
- `check(currIdx)`: Checks if the user’s sequence matches the game’s sequence.

---


## 📜 License

This project is open-source and free to use.

## Thank you 
## Pranay Jaiswal Signing Off 
## Enjoy and Contribute

