# Flappy Beat Drop

A neon-soaked, rhythm-inspired arcade game built with HTML, CSS, and JavaScript. Leap through glowing speaker stacks, collect power-ups, chain combos, and push your score higher with every run.

## Live Demo

- Web demo: https://golden-elf-10a0d8.netlify.app/
- GitHub repository: https://github.com/khan018134/flappy-beat-drop

## Overview

Flappy Beat Drop takes the classic endless flapper formula and gives it a fresh hip-hop arcade identity. The player dodges obstacles, collects bonus pickups, and battles increasing speed while trying to set a new high score.

The project is intentionally lightweight, self-contained, and mobile-friendly so it can run instantly in a browser without any setup or build tools.

## Key Features

- Three selectable characters: MC Mic, Boombox, and Grillz
- Endless arcade gameplay with tap-to-fly mechanics
- Neon visual style with animated backgrounds and glowing effects
- Speaker-stack obstacle design inspired by music gear and DJ culture
- Combo scoring with multipliers up to 4x
- Power-ups:
  - Vinyl (+5 points)
  - Shield (temporary protection)
  - Slow-Mo (reduces pace temporarily)
- Local high-score saving through browser storage
- Responsive controls for mobile and desktop use
- Web Audio API-generated sounds and rhythmic beat loop

## Gameplay

- Tap the screen or press Space to flap upward.
- Avoid collisions with obstacles and the screen bounds.
- Pass through gaps to earn score.
- Build score chains by continuously clearing obstacles.
- Grab pickups to increase score and gain advantages.
- Survive as long as possible and beat your best run.

## Controls

### Mobile
- Tap anywhere on the screen to flap.

### Desktop
- Click the game area to flap.
- Press the Space key to jump.

### Audio
- Use the SOUND ON / SOUND OFF toggle in the top-right header.

## Character Skins

- MC Mic: slick microphone performer look
- Boombox: retro street-audio energy
- Grillz: flashy golden, high-impact style

## Local Run

No build process is required.

1. Clone or download the repository.
2. Open `index.html` directly in a browser, or serve the folder locally.
3. Optional local web server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deployment

This is a static web project and works with standard hosting providers such as:

- GitHub Pages
- Netlify
- Vercel
- Firebase Hosting

The entry point is `index.html`, so it can load correctly from a root URL or a static site root.

## Technology Stack

- HTML5
- CSS3
- JavaScript
- Canvas API
- Tailwind CSS CDN
- Font Awesome
- Google Fonts
- Web Audio API

## Project Structure

```text
flappy-beat-drop/
├── index.html
├── README.md
├── .gitignore
├── LICENSE
└── assets/
```

## Notes

- The game uses external CDNs for styling and typography; an internet connection is needed for the full look.
- High scores are saved locally in the browser via `localStorage`.
- The project is intentionally lightweight and easy to customize.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
