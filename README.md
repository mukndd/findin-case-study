# Findin Public Case Study Export

This folder is a standalone, recruiter-safe showcase package for the private Findin project. It contains public-facing HTML, CSS, one screenshot captured from the current product, a high-level architecture diagram, and a PDF-ready recruiter version.

## Contents

- `index.html` - responsive public case study.
- `styles.css` - standalone styling for the case study.
- `assets/screenshots/daily-gameplay.png` - real local Daily screen, captured from the running app.
- `assets/diagrams/architecture.svg` - public-safe architecture diagram.
- `assets/logo/` - public brand assets copied from the app's public assets.
- `pdf/case-study.html` - PDF-ready one-page recruiter version.
- `pdf/case-study.pdf` - generated PDF.

## Verified Audit Snapshot

Refreshed 2026-10-02 from the project's latest passing CI run on its default branch (29 September 2026) and its launch manifest:

- Typecheck, lint, tests, production build and a production-dependency audit: all passed in CI.
- Tests: 350 passed across 58 test files.
- Production build: 31 static pages generated.
- Launch manifest: 60 species specifically reviewed and verified (`scripts/content/manifests/launch-60.json`).
- Live demo: `https://findin.world` returned 200 for `/`, `/daily`, `/practice` and `/leaderboard` on 2026-10-02.

Not refreshed, kept as a dated snapshot (2026-09-16): the content catalogue counts of 578 total candidates (282 prehistoric, 296 modern), 80 published/playable and 493 review-required. Refreshing them needs a read of the production content database.

## Public-Safety Notes

This export intentionally excludes:

- application source code
- private repository links or remotes
- credential material, keys, connection strings, or account identifiers
- internal hostnames and private infrastructure identifiers
- the `/admin/content` routes that exist in the app
- screenshots of dashboards, consoles, errors, or local browser chrome
- the second local screenshot that showed a generated guest username in its top bar
- internal incidents and recovery details

Personal context (role, motivation, collaboration) is stated exactly as confirmed by the project owner in the source repository's own documentation; anything not confirmed stays out rather than being guessed at.
