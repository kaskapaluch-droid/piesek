# Piesek Platformer — Deploy

This is a static, single-file HTML game. No build tools required.

## Quick preview
Double-click `index.html` to open it in a browser.

> On iOS Safari you must interact once (tap screen) to enable audio (WebAudio policy).

## Deploy options

### 1) GitHub Pages (free)
1. Create a new repo (or use an existing one).
2. Add `index.html` to the root of the repo.
3. Push to GitHub.
4. In **Settings → Pages**, set **Source** to **Deploy from a branch**, select `main` and `/ (root)`.
5. Wait a minute, your game will be available at `https://<your-user>.github.io/<repo>/`.

### 2) Netlify (drag & drop)
1. Go to https://app.netlify.com/drop
2. Drag-and-drop the folder containing `index.html`.
3. Netlify will assign a URL like `https://<random-name>.netlify.app`.

### 3) Vercel
1. `vercel deploy` in the folder with `index.html`, or use the Vercel web UI.
2. Set project type to **Other** (static site).

### Performance tips
- Keep the game in one file (done).
- Avoid large images; use the upload button for your sprite (already supported).
- Audio will only play after user interaction due to browser policies.

### Custom domain
- Both Netlify and Vercel support custom domains under Project → Domains.
- For GitHub Pages, add a `CNAME` file with your domain and set DNS to GitHub Pages.

Enjoy! 🐶🎮
