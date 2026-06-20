# StyleWhiz AI — Legal Pages

A minimal static-HTML microsite hosting the legal documents for the StyleWhiz AI iOS app: a landing index page, Privacy Policy, and Terms of Use. No build step, no framework, no dependencies.

## Tech Stack

- **Pure static HTML/CSS** — three standalone HTML files
- No JavaScript, no build tooling, no package manager

## Setup

No setup required. Open files directly in a browser or serve with any static file server.

## Build / Run / Test

```bash
# Serve locally (any static server works)
python3 -m http.server 8080
# then open http://localhost:8080
```

## Project Structure

```
index.html      Landing page — links to Privacy Policy and Terms of Use
privacy.html    Privacy Policy for StyleWhiz AI
terms.html      Terms of Use for StyleWhiz AI
```

## Architecture & Key Files

- `index.html` — brand landing page with links to the two legal documents and a support email (`deonmenezescodes@gmail.com`).
- `privacy.html` — full Privacy Policy.
- `terms.html` — full Terms of Use.
- Inline CSS only; no external stylesheets or scripts.

## Conventions & Notes for Agents

- This repo is intentionally minimal — three HTML files, nothing else.
- Do not add a build system, framework, or package manager unless explicitly requested.
- Keep legal text accurate to the actual StyleWhiz AI app behavior. Do not generate placeholder or generic legal text — any changes to policy content require human review.
- The support email in `index.html` (`deonmenezescodes@gmail.com`) is the real contact address; do not change it.
