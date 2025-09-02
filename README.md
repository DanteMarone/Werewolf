# Werewolf: A Gemini-Powered AI Game

Welcome to **Werewolf**, an immersive, single-page web application where you can play the classic social deduction game against a cast of AI characters powered by Google's Gemini API. This project brings the thrilling experience of Werewolf to your browser, with no backend or complex setup required.

This project is designed as a **single-file, single-page application (SPA)**. This makes it incredibly easy to share, run, and play. Just open the `index.html` file, and you're ready to go!

## ✨ Features

*   **Interactive Gameplay**: Join the game as a **Player** and try to survive the night, or become an **Observer** to watch the AI drama unfold with full knowledge of everyone's roles.
*   **AI-Driven Characters**: Play with up to 5 AI villagers, each with a unique personality and backstory, powered by the **Gemini API**. The AI handles everything from dialogue and strategic decisions to private note-taking.
*   **Dynamic Game Phases**: Experience the full Werewolf game loop, including:
    *   **Mayor Elections**: Nominate candidates and vote for a leader.
    *   **Night Phase**: Werewolves choose their target, and special roles like the Seer and Witch take their actions.
    *   **Day Phase**: Discuss, debate, and vote to eliminate a suspected werewolf.
*   **Special Roles**: Play with key roles that make the game dynamic:
    *   **🐺 Werewolf**: Deceive the village and eliminate players at night.
    *   **🔮 Seer**: Learn the true role of one player each night.
    *   **🧙‍♀️ Witch**: Use a one-time heal potion and a one-time kill potion.
*   **In-Game Tools**:
    *   **Private Scratchpad**: Keep your own notes and theories.
    *   **AI Scratchpads**: As an observer, view the private notes of the AI players to understand their reasoning.
*   **AI-Generated Content**:
    *   **Round Summaries & Images**: At the end of each day's discussion, a summary of the round is generated and visualized with an AI-created image using the **Imagen API**.
    *   **Game Analysis**: After the game ends, get a full AI-powered analysis of the match, including the MVP and key turning points.
*   **Immersive Experience**:
    *   **Atmospheric Audio**: Sound effects and background music powered by **Tone.js**.
    *   **Voice Input**: Use your microphone to speak your turn instead of typing.

## 🛠️ Tech Stack

This project is built with a focus on simplicity and leveraging modern web technologies:

*   **HTML, CSS, and Vanilla JavaScript (ES6 Modules)**: The core of the application is built without any frontend frameworks.
*   **Tailwind CSS**: For a utility-first approach to styling.
*   **Tone.js**: For web-based audio and sound effects.
*   **Google Gemini API**: Powers the AI's logic, decision-making, and dialogue.
*   **Google Imagen API**: Generates images for the round summaries.

## 🚀 Getting Started

To run this project, you only need a modern web browser and a Google Gemini API key.

### Prerequisites

*   A modern web browser that supports ES6 modules (e.g., Chrome, Firefox, Safari, Edge).
*   A Google Gemini API key. You can get one from [Google AI Studio](https://aistudio.google.com/).

### Installation & Configuration

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/werewolf-gemini.git
    ```

2.  **Add your API Key:**
    Open the `index.html` file in a text editor and find the following line (around line 300):
    ```javascript
    const GEMINI_API_KEY = "";
    ```
    Paste your Gemini API key inside the quotes.

3.  **Open the game:**
    Simply open the `index.html` file in your web browser. You can do this by double-clicking the file or by using a local web server.

## 🎮 How to Play

1.  **Choose Your Experience**: On the title screen, you can choose to be an **Observer** or a **Player**.
    *   **Observer**: You'll see everyone's roles and private thoughts.
    *   **Player**: You'll be assigned a secret role and play as part of the village.
2.  **Setup Your Character**: If you join as a player, you can customize your name and the names and backstories of the AI players.
3.  **The Game Begins**: The game will proceed through the phases of Mayor Election, Night, and Day.
4.  **Interact with the UI**:
    *   **Player Grid**: On the left, you can see all the players, their status (alive/dead), and their roles (if you are an observer or they are revealed).
    *   **Chat Log**: The main area shows the game's progress, dialogue, and events.
    *   **Action Panel**: When it's your turn to act (vote, speak, use a power), buttons and inputs will appear here.
    *   **Header Controls**: Use the buttons in the header to view rules, use your scratchpad, toggle audio, and pause the game.
5.  **Win the Game**:
    *   **Villagers**: Win by eliminating all the werewolves.
    *   **Werewolves**: Win when the number of werewolves is equal to or greater than the number of villagers.

## 🤖 About this Project

This project was co-created with the assistance of AI tools, **Gemini** and **Jules**. The goal was to create a compelling, shareable, and fun single-page application that showcases the power of modern AI and web technologies.

The decision to keep it as a single-file SPA was intentional to ensure maximum portability and ease of use. Anyone can download the `index.html` file, add their API key, and start playing immediately.

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
