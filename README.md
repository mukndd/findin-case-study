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

## Verified Audit Snapshot (2026-09-16)

- Typecheck: passed, no errors.
- Lint: passed (3 warnings, all in local `.tmp/` scratch scripts, not app code).
- Tests: 53 test files passed, 328 tests passed.
- Production build: passed, 29 app routes generated.
- Content catalog: 578 total candidates (282 prehistoric, 296 modern) - 80 published/playable, 493 review-required.
- Launch manifest: 60 species specifically reviewed and verified (`scripts/content/manifests/launch-60.json`), a curated subset of the 80 published rows.
- The previously documented Railway deployment URL returned HTTP 404 on `/`, `/daily`, `/practice`, and `/leaderboard` during verification, so no live demo is linked anywhere in this export.

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
