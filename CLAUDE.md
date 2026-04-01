# ~/src/thoughts

A place for standalone pages, guides, and one-off projects.

---

## python-guide.html — Ari's Python Dev Setup Guide

### What it is
A self-contained single-page HTML guide for Ari learning Python development. No build step — open directly in a browser or serve as-is via GitHub Pages.

### Content
- **VS Code setup** — see CLAUDE.local.md for device details
- **GitHub sync workflow** — commit, push, pull via VS Code's Source Control panel (no terminal needed)
- **Framework comparison cards** — tkinter, CustomTkinter, Pygame Zero, Pygame (with rating bars and trading-card design)
- **First project: GUI Calculator** — full working CustomTkinter calculator (`calculator.py`) with extension ideas
- **Starter code** — working examples for all four frameworks, syntax-highlighted
- **Decision flowchart** — SVG tree: "making a game or an app?" → right tool
- **Tips** — commit often, read errors top-to-bottom, use print() to debug, etc.
- **Linked resources** — Making Games with Pygame (free PDF), programarcadegames.com, Pygame Zero docs, Real Python, Clear Code YouTube, Stack Overflow

### Hosting plan: GitHub Pages
1. Create a new **public** GitHub repo (e.g. `ari-python-guide`)
2. Rename `python-guide.html` → `index.html` and push it
3. Repo **Settings → Pages → Deploy from branch** (main, / root)
4. GitHub publishes at `https://<username>.github.io/ari-python-guide`

### Next steps (pick up here next session)
- [ ] Create GitHub repo
- [ ] Rename file to `index.html`, push
- [ ] Enable GitHub Pages
- [ ] Share URL with Ari
