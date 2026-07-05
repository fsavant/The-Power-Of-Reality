# The Power of Reality

A psychological platformer built as a single self-contained HTML file (canvas + vanilla JS, no build step, no external assets).

## Play it locally
Just open `index.html` in any modern browser (desktop or mobile).

## Publish on GitHub Pages
1. Create a new GitHub repo (or use an existing one).
2. Upload `index.html` to the root of the repo (this zip is already named so it works as-is — GitHub Pages serves `index.html` automatically).
3. Go to **Settings → Pages** in the repo.
4. Under "Build and deployment", set **Source: Deploy from a branch**, branch: `main` (or `master`), folder: `/ (root)`.
5. Save. GitHub will give you a URL like `https://<username>.github.io/<repo-name>/` within a minute or two.

## Controls
- Joystick (bottom-left): move / swim
- 🧠 button (bottom-right): throw your brain at intrusive thoughts
- Hold **down** at a barrier's door to sink into its tunnel
- Hold **forward** at an unlocked-but-shut door to push it open
- Settings (⚙ top-right): Save / Load / New Game, Music On/Off

## Save data
Progress is saved locally in the browser via `localStorage` — it's per-device/per-browser, not synced anywhere.

## Notes for future edits
Everything (HTML, CSS, JS) lives in `index.html`. There's no build step — just edit and re-upload.
