# AI Lumière · Platform (demo)

Static demo of the AI Lumière interface. One page, no server.

## Contents
- `index.html` — the whole app in one file.
- `assets/` — logos, partner logos and style previews. The app loads them at runtime, so keep the folder next to `index.html`.

## Publish on GitHub Pages
1. Upload `index.html` and the `assets` folder to the root of the repository (branch `main`).
2. Settings → Pages → Source: *Deploy from a branch* → Branch: `main` / root → Save.
3. After 1–2 minutes the site is live at `https://<account>.github.io/<repository>/`.

## What works in the demo
- Home page, pricing, sample project (SEE A SAMPLE PROJECT) with all sections.
- Image generation (Nano Banana / OpenAI / FLUX) and voice (ElevenLabs) if the visitor enters their own key in Settings and switches to Live.
- Export: PDF, PPTX, ZIP.

## What does not work yet
- Analysis of your own screenplay: it needs the AI Lumière server. The demo shows "AI analysis is not available".
- Accounts, payment, shared storage: projects live only in the visitor's browser.
- API keys are entered by each visitor and stored in their browser. Do not publish a page with your keys filled in.
