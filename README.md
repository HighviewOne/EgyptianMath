<div align="center">

<!-- SVG pyramid banner -->
<img src="https://raw.githubusercontent.com/HighviewOne/EgyptianMath/main/banner.svg" alt="Temple of Numbers" width="720" />

# Temple of Numbers

**Ancient Egyptian culture meets middle-school math — an interactive learning site for curious 13-year-olds.**

[![GitHub Pages](https://img.shields.io/badge/Live%20Site-GitHub%20Pages-gold?style=for-the-badge&logo=github&logoColor=black)](https://highviewone.github.io/EgyptianMath/)
[![Single File](https://img.shields.io/badge/Stack-HTML%20%2F%20CSS%20%2F%20JS-lapis?style=for-the-badge&color=1B3F8A)](index.html)
[![No Dependencies](https://img.shields.io/badge/Dependencies-None-2ABFBF?style=for-the-badge&color=2ABFBF)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-C9A227?style=for-the-badge)](LICENSE)

[**→ Open the site**](https://highviewone.github.io/EgyptianMath/)

</div>

---

## What is this?

Temple of Numbers is a **single-page, zero-dependency** educational website that teaches core middle-school math concepts through the lens of ancient Egyptian history and culture. No install, no login — just open it in a browser.

## Features

| Section | What you'll learn | Interactive tools |
|---|---|---|
| 📜 **Introduction** | Story of Egyptian mathematics | — |
| 𓏤 **Numbers** | Hieroglyphic numeral system | Converter + Speed Quiz |
| 𓂀 **Fractions** | Eye of Horus unit fractions | — |
| 📐 **Geometry** | Pyramid formulas (area, volume, seked) | Pyramid Builder |
| 𓂓 **Algebra** | Rhind Papyrus "aha" problems | — |
| 🔢 **Patterns** | Doubling sequences | Multiplication Trainer |
| 🏆 **Grand Quiz** | All five topics, 15 questions | Rank title at end |

### Highlights

- **Hieroglyph Number Converter** — type any number up to 9,999,999 and see it written in Egyptian hieroglyphs (try 1,000,000 to meet the god Heh 𓁨)
- **Hieroglyph Speed Quiz** — read hieroglyphs, type the Arabic numeral; builds a streak counter
- **Interactive Pyramid Builder** — drag sliders for base and height; canvas redraws live with area, volume, slant height, and seked
- **Egyptian Multiplication Trainer** — build the doubling table, tap the rows that sum to the multiplier, and read off the answer; tracks solved count and streak
- **15 practice problems** (3 per lesson) with instant feedback and "☥ Show me how →" step-by-step solutions
- **Saved progress** — your practice answers and the nav-tab badge (lit once every problem in a lesson is answered) are saved in `localStorage`; a "↺ Reset these problems" button under each lesson's practice lets you try again
- **Grand Quiz** — 15-question final challenge (3 per lesson, answer order shuffled each time) with an Egyptian rank title at the end
- **Shareable lesson links** — every lesson has its own URL (e.g. [`#geometry`](https://highviewone.github.io/EgyptianMath/#geometry)), so teachers can link straight to it and the browser's Back button moves between lessons
- **Accessible** — feedback is announced to screen readers, text meets WCAG contrast, and animations stop when the device's *reduce motion* setting is on (the starfield also pauses whenever it's scrolled off-screen)

## Tech stack

| Layer | Choice |
|---|---|
| Structure | HTML5 |
| Style | CSS3 (custom properties, grid, canvas) |
| Logic | Vanilla JavaScript (ES2020) |
| Fonts | Cinzel + Crimson Text + Noto Sans Egyptian Hieroglyphs via Google Fonts (so hieroglyphs render on every device) |
| Deploy | GitHub Pages (main branch root) |

No frameworks. No build step. No Node. The whole site is one file: [`index.html`](index.html).

## Running locally

```bash
git clone https://github.com/HighviewOne/EgyptianMath.git
cd EgyptianMath
# Open index.html in any modern browser — no server needed
open index.html          # macOS
xdg-open index.html      # Linux
start index.html         # Windows
```

## Contributing

Found a bug or have an idea for a new lesson? Open an issue or a pull request — templates are provided in `.github/`.

## License

[MIT](LICENSE) — feel free to fork, adapt, and share.

---

<div align="center">
<sub>Built with ☥ and JavaScript · Egyptian color palette: gold #C9A227 · lapis #1B3F8A · turquoise #2ABFBF · papyrus #EDE3C0</sub>
</div>
