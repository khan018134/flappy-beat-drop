# Flappy Beat Drop

A vibrant, rhythm-inspired arcade game built with HTML, CSS, and JavaScript. Players control a stylized performer and navigate through neon speaker stacks, collect power-ups, build combos, and try to beat their personal high score.

This project is designed as a fast, mobile-friendly browser game with a hip-hop visual style, synthesized sound effects, and smooth single-file gameplay.

## Live Demo

- Production demo: https://golden-elf-10a0d8.netlify.app/
- GitHub repository: https://github.com/khan018134/flappy-beat-drop

## Game Overview

Flappy Beat Drop blends classic tap-to-fly mechanics with a modern music-themed arcade aesthetic. The player dodges obstacles, grabs power-ups, and steadily builds momentum as the pace and difficulty increase over time.

The experience is intentionally lightweight so it can run instantly in the browser without installation or a build pipeline.

## Features

- Three selectable characters: MC Mic, Boombox, and Grillz
- Tap-to-fly gameplay with mouse and keyboard support
- Neon city-night visual style with glowing effects and animated backgrounds
- Dynamic obstacle generation with speaker-stack style pipes
- Score combo system with multipliers up to 4x
- Collectible power-ups:
  - Vinyl (+5 points)
  - Shield (protective aura)
  - Slow-Mo (temporary speed reduction)
- Local high-score saving using browser storage
- Responsive layout for mobile and desktop screens
- Web Audio API synth effects for jump, scoring, bass hits, and power-ups

## Gameplay Mechanics

- Start the round from the menu screen.
- Tap or press Space to flap upward.
- Avoid colliding with the top or bottom boundaries and the speaker obstacles.
- Pass through gaps to score and build combo chains.
- Collect pickups to gain points and unlock tactical advantages.
- Survive as long as possible and beat your best recorded score.

## Controls

### Mobile
- Tap anywhere on the screen to flap.

### Desktop
- Click the game area to flap.
- Press the Space key to jump.

### Audio
- Use the SOUND ON / SOUND OFF toggle in the top-right of the game header.

## Character Skins

- MC Mic: clean and focused performer look
- Boombox: bold retro street sound aesthetic
- Grillz: flashy golden, high-energy character style

## Local Development

No build step is required.

1. Clone the repository.
2. Open `index.html` directly in your browser, or run a local static server.
3. For a simple local server:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Deployment

This is a static website and can be deployed on any hosting platform that supports HTML/CSS/JS.

### Recommended options
- GitHub Pages
- Netlify
- Vercel
- Firebase Hosting

Because the project uses `index.html` as the main entry file, it will work correctly on a root URL deployment.

## Project Structure

```text
flappy-beat-drop/
├── index.html
├── README.md
├── LICENSE
├── .gitignore
└── assets/ (optional future content, art, or screenshots)
```

## Tech Stack

- HTML5
- CSS3
- JavaScript (Canvas API)
- Tailwind CSS CDN
- Font Awesome CDN
- Google Fonts
- Web Audio API

## Notes

- The game uses external CDN assets for styling and iconography, so an internet connection is needed for the full visual experience.
- The saved high score is stored locally in the browser via `localStorage`.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
