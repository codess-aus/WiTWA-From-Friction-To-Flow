# From Friction to Flow

Workshop companion site for the **Women in Tech WA 2026** keynote, *From Friction to Flow: the confidence to build what's next*.

Live site: https://codess-aus.github.io/WiTWA-From-Friction-To-Flow/

The original talk track and speaker notes are kept in [notes/talk-track.md](notes/talk-track.md).

## Run locally

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

## Publish

Pushing to `main` runs `.github/workflows/pages.yml`, which builds with `mkdocs build --strict` and deploys to GitHub Pages. In the repo, set **Settings > Pages > Source** to **GitHub Actions** once.

## Credits

Font: [Mona Sans](https://github.com/github/mona-sans), SIL Open Font License 1.1 (see `docs/fonts/OFL-LICENSE.txt`).
