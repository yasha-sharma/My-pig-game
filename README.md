# My-pig-game
A classic pig dice game built with javascript

## 🐷 The Pig Game

### Overview

The **Pig Game** is a popular dice game for two players. This version is built using **HTML**, **CSS**, and pure **JavaScript**, making it an excellent demonstration of **DOM manipulation**, **event handling**, and implementing clear **game state logic**.

The goal is to be the first player to reach a predefined **winning score** (usually 100).

-----

## 🚀 How to Play (Game Rules)

### The Objective

Be the first player to reach the **target score** (default is 100 points).

### Gameplay Turn

1.  On your turn, you repeatedly **roll a die**.
2.  Each roll is added to your **Current Score**.
3.  You can choose to **Hold** at any time.

### Holding

  * If you click **"Hold"**, your **Current Score** is added to your **Global Score**, and control passes to the other player.

### Losing the Turn

  * If you roll a **1**, you lose your entire **Current Score** (it resets to 0), and control immediately passes to the other player.

-----

## ✨ Features

  * **Two-Player Local Game:** Supports two players taking turns on the same device.
  * **Dynamic Dice Roll:** A visual representation of a standard six-sided die is updated with each roll.
  * **Active Player Indication:** Visually highlights the player whose turn it is.
  * **Score Tracking:** Clearly displays **Current Scores** and **Global Scores** for both players.
  * **Customizable Winning Score:** Players can set a custom score goal before starting the game.
  * **"New Game" Reset:** Allows for a quick and easy game reset.
  * **Winner State:** Locks the game controls and highlights the winning player.

-----

## 🛠️ Technologies Used

  * **HTML5:** Provides the structure and layout for the game interface.
  * **CSS3:** Handles all the styling, including dynamic player highlighting.
  * **JavaScript (ES6+):** Implements all the core game logic, including the dice roll, score accumulation, state management, and DOM updates.

-----

## ⚙️ Local Setup

To get a local copy up and running, follow these simple steps:

1.  **Clone the repository:**
    ```bash
    git clone [Your-Repo-URL]
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd pig-game
    ```
3.  **Open `index.html`:** Simply open the `index.html` file in your preferred web browser to start playing immediately.

-----

## 📂 Project Structure

The project maintains a clear and standard front-end structure:

```
pig-game/
├── index.html       # The main markup and structure
├── style.css        # Styles for the game layout and components
├── script.js        # The core JavaScript logic for the game
└── dice-images/     # Folder containing images for the dice faces (e.g., dice-1.png, dice-2.png)
```

-----

## 🤝 Contribution

Contributions are welcome\! If you find a bug or have a suggestion for an improvement (e.g., AI opponent, better UI), please feel free to:

1.  **Fork** the repository.
2.  Create a new feature branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the branch (`git push origin feature/AmazingFeature`).
5.  Open a **Pull Request**.

