# Sudoku Duel 🤺

A modern, interactive Sudoku game where you can challenge an AI opponent or a friend in a head-to-head duel. This project is built with pure HTML, Tailwind CSS, and vanilla JavaScript, and is powered by Google's Gemini AI for a dynamic and challenging experience.

<!-- TODO: Replace with an actual screenshot of the game -->
 

## ✨ Features

- **Dynamic AI-Powered Puzzles:** Every game features a unique, procedurally generated puzzle from the Gemini AI, with varying difficulty levels (Easy, Medium, Hard).
- **Challenging AI Opponent:** Face off against a smart AI that uses Gemini to make strategic moves based on the current board state.
- **Local Multiplayer:** Play against a friend in a "hot-seat" mode on the same device.
- **Strategic Gameplay:** The winner is the player with the most correctly filled cells when the board is full.
- **Modern UI & UX:** Enjoy a clean interface with helpful features like:
  - **Pencil Mode:** Jot down candidate numbers before making a final decision.
  - **Smart Highlighting:** Selecting a cell highlights its row, column, and 3x3 box.
  - **Number Highlighting:** See all instances of a selected number on the board.
  - **Completed Number Indicator:** The number pad grays out numbers that are fully placed on the board.
- **Timed Turns:** Keep the pressure on with an adjustable turn timer.

## 🎮 How to Play

1.  Open the `public/index.html` file in your browser or visit the deployed site.
2.  Choose your game mode: **vs. AI** or **vs. Player**.
3.  Select a difficulty and turn timer duration.
4.  Click **"Start Game"**.
5.  Take turns filling in the Sudoku grid. The player with the most correct cells at the end wins!

## 🛠️ Tech Stack

- **Frontend:** HTML5, Tailwind CSS, Vanilla JavaScript
- **AI:** Google Gemini API (for puzzle generation and AI opponent logic)
- **Deployment:** Firebase Hosting
- **CI/CD:** GitHub Actions

## 🚀 Setup and Installation

To run this project locally, you will need a Google Gemini API key.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2.  **Add your API Key:**
    - Open the `public/index.html` file.
    - Find the following line in the `<script>` section:
      ```javascript
      const geminiApiKey = '931e07bcc7244da89afc97fe5e5c8711';
      ```
    - Replace the placeholder key with your own Google Gemini API key. You can get one from Google AI Studio.

3.  **Run the game:**
    - Simply open the `public/index.html` file in your web browser.

## ☁️ Deployment

This project is configured for continuous deployment to Firebase Hosting using GitHub Actions.

- Pushes to the `main` branch are automatically deployed to the live channel.
- Pull requests generate a preview deployment for review.

The configuration can be found in the `.github/workflows/` directory.
