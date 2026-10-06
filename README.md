# Mohd Mujtaba — Portfolio

Personal portfolio website (online resume) of **Mohd Mujtaba**, Senior Backend Engineer (SDE-3) — Fintech & Distributed Systems.

## What's inside

- **Animated dark-premium hero** — gradient orbs, particle network canvas, glassmorphism
- **Live typing code window** — Go/MeetIQ snippet types itself out with syntax highlighting
- **Stat cards** — 500k+ transactions/month, 70x AUM growth, 6+ years
- **Tech stack marquee** — infinite scrolling ticker
- **AI Work & Open Source sections** — MeetIQ, Google GenAI Toolbox contributions
- **Volt 🦊 — the anime pet mascot** — pops in on page load, gives a typed intro, speaks it aloud (voice in `assets/volt-intro.mp3`), reacts to clicks with quips, blinks/wags/floats idly

## Run locally

```bash
cd site
python3 -m http.server 8080
# open http://localhost:8080
```

> Note: the pet's voice plays on first user interaction (browser autoplay policy) — click anywhere and Volt will speak.

## Tech

Single self-contained `index.html` (inline CSS/JS) + one MP3 asset. No build step, no frameworks.
