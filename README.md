# GitHub Trainer Card — Web Edition

A free, responsive pixel-art-inspired GitHub profile card made with plain HTML, CSS, and JavaScript.

## Run locally
1. Extract this ZIP.
2. Open `index.html` in a browser.
3. Enter your display name and public GitHub username.
4. Click **SAVE PROFILE**, then **FETCH STATS**.
5. Click the card to flip it. Select an award tile to inspect it.
6. Pick a color swatch to change the theme.

## Publish free with GitHub Pages
1. Create a new **public** GitHub repository, e.g. `trainer-card`.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**.
5. Choose branch `main` and folder `/(root)`, then click **Save**.
6. Wait a few minutes; the Pages URL will appear in Settings → Pages.

## Notes
- No login or GitHub token is required. It fetches only public profile fields from `api.github.com/users/{username}`.
- Profile name, username, and theme are stored in this browser's local storage.
- GitHub's basic public user endpoint does not provide a contribution total; that field intentionally remains `—`.
- The award tiles are demo achievements and are not official GitHub Universe awards. The app cannot verify real badge/Expedition data.
- Google Fonts is optional; the page uses fallback fonts if unavailable.
