# Ventorme landing — Hacknext 2026

Our team's landing page for the Hacknext 2026 hackathon, case "Почему не регистрируются" by Ventorme.

Team number: `team-NNN` (replace NNN once with our number from the official list, 3 digits, e.g. `team-017`).

## Hard rules

- Every registration button links to exactly `https://ventorme.ai/register?utm_source=hacknext&utm_campaign=team-NNN`. A wrong number sends our registrations to another team.
- The page clearly says it is Ventorme. No sign-up form and no contact collection: Ventorme counts registrations by our link.
- Say only what is true about Ventorme (check ventorme.ai). If unsure, leave a visible `TODO` instead of inventing.
- This repo is public. Never commit case materials (data tables, the case page, our analysis or presentation): rule 13.5 of the regulations forbids publishing them.
- No paid ads, bots, fake accounts or rewards for sign-ups. Any of these disqualifies the team.

## Tech

- One page: `index.html` in the repo root, inline CSS and JS, no frameworks, no build step. Images: `og-image.png` (1200×630) and inline SVG only.
- Mobile first. Main screen is 360×640: the main button is visible without scrolling, body text is at least 16px, tap targets are at least 44px, no horizontal scroll, no cookie banner, no hamburger menu.
- All visible text is in Russian. The page loads fast on mobile data.
- Deploy: GitHub Pages from `main` (root). Merging into `main` publishes the site.

## How to work with us

We must explain every part of this page to the jury ourselves, so:

- Before a big change, show a 3-line plan. Change only what we asked for.
- After each change, explain in simple Russian what changed and why (5 lines at most).
- Add one line to `AI_LOG.md`: `date | who | what Claude did | what we checked ourselves`.
- Before pushing, check that every registration link equals the team link and take a 360×640 screenshot.
