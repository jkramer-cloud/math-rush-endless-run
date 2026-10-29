# Math Rush: Endless Run

An original, three-lane endless runner designed from a student idea for the Naches Learning Arcade. The graphics are drawn entirely in HTML5 Canvas with perspective-style 2.5D scenery. No third-party libraries, commercial artwork, or online services are required.

## Start playing

Open `hudsons_math_runner.html` in a modern browser (Chrome, Edge, Safari, or Firefox) or upload the file to a static site such as GitHub Pages. The game uses a portrait layout on desktop and mobile.

- **Left/Right arrow** or **A/D**: change lanes
- **Up arrow**, **W**, or **Space**: jump over crates
- **Down arrow** or **S**: slide below overhead bars
- **P** or **Esc**: pause (or resume)
- **Touch**: swipe left/right/up/down, or use the visible game buttons
- **Math**: move into the lane with the correct answer before the checkpoint; tapping an answer button also moves to its lane
- **Hint**: tap "Show hint" to reveal a guided strategy while the math gate approaches

## Features

- The goal is to run farther, with speed increasing steadily (up to a cap).
- Three lane obstacles: low crates (jump), hanging bars (slide), and trains (avoid by switching lanes).
- Math gates show three possible numeric answers. The correct response earns bonus points and starts/builds a correct-answer streak.
- A wrong answer costs **two of the three health points**. Ordinary collisions cost one health point. The run ends at zero health. Collision immunity briefly prevents repeated obstacle hits, but not math penalties.
- Two math pools: **grades 5–6** (operations, fractions, decimals, area, money) and **grades 7–8** (integers, percentages, algebra, ratios, exponents, and more).
- Coins placed on the track, a wallet, and ten cosmetic characters with increasing coin costs.
- Score, distance, health, coin collection, and math accuracy on the game-over screen.
- The setting alternates between a colorful city and desert environment as the distance increases.
- Sound effects are original synthesized tones and **off by default** so the game is classroom-friendly.
- Local browser storage remembers coin balance, unlocked/selected character, grade-band choice, sound preference, and personal records.

## Add to the Learning Hub

Copy `hudsons_math_runner.html` into the same published folder as the Learning Hub HTML (or place it in a games folder and adjust the URL). For a simple entry, use:

```html
<a href="hudsons_math_runner.html">Math Rush: Endless Run</a>
```

Suggested Learning Hub listing:

- **Name:** Math Rush: Endless Run
- **Category:** Math / Arcade / Endless Runner
- **Description:** Dodge trains, jump over crates, slide under barriers, collect coins, and solve math checkpoints by choosing the correct lane. Run farther to go faster, beat your record, and unlock new characters.
- **Grades:** 5–8

If your hub uses JavaScript-based game cards or routing, its code needs to be updated accordingly; this project does **not** modify any existing Hub files by itself.

## Important design notes

- The prototype uses 2.5D canvas perspective, **not** an actual 3D game engine or imported Subway Surfers artwork.
- Progress is saved per browser profile/device, not per student account. Clearing site data resets local progress.
- There is no server-side leaderboard, instructor dashboard, or cloud synchronization yet.
- This is an initial functional prototype intended for student testing and iteration. Review difficulty, math accuracy, readability, and device performance before classroom deployment.
