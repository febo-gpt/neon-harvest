# Neon Harvest

Marketing site for **Neon Harvest** — a custom marketing intelligence dashboard service for agencies and ecommerce teams.

## Project Structure

```
neon-harvest/
└── neon-harvest.html   # Single-page marketing site (all-in-one: HTML, CSS, JS)
```

## Stack

- **Pure HTML/CSS/JS** — no build tools, no dependencies
- **Fonts** (via Google Fonts): Syne (headings), Rajdhani (labels/monospace), DM Sans (body)
- **JavaScript**: Minimal — IntersectionObserver for scroll-reveal animations

## Page Sections

| Section | ID | Description |
|---|---|---|
| Nav | — | Sticky nav with links and "Get a Demo" CTA |
| Hero | — | Headline, subheadline, two CTAs, dashboard mockup |
| The Problem | `#problem` | Pain point grid (3 cards) |
| Features | `#features` | What you get (5 feature cards) |
| Who It's For | `#who` | Agencies vs. ecommerce (2-column) |
| CTA / Contact | `#contact` | Email capture + demo request |
| Footer | — | Logo + copyright |

## Design Tokens

| Token | Value |
|---|---|
| Background | `#080a0f` |
| Surface | `#0d1117` |
| Accent green | `#00ff88` |
| Accent cyan | `#00e5ff` |
| Muted text | `#7a8499` |
| Foreground | `#e8edf5` |

## Local Dev

```bash
python3 -m http.server 8080
```

Then open: [http://localhost:8080/neon-harvest.html](http://localhost:8080/neon-harvest.html)
