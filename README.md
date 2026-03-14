# erinyabrams.github.io

Personal portfolio site. Live at [erinabrams.com](https://erinabrams.com).

## Tech

- Static HTML/CSS/JS
- Hosted on GitHub Pages
- Contact form via [Formspree](https://formspree.io)

## Workflow

- **`main`** — production branch. Pushes here deploy to GitHub Pages.
- For new work: create a feature branch, make changes, then merge into `main`:

```bash
git checkout -b feature/your-feature-name
# make changes, commit
git add .
git commit -m "Describe your change"
git push origin feature/your-feature-name
```

Then open a Pull Request on GitHub to merge into `main`, or merge locally:

```bash
git checkout main
git merge feature/your-feature-name
git push origin main
```

- For small, quick fixes you can still commit directly to `main` if you prefer.
