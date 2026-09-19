# Kipot — Personal Portfolio

A cinematic, editorial-style personal portfolio built as a lightweight static site.

## Concept

**Multiple perspectives, one practice.**

The site treats the portfolio as a working map rather than a conventional CV, moving through five lenses:

- Law
- Digital
- Markets
- Literature
- Culture

## Stack

- Semantic HTML
- Modern CSS
- Vanilla JavaScript
- Google Fonts (Manrope, DM Mono, Playfair Display)

No framework or build step is required.

## Run locally

Because the portfolio loads the profile image from the repository, serve it through a local HTTP server:

```bash
python -m http.server 5500
```

Then open:

```
http://localhost:5500
```

## GitHub Pages

The site is already structured for static hosting. GitHub Pages can publish the repository root directly.

1. Open **Settings → Pages**.
2. Choose **Deploy from a branch**.
3. Select **main** and **/(root)**.
4. Save.

## Editing

- Profile photo: `assets/kipot.jpg`
- Main content: `index.html`
- Visual system: `styles.css`
- Interactions: `script.js`

