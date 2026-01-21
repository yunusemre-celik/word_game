# Fast Fingers: Precision Edition

## Project Description
Fast Fingers is a web-based typing proficiency game developed to test reaction speed and typing accuracy. Built entirely with **HTML5, CSS3, and Vanilla JavaScript**, this project utilizes the HTML5 Canvas API for rendering and the Web Audio API for a custom, procedurally generated audio engine. No external libraries, assets, or game engines were used in development.

## Features

### Core Mechanics
* **Precision Input System:** The game employs a "lock-on" typing mechanic. Once the player starts typing a word, the input field locks to that specific target. To switch targets, the player must either complete the current word or use `Backspace` to clear the input buffer.
* **Dynamic Difficulty:** Game speed and word length increase progressively as the player advances through levels.
* **Score & Health System:** The player starts with 3 lives. Missing a word results in the loss of a life. The game ends when all lives are depleted.

### Customization
* **Visual Themes:** Three distinct rendering modes are available:
    * **Matrix:** Green code-rain aesthetic with terminal fonts.
    * **Neon:** High-contrast synthwave style with glow effects.
    * **Deep Space:** Starfield background with high-visibility text.
* **Custom Word Lists:** Users can upload a local `.txt` file containing a custom list of words to practice specific vocabulary.

### Audio Engine
* **Procedural Sound Generation:** All sound effects (SFX) and background music are generated in real-time using JavaScript Oscillators and Gain Nodes via the Web Audio API. No external audio files are loaded.
* **Audio Controls:** Independent volume sliders and mute toggles for Music and SFX are available in the Settings menu.

## How to Run
This application is a standalone HTML file requiring no installation or server-side setup.

1.  Download the `word_game.html` file.
2.  Open the file in any modern web browser (Google Chrome, Firefox, Edge, or Safari).
3.  The application will initialize immediately.

## Controls

| Key | Function |
| :--- | :--- |
| **A - Z** | Type characters to match falling words. |
| **Backspace** | Delete the last typed character / Unlock current target. |
| **ESC** | Pause the game / Open In-Game Menu / Go Back. |

## Usage Guide

### Starting the Game
Upon launching, the **Start Screen** allows you to:
1.  Select a visual theme from the dropdown menu.
2.  (Optional) Upload a `.txt` file for a custom word pool.
3.  Click "START GAME" to begin Level 1.

### Gameplay Rules
* Words spawn at the top of the canvas and descend at varying speeds.
* Type the word exactly as displayed.
* Successful completion of a word increments the score and clears the word from the screen.
* If a word reaches the bottom of the screen, the screen shakes, a damage sound plays, and one life heart is removed.

### Settings & Configuration
Press `ESC` during gameplay to access the **Pause Menu**, then select **SETTINGS**.
* **Music:** Adjust the slider to change the background music volume or check "MUTE" to disable it.
* **SFX:** Adjust the slider for typing and explosion sounds or check "MUTE" to disable them.

## Technical Stack
* **Frontend:** HTML5, CSS3
* **Logic:** JavaScript (ES6+)
* **Graphics:** HTML5 Canvas API (2D Context)
* **Audio:** Web Audio API
