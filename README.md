> This is an experiment. I was frustrated trying to Google for a simple alphabet flashcard game for my daughter, and mostly running into paid options. So I wrote a large prompt, and asked Codex to make it. 90% is the first run, and then a few tweaks for appearance. You can try it here: [https://thebracket.github.io/alphabet_game/alphabet.html](https://thebracket.github.io/alphabet_game/alphabet.html).

# Alphabet Adventure

Alphabet Adventure is a pastel, kid-friendly flashcard game that helps little learners practice the uppercase English alphabet. It runs entirely in `alphabet.html` with no build step—just open the file in a browser.

## How to play
- Open `alphabet.html` in a modern browser (supports local file opening).
- Tap **Click here to play** to start the flashcards.
- Each round shows a large letter with a spoken prompt (when the Web Speech API is available). Use **Repeat** to hear or re-read the prompt, **Answer** to reveal a mnemonic, and **Continue** for the next letter.
- Use **Voice on/off** to mute speech and **Exit** to return to the start screen.

## Data
- The alphabet deck lives in `alphabet.html` inside the `LETTERS` constant. Each letter has 1–3 mnemonics; edit the array to adjust wording or add more variety.

## Tech notes
- Vanilla HTML, CSS, and JavaScript.
- Optional Web Speech API support for spoken prompts and answers; the UI still works if speech is unavailable.
- Uses Google Fonts and Font Awesome (free) via CDN.

## Changelog
- 2024-12-01: Initial version generated with OpenAI Codex — as an experiment.

## License
- MIT License. See `LICENSE.md`.
