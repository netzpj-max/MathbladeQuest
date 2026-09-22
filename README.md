# Mathblade Quest

A self-contained 2D flat-anime turn-based multiplication RPG for the browser.

## Play

Open `index.html` directly in a modern browser, or publish the repository with GitHub Pages.

No build step, package manager, backend, or external dependency is required.

## Core features

- 9-stage multiplication campaign
- Thai and Simplified Chinese UI
- Turn-based battle system
- Automatic normal-attack questions
- Harder skill questions with rainbow skill UI
- HP / MP / EXP / leveling
- Guard, skills, items, random item drops
- Animated player, monsters, skills, defense, and item use
- Stage leaderboard and final-run summary
- NPC simulated rivals for progression targets
- Responsive desktop / tablet / mobile layout
- Offline-friendly HTML/CSS/JavaScript

## Repository structure

```text
mathblade-quest/
├─ index.html
├─ README.md
├─ .gitignore
├─ .nojekyll
└─ assets/
   └─ favicon.svg
```

## GitHub Pages

1. Create a new GitHub repository.
2. Upload all files from this project.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`.
6. Save.

GitHub Pages will serve `index.html` as the game homepage.

## Local testing

Double-click `index.html`, or run a simple local server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Notes

- Leaderboard data is stored in the player's browser using `localStorage`.
- NPC rival scores are simulated game characters, not real online players.
- No license file is included. Add the license you want before publishing as open source.
