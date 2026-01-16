# LeeDaud's Homepage

Personal homepage serving as the entry point and navigation hub for my digital presence.

**Live site:** [licheng.website](https://licheng.website)

## Structure

```
licheng.website (Main)
├── Hero - Identity & tagline
├── Now - Current focus (time-sensitive)
├── Featured Projects - 3 selected works
├── Recent Notes - 3 latest writings
├── Navigation - Links to subsites
└── Footer - Contact & quote

notes.licheng.website (Subsite)
└── Digital garden with all projects & notes
```

## Tech Stack

- Pure HTML/CSS/JS (no framework)
- Data-driven via `data/home.json`
- Dark/Light theme toggle
- Responsive design

## File Structure

```
├── index.html          # Homepage
├── about.html          # About page
├── styles.css          # All styles
├── script.js           # Theme toggle & data rendering
├── data/
│   └── home.json       # Content configuration
├── images/
│   ├── avatar.jpg
│   └── favicon-*.png
└── favicon.ico
```

## Update Content

Edit `data/home.json` to update:

- `now.summary` / `now.updated` - Current status
- `featuredProjects` - Featured project cards
- `recentNotes` - Recent note entries
- `contact` - Contact information
- `footer` - Copyright & quote

No need to modify HTML/CSS/JS for content updates.

## Local Development

Simply open `index.html` in a browser, or use a local server:

```bash
# Python
python -m http.server 8000

# Node.js
npx serve
```

## License

MIT License - See [LICENSE](LICENSE) for details.
