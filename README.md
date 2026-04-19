# HTML Tools

A collection of self-contained, single-file HTML tools and artefacts — published with GitHub Pages.

Each file is one `.html` with no build step and no dependencies beyond Google Fonts. Open any file directly in a browser, or host the repo on GitHub Pages.

## Live site

- **Landing page:** https://ceciliaw888.github.io/html-tools/
- **Artefact gallery:** https://ceciliaw888.github.io/html-tools/artefacts/

## Structure

| Path | What it is |
|------|------------|
| [`index.html`](index.html) | Landing page — links to every tool and the gallery |
| [`tools/motion-lab/`](tools/motion-lab/) | Motion Lab — an interactive motion-study tool |
| [`artefacts/`](artefacts/) | Artefact gallery — see its [README](artefacts/README.md) |

## The artefact gallery

The gallery lives in [`artefacts/`](artefacts/); its `index.html` links out to every artefact (Berkshire 13F, US National Defense Strategy, ASGS geography explainer, Web Scraping Field Guide Ed II). Full index is in [`artefacts/README.md`](artefacts/README.md).

## Design

All tools and artefacts share one type system and a common component grammar, with per-theme accent and mood. See [`DESIGN.md`](DESIGN.md).

## Local preview

```bash
# from the repo root
python3 -m http.server 8000
# landing page:   http://localhost:8000/
# gallery:        http://localhost:8000/artefacts/
```
