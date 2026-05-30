# CLAUDE.md

Personal academic website for Niklas Leinz (PhD student, TUM, industrial PhD with Volkswagen Group).
Hosted via GitHub Pages.

## Structure
- `index.html` — the entire site (header/bio, Publications, News, Teaching, footer). Inline `<script>` handles dark-mode toggle and the auto-updated year/date.
- `assets/s.css` — all styles, single minified line. Edit carefully; theme colors live in the `:root` / `html.dark` custom properties.
- `assets/favicon.svg` — "NL" monogram, adapts to light/dark.
- `images/`, `cv/` — headshot and CV PDF.

## Conventions
- No build step. Edits to `index.html` / `assets/` are deployed directly by GitHub Pages on push.
- External links use `target="_blank" rel="noopener noreferrer"`.
- Do not use em dashes or en dashes in the page copy (use commas or "to").
- Keep research descriptions broad; do not expose specific methods/architectures.
- `index.html.bak` and `backup.html` are local backups, not committed.

## After making changes
After editing any file in this project, always include this link at the end of your reply so I can open the page locally:

file:///Users/niklasleinz/dev/niklas-leinz.github.io/index.html
