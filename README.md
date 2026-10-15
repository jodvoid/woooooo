# For Koushani ✦

A mobile-first interactive birthday surprise made with plain HTML, CSS and JavaScript. No backend, login, database, voice recording, AI voice, or build step required.

## Files
- `index.html` — complete website and interaction logic
- `assets/koushani-caricature.png` — custom illustrated birthday caricature

## Run locally
Open `index.html` in a modern browser. For best results, serve the folder locally (some browsers limit features for `file://` pages):

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish
**GitHub Pages:** upload `index.html` and the entire `assets` folder to the root of your repository, then open **Settings → Pages** and deploy from the `main` branch and `/ (root)`.

**Netlify:** drag the whole `koushani-birthday` folder into Netlify Drop, or connect the repository.

**Vercel:** import the repository and use the default static deployment settings.

## Sound
No voice or speech synthesis is used. The party horn and subtle musical tones are synthesized in-browser with Web Audio after the visitor taps the opening button. Audio is not autoplayed before interaction. The sound toggle controls the audio.

## Customization
Edit the Bengali message directly in `index.html`. Replace `assets/koushani-caricature.png` with another image using the same filename if desired.
