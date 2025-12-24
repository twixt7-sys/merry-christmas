# Christmas App 2025

A small, warm single-page Christmas card experience with ambient visuals, snow, aurora effects, and a hold-to-open gift interaction that reveals a heartfelt message and music.

## Live Preview

Open `index.html` in your browser or serve the folder with a local static server.

Quick preview (recommended):

```powershell
# from repo root
python -m http.server 8000
# then open http://localhost:8000 in your browser
```

## Features
- Hold-to-open gift interaction with countdown
- Ambient snow, stars, aurora and particle effects
- Soft background music with a mobile-friendly volume prompt
- Fully responsive layout and accessible controls

## Layout & scrolling
This version limits horizontal scrolling and only allows vertical scrolling when content grows (e.g. long message text). If you see any horizontal scroll, try clearing browser cache or resize the window.

## Screenshots & Templates
See `screenshots/README.md` for recommended screenshot sizes, naming conventions, and a convenient issue template for submitting screenshots.

## Development notes
- Source files for the card: `christmas-card/style.css`, `christmas-card/script.js`, `index.html`.
- Music file: `christmas-card/song.mp3` (not included in the repo by default)

### Accessibility & mobile
- The overlay handles blocked autoplay gracefully and enables users to tap to enable sound.
- Visuals are disabled by default on older/smaller devices to preserve performance.

## Contributing
Feel free to open an issue or submit a PR. Use the screenshot issue template in `.github/ISSUE_TEMPLATE` to attach images.

---

Made with care 🎄 — happy holidays!

