# FODMAP Scanner

A mobile-friendly web app for scanning food (by photo or description) and getting a FODMAP score, built to help people managing IBS/low-FODMAP diets make quicker decisions about what they can eat.

Built as a single-page installable web app (PWA) with an in-app chat assistant, using [Claude Code](https://claude.com/claude-code) for development.

## Features

- Scan a food photo or describe a food to get a FODMAP score and explanation
- Chat assistant for follow-up questions about specific foods
- Installable as a home-screen app (PWA) on iOS/Android
- Uses your own free [Google Gemini API key](https://aistudio.google.com/apikey) — no data sent to any backend server, no accounts, everything runs client-side

## Tech

- Vanilla HTML/CSS/JS, no build step or framework
- Google Gemini API (`gemini-2.5-flash-lite`) for food analysis
- PWA manifest for installability

## Running locally

```bash
python3 -m http.server 3456
```

Then open `http://localhost:3456` and add your free Gemini API key in Settings.
