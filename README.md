# Birthday Surprise ❤️

A four-screen birthday website built with plain HTML, CSS and JavaScript.

## Personalize
Edit the `CONFIG` object at the top of `script.js`: set `name`, `age`, `birthdayMessage`, `loveLetter`, and optionally `musicFile` (for example `assets/birthday-music.mp3`). Add photos named `memory-1.jpg`, `memory-2.jpg`, and `memory-3.jpg` inside `assets/`.

## Screens
1. Cake: click Blow the candle, tap the flame, or enable microphone detection.
2. Birthday reveal: automatic after the candle goes out, with confetti.
3. Love letter: opens on button click.
4. Memories: opens on button click with your photos.

Microphone is requested only after clicking its button. It is analyzed locally in the browser and is not uploaded. Microphone needs HTTPS or localhost; tapping the flame is the fallback.

## Preview
Run `python3 -m http.server 8000` in this folder and open http://localhost:8000.

## GitHub Pages
1. Create a GitHub repository named `birthday-surprise`.
2. Upload `index.html`, `style.css`, `script.js`, `README.md`, and `assets/` to the repository root.
3. Go to Settings → Pages.
4. Choose Deploy from a branch, branch `main`, folder `/(root)`, then Save.
5. Your URL will be `https://YOUR-GITHUB-USERNAME.github.io/birthday-surprise/`.
