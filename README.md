# getgaruda.in

The website for [Garuda](https://github.com/myshra777-ai/garuda), live at **https://getgaruda.in**.

Garuda checks every change your AI coding assistant makes against your system and your team's rules, before and after the edit. The engine, docs and issues live in the main repository: [myshra777-ai/garuda](https://github.com/myshra777-ai/garuda).

## What's here

| Path | What it is |
| :--- | :--- |
| `index.html` | The whole site: one self-contained page (styles and script inline) |
| `img/` | Logo mark, favicon and the social preview image |
| `CNAME` | Custom domain for GitHub Pages. Don't delete it |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

There is no build step. GitHub Pages serves the `main` branch as it is.

## Changing the site

1. Edit `index.html`.
2. Open it in a browser to check it.
3. Commit and push to `main`. The live site updates in one to three minutes.

Two settings near the top of the page's `<script>` control the contact buttons:

- `CALL_URL`: a booking link (Cal.com or Google Calendar) for every "Book a demo" button. Empty sends an email instead.
- `WHATSAPP`: a WhatsApp business number, digits only, with country code. Empty makes "Ask us" open LinkedIn.

## Contact

- Questions and demos: contact@getgaruda.in
- Help using Garuda: support@getgaruda.in
- Security reports: see [SECURITY.md](https://github.com/myshra777-ai/garuda/blob/main/SECURITY.md) in the main repository

Site content © 2026 Garuda. The Garuda engine is open source under Apache-2.0.
