# Credits — The Million-Dollar Vault

Original game made for family play. Private use. Not affiliated with any TV show, network or brand.
The "million‑dollar prize" is fictional. There is no real money, purchases, ads, accounts, analytics or network use.

- **Game design, code, layout, vector art (vault doors, wheel, logo, icons):** original, drawn in code (SVG/CSS/canvas).
  No third‑party images.
- **Trivia (221 questions) and vault phrases (40 puzzles):** original, written for this game (see `content/CONTENT_NOTES.md`).
- **v2 Family Pack seed (15 questions, 6 phrases), Showdown clues (28) and host lines:** original, written for this game.
- **Music and sound effects:** original, procedural Web Audio synthesis (`src/audio/`). No samples or recordings.
- **Host voice:** Host voice clips generated offline with Piper TTS (github.com/rhasspy/piper) using the Piper voice
  **'en_GB-northern_english_male-medium'** (rhasspy/piper-voices, MIT). Its training data is the *Crowdsourced high-quality UK and
  Ireland English Dialect speech data set* (OpenSLR 83; Demirsahin, Kjartansson, Gutkin & Rivera, LREC 2020), licensed
  **CC BY-SA 4.0** (creativecommons.org/licenses/by-sa/4.0/); the model was fine-tuned from Piper's en_US 'lessac' medium voice.
  The clips were then pitched down, slowed and given EQ and a light synthetic hall reverb (ffmpeg). The generated clips are
  shared under the same CC BY-SA 4.0 terms. The host is an original character voice, not modelled on, cloned from or imitating
  any real person. Piper was used offline as a tool and is not included in the game.
  Anything without a clip (solo questions, the Showdown clue) uses the device's own built-in voice, or captions only.
- **Fonts:** the device's built‑in system fonts (Avenir Next / Helvetica / Didot on Apple devices). No font files are bundled.
- **Build/test tools (development only, not shipped):** esbuild (MIT), Playwright (Apache‑2.0), Node.js, ffmpeg.
