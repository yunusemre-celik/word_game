# Fast Fingers: Precision Edition

A high-speed, precision typing game built entirely in HTML5. Lock onto falling words by typing them accurately to survive as long as possible. Choose between multiple immersive themes, adjust audio, or upload your own custom word lists!

## Features
- **Precision Lock-on System**: Type the beginning of a word to lock onto it. Misspelled characters shake the screen!
- **Dynamic Difficulty**: The speed and complexity of the falling words increase as you advance through the levels.
- **Multiple Aesthetics**: 
  - `Matrix (Hacker)`
  - `Neon (Synthwave)`
  - `Deep Space`
- **Custom Word Lists**: Upload any `.txt` file containing your own words separated by spaces or commas to practice specific vocabulary.
- **Audio Engine**: Custom synthesized sound effects and background music logic leveraging the Web Audio API.

## How to Play
1. Download or clone this repository, or simply open the `word_game.html` file in any modern web browser.
2. Select your preferred theme from the Start Screen.
3. Click **START GAME**.
4. Type the exact characters of any falling word.
5. Do not let any word reach the bottom of the screen, or you lose a life (❤️)!
6. Survive the level's quota to advance to the next round.

## How to Publish
This game is a zero-dependency, single-file HTML application. You can host it anywhere static files are supported:
- **GitHub Pages**: Go to repository settings -> Pages -> Deploy from a branch. Select `main` -> `root` directory.
- **Netlify / Vercel**: Drag and drop the folder containing `word_game.html` directly into their dashboard to deploy.
- **itch.io**: Zip the `word_game.html` file (optionally renaming it to `index.html`) and upload it as a HTML game project.

## Author
Developed by **hirtzirt**. Powered by AI.