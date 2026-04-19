# Design System

Artefacts in this repo share one type system so the set reads as a family, while each keeps its own accent colour and light/dark mood by theme. Think of the gallery as a magazine: one house style, but every feature spread gets its own art direction.

## Type system

| Role | Typeface |
|------|----------|
| Display serif | **Fraunces** |
| Body | **Inter** |
| Mono / labels | **JetBrains Mono** |

Loaded from Google Fonts. `font-optical-sizing: auto` lets Fraunces adapt across display and body sizes.

## Shared grammar

What stays consistent across every artefact:

- Mono, uppercase, letter-spaced "kicker" labels above section titles
- Numbered sections and cards
- Hairline (1px) borders and dividers
- `fadeUp` entrance animation on scroll

## Varied by theme

What changes per artefact — accent colour, light/dark mood, and component density — chosen by domain:

| Artefact | Mood | Accent |
|----------|------|--------|
| Berkshire 13F | Dark, financial | Gold |
| US National Defense Strategy | Dark, steel | Steel blue |
| ASGS explainer | Dark, technical | Teal / azure |
| Web Scraping Field Guide | Light, editorial | Warm paper |
| Gallery (`artefacts/index.html`) | Light, editorial | Crimson |

## Conventions

- One self-contained `.html` per artefact — no build step, no JS dependencies beyond Google Fonts.
- Relative links only, so the folders stay portable on GitHub Pages.
- `index.html` is the entry page at each level; artefacts link back to the gallery via a "← Artefact gallery" link where present.
