# Math Rush: Endless Run — Version 1.1

An original 2.5D educational endless runner inspired by a Naches Learning Arcade student's idea. Choose math-answer lanes, dodge crates, overhead beams and trains, collect coins, and keep going as the speed increases.

## Release 1.1 — Gameplay Repair and Style Studio

- **Coin pickups repaired:** coins are collected when the runner reaches their actual on-screen depth; collection increments the run coin count and saved wallet. Coins appear singly or in pairs with longer breaks between groups.
- **Obstacles repaired:** trains require a lane switch, crates can be jumped, and overhead beams can be slid beneath. Three hearts; hitting obstacles reduces health and reaching zero opens the **RUN OVER** result screen.
- **Five changing areas:** City Streets, Desert Canyon, Forest Trail, Snowy Summit, Neon Night. A new zone arrives approximately every 390 meters and cycles endlessly.
- **Character & Style Studio:** ten runners; six outfits; five headwear styles (including default); five handheld prop choices; four boards; and four trails. Purchases consume game coins and persist in local browser storage. All upgrades are cosmetic.
- Grade 5–6 and grade 7–8 math questions, pause, hints, run results and records remain available.

## Publish to GitHub Pages

1. Open the existing public GitHub repository `jkramer-cloud/math-rush-endless-run`.
2. Upload **all files from this folder to the repository root**. Replace the existing `index.html` and `README.md` (and any named preview images). The essential updated file is `index.html`.
3. Make sure GitHub Pages uses `main` → `/(root)`, then open https://jkramer-cloud.github.io/math-rush-endless-run/ .
4. On Chrome, use Ctrl+Shift+R if your browser still shows the old version.

**Learning Hub:** The game address is unchanged, so the game repair goes live when this repository deploys. A separate optional Learning Hub v31.23 package updates the Hub card description to mention the Style Studio.

## Keyboard / touch controls

Left/Right or A/D: switch lanes. Up/W/Space: jump. Down/S: slide. P/Escape: pause. On touchscreens, swipe or use the visible action buttons. Choose a math answer by entering its lane before the gate.

This original game is not affiliated with Subway Surfers. It is built as one self-contained HTML file, with no additional runtime libraries or account sign-in. High scores, coins and outfits are stored on the device in browser localStorage; changing devices or clearing browser data may clear progress.
