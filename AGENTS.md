# Repository Guidelines

## Project Structure & Purpose
- Source of truth: `README.md` — contains the only up‑to‑date information (address, links, and ZIP code).
- Archive: `_/` — legacy static site kept for reference only. Do not modify, rebuild, or deploy it.
- Misc: `.idea/` is editor metadata and not required for contributions.

## Build, Test, and Development Commands
- No build or runtime. Editing `README.md` is the primary task.
- Preview Markdown: rely on your Git host’s renderer or a local editor preview.
- Find the ZIP code quickly: `grep -n "197341" README.md`.

## Coding Style & Naming Conventions
- Markdown only: clear headings, concise bullets, and short paragraphs.
- Language: keep existing Russian text; add English only when it improves clarity.
- Links: prefer `https` where available; keep URLs readable and verified.
- Formatting: wrap lines at a reasonable length and avoid trailing whitespace.

## Testing Guidelines
- Sanity‑check: ensure ZIP code and address lines in `README.md` are correct and visible.
- Link check: click each README link and confirm it opens; replace dead links or annotate as legacy.
- No automated tests; keep changes minimal and obvious.

## Commit & Pull Request Guidelines
- Commits: small, focused, imperative. Suggested prefix: `docs:` for README edits.
  - Example: `docs: clarify ZIP code 197341 in header`.
- PRs: include a one‑paragraph summary, list of changed lines/sections, and any updated links.
- Do not include changes to `_/` unless explicitly requested for archival curation.

## Deprecation Note for `_/`
- The `_/` tree is an outdated site snapshot. Treat as read‑only archive; updates are not part of normal maintenance.
