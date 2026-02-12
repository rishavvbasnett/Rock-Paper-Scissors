# Project-3_Rock-Paper-Scissors
Third Project from TOP (by mostly using Javascript)

# Rock Paper Scissors

A browser-based Rock Paper Scissors game built with HTML, CSS, and JavaScript as part of [The Odin Project](https://www.theodinproject.com/) Foundations course.

## How It Works

- Click **ROCK**, **PAPER**, or **SCISSORS** to play a round
- First to **5 points** wins the game
- The game redirects to a win/lose page with a **Play Again** button

## What I Learned

- **DOM Manipulation** — selecting elements, changing text content, and updating styles with JavaScript
- **Event Listeners** — handling button clicks to trigger game logic
- **Git Branching Workflow** — creating a feature branch (`rps-ui`), working on it, merging it back into `main`, and deleting the branch after
- **CSS Flexbox** — laying out the game UI with flexible containers
- **Game Logic** — comparing player and computer choices, tracking scores, and determining a winner

## Branch Workflow Used

```
main ──────────────────────── merge ── push to GitHub ── delete rps-ui
  \                            /
   rps-ui ── commits ── commits
```

1. Created feature branch: `git checkout -b rps-ui`
2. Built the UI and game logic on `rps-ui`
3. Switched back: `git checkout main`
4. Merged: `git merge rps-ui`
5. Pushed: `git push origin main`
6. Cleaned up: `git branch -d rps-ui`

## Built With

- HTML
- CSS (Flexbox)
- JavaScript (DOM)