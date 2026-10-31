# STATUS — AI Safety Basics guide

## What was built

A beginner manual on AI safety basics plus a static HTML site, published by Asdale Dynamics, LLC.

### Files

- `README.md` — project overview, topics, how to use, about Asdale Dynamics, LLC, license
- `LICENSE` — MIT License, copyright line: `Copyright (c) 2026 Asdale Dynamics, LLC`
- `docs/manual.md` — full manual: data privacy, spotting scams and deepfakes, what never to paste into chatbots
- `docs/checklists.md` — printable step-by-step checklists (before you paste, when you receive a surprise, after a session, plus the never-paste short list)
- `docs/README.md` — documentation overview
- `site/index.html` — static HTML site mirroring the manual, opens in any browser

### Topics covered

1. Data privacy — keep your info yours (good habits, sensitive data, local AI)
2. Scams and deepfakes — common scam patterns, deepfake spotting, what to do if scammed
3. What never to paste into chatbots (the short list, fake-example trick, when in doubt leave it out)
4. Step-by-step checklists (A, B, C)

### Style

Plain English, step by step, warm, never condescending, no fear-mongering, education only. Credits Asdale Dynamics, LLC throughout. No secrets, API keys, or personal data in any file.

## How to run it

- Read the manual: open `docs/manual.md` in any Markdown viewer or text editor.
- Open the site: open `site/index.html` in any web browser. No build step, no server, no internet required.
- Print checklists: `docs/checklists.md` is printable.

## Verification results

- Git initialized and committed as existing identity (`Dylan Asdale <dylanasdale@users.noreply.github.com>`), one plain commit message, no Co-authored-by trailers. No push, no remote.
- `LICENSE` copyright line verified exact: `Copyright (c) 2026 Asdale Dynamics, LLC` (line 3).
- `README.md` credits Asdale Dynamics, LLC.
- HTML structure checked with Python `html.parser` — only flagged void elements (`<meta>`, `<br>`), which are valid self-closing HTML; no real mismatches.
- Secret scan: no API keys, passwords, tokens, or personal data found. Matches for "password"/"secret" are educational words in context (e.g., "Passwords and login credentials").
- No `.github/workflows` files added.

## Known gaps

- No automated test suite (static docs/HTML only; nothing to compile or run tests against).
- HTML not run through an external validator beyond the local parser check.
- `tests/` directory exists but is empty (no tests applicable to static content).
- Site is a single-page HTML file; no separate pages per chapter or navigation beyond anchor links.
