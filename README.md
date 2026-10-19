# MINDRACE / MIYA ARENA — standalone reconstructed project

This is a self-contained, static HTML/CSS/JavaScript version based on the screenshots and the accessible `arenauitc` source repo. It is intended to be easy to upload to GitHub and host on GitHub Pages or Vercel.

## Start locally
Open `index.html` in a modern browser. No package installation or build step is required.

## Project layout
- `index.html` — setup UI, game screen, result screen, modal.
- `styles.css` — responsive layout and styling.
- `js/app.js` — subject and mode selection, car chooser, timer, score, answer controls, language switching, sound and game flow.
- `js/questions.js` — bundled local questions by subject.
- `assets/utc-logo.svg` — local UNITED IT CLUBS-style logo asset.
- `assets/cars/*.svg` — local, stylized car illustrations used by the game.
- `RECOVERY_STATUS.md` — limits of this reconstruction.

## Deploy to GitHub
1. Create/open a GitHub repository.
2. Upload all files and folders preserving their directory paths.
3. Make sure `index.html` is at the repository root.
4. For GitHub Pages, open **Settings → Pages** and select the `main` branch and root folder.
5. On Vercel, import this repository and use the default static deployment settings.

## Notes
All assets are local; the app does not need external image/audio URLs. Music and sound cues are generated using Web Audio when enabled.
