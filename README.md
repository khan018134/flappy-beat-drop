# Flappy Beat Drop

A neon-soaked, rhythm-inspired arcade game built as a lightweight, single-page HTML experience. Take control of a musical character, flap through animated speaker stacks, collect power-ups, and chase a new high score.

## Play

**Live game:** [Play Flappy Beat Drop](https://golden-elf-10a0d8.netlify.app/)

## Features

- Three playable characters: MC Mic, Boombox, and Grillz.
- Tap-to-fly arcade gameplay with keyboard support.
- Animated speaker-stack obstacles and a neon, color-shifting stage.
- Combo scoring with multipliers up to 4×.
- Vinyl collectibles worth +5 points, plus Shield and Slow-Mo power-ups.
- Synthesized sound effects and a looping beat, with a sound toggle.
- High score saved locally in your browser.
- Responsive layout designed for phones and desktop browsers.

## Controls

- **Mobile:** Tap the screen to flap.
- **Desktop:** Click or press **Space** to flap.
- Use the skin cards to choose a character before playing. Toggle audio from the header.

## Run locally

No build step or package installation is required. Download or clone the repository, then open `index.html` in a modern browser. For local hosting, you can also run a simple static server from the project directory, for example:

```bash
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Deploy

This is a static website. It can be deployed with GitHub Pages, Netlify, or another static hosting provider. The entry point is `index.html`, so the game loads from the site's root URL.

The page loads Tailwind CSS, Font Awesome, and Google Fonts from their respective CDNs, so an internet connection is needed for those external assets. The game itself is implemented with HTML, CSS, Canvas, and vanilla JavaScript; audio is generated with the Web Audio API.

## Project structure

```text
.
├── index.html    # Game, styles, and client-side logic
├── README.md     # Project overview and usage
└── .gitignore    # Common local/editor files excluded from Git
```

## License

No license has been specified yet. Unless a license is added, standard copyright applies and reuse is not automatically granted.
