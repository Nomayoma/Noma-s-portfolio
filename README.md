# Noma Edeki — Product Design Portfolio

Static portfolio site. Plain HTML, CSS and vanilla JavaScript — no build step, no dependencies, no API keys.

## Structure

```
index.html          Home
about.html          About
contact.html        Contact
movefinance.html    Case study 01 — MoveFinance
oloja.html          Case study 02 — Oloja
ai-assistant.html   Case study 03 — AI Customer Assistant
other-work.html     Other projects — Henna Place & Trian Energy
404.html            Not-found page
assets/images/      All site images
assets/files/       Downloadable resume (PDF)
```

## Run locally

Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

then visit http://localhost:8000.

## Deploy

**GitHub Pages:** push this folder to a repository, then Settings → Pages → Deploy from branch → `main` / root.
**Netlify / Vercel:** import the repository; no build command, publish directory is the root.

## Updating

- **Resume:** replace `assets/files/Noma-Edeki-Resume.pdf` (keep the same file name).
- **Images:** replace a file in `assets/images/` with one of the same name, or update the `src` in the relevant page.

## External services

- Fonts load from Google Fonts (Instrument Sans, Instrument Serif, Space Mono).
- No analytics, tracking, or third-party scripts.
