# The Shelf — Novel Reader

A minimal, iPad-optimised novel reader hosted via GitHub Pages.

## Structure

```
/
├── index.html                        ← Library (main page)
├── novels/
│   └── the-unknown-entity.html       ← Novel 1
└── README.md
```

## Adding a New Novel

1. Create a new file in `novels/` — e.g. `novels/my-new-novel.html`
2. Copy the structure from `the-unknown-entity.html` and update:
   - The `<title>` tag
   - The hero section (title, genre, tagline)
   - The table of contents links
   - The chapter sections
3. Add a card in `index.html` inside the `.novel-grid` div, following the same pattern as the existing card.

## Hosting on GitHub Pages

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Set Source to **Deploy from a branch**, branch: `main`, folder: `/ (root)`
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/`

## Fonts Used

- Cinzel (headings, labels)
- Cormorant Garamond (chapter titles, display)
- EB Garamond (body prose)

All loaded from Google Fonts — no local files needed.
