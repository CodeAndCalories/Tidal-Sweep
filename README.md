# 🌊 Tidal Sweep

**Navigate the ocean floor. Avoid the jellyfish. Clear the depths.**

Tidal Sweep is an ocean-themed tile-sweeping puzzle game inspired by classic grid-based logic games. Explore underwater terrain, use number clues to locate hidden jellyfish, and flag them before they sting you — all while marine life drifts through the deep.

## 🎮 Play Now

**[Play Tidal Sweep](https://codeandcalories.github.io/tidal-sweep/)**

## ✨ Features

- **Three ocean depths** — each with unique visuals, color palettes, and ambient sea creatures:
  - 🐠 **Shallows** (9×9, 10 jellyfish) — soft teal waters with tropical fish swimming by
  - 🦈 **Deep Sea** (16×16, 40 jellyfish) — dark ocean blue with passing sharks
  - 🦑 **The Abyss** (16×30, 99 jellyfish) — pitch-dark navy with kraken tentacles rising from below
- **Smooth theme transitions** — colors, backgrounds, and creatures shift as you change depth
- **Timer and score tracking** — see how fast you can clear each level
- **Flag system** — right-click (or long-press on mobile) to mark suspected jellyfish
- **Safe first click** — your first reveal is always jellyfish-free
- **Animated ocean environment** — drifting waves, rising bubbles, and randomly spawning sea creatures all rendered in pure CSS and inline SVG
- **Mobile friendly** — works on phones and tablets with touch support

## 🕹️ How to Play

1. **Left-click** a tile to reveal it
2. Numbers show how many jellyfish are in the 8 surrounding tiles
3. **Right-click** (or long-press on mobile) to flag a tile you think contains a jellyfish
4. Reveal all safe tiles to win — but hit a jellyfish and you get stung!

## 🚀 Setup

No build tools, frameworks, or dependencies required. It's a single HTML file.

### Play locally

Open `index.html` in any modern browser.

### Host on GitHub Pages

1. Create a new repository on GitHub
2. Upload `index.html` to the root of the repo
3. Go to **Settings → Pages → Source** and select your main branch
4. Your game will be live at `https://yourusername.github.io/repo-name/`

## 🛠️ Tech Stack

- **HTML5 / CSS3 / Vanilla JavaScript** — zero dependencies
- **Inline SVG** — all creatures (fish, sharks, tentacles) are procedurally generated with randomized colors, sizes, and animations
- **CSS Custom Properties** — theme switching with smooth transitions
- **CSS Animations** — waves, bubbles, creature movement, and UI effects

## 📁 Project Structure

```
tidal-sweep/
└── index.html    ← the entire game in one file
```

That's it. No `node_modules`. No bundler config. No build step.

## 🎨 Customization Ideas

Want to make it your own? Here are some things you could add:

- **Best times leaderboard** with `localStorage`
- **Sound effects** for reveals, flags, wins, and stings
- **Custom grid sizes** with a settings menu
- **New depth levels** with different creatures
- **Particle effects** when revealing tiles
- **Dark/light mode toggle** independent of difficulty

## 📄 License

MIT — free to use, modify, and share.
