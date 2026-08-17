# Farzana Afroz — Portfolio

Personal portfolio website of **Farzana Afroz**, an oceanographer specializing in marine biogeochemistry, coastal habitat mapping, and blue carbon research. Built as a single-page site presenting academic background, research assistantships, publications, technical skills, and awards.

**Live site:** https:farzanabiva.github.io

## About

Farzana holds an MS in Oceanography from Shahjalal University of Science and Technology (SUST), Sylhet, and is an NST Fellowship recipient. Her research spans bioturbation and carbon cycling in mangrove ecosystems, oyster habitat relationships, microplastics pollution, and marine biodiversity mapping, using tools including R, Python, ArcGIS/QGIS, Delft3D, and SPSS.

## Design concept

The site is built around a single idea: scrolling the page is descending through the ocean. Each section is framed by a real oceanographic depth zone — Sunlight, Twilight, Midnight, Abyssal, and Hadal — moving from Farzana's introduction at the surface down to her contact details at the Challenger Deep. A fixed depth gauge tracks scroll position and displays the current zone in real time.

- **Palette:** deep-ocean navy through near-black, with a bioluminescent cyan accent and warm amber for highlights
- **Type:** Newsreader (display), IBM Plex Sans (body), IBM Plex Mono (data/coordinates)
- **Structure:** single `index.html` file — no build step, no dependencies

## Sections

- About
- Education (MS &amp; BSc in Oceanography, HSC, SSC)
- Research Assistantship
- Thesis &amp; Conference Presentations
- Technical Skills
- Awards &amp; Training
- Outreach &amp; Extracurricular
- References
- Contact

## Tech stack

- Plain HTML, CSS, and vanilla JavaScript (no frameworks, no build tools)
- Fonts loaded from Google Fonts
- Deployed via GitHub Pages

## Running locally

Clone the repo and open `index.html` directly in a browser, or serve it locally:

```bash
git clone https://github.com/<username>/<repo-name>.git
cd <repo-name>
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment (GitHub Pages)

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and `/ (root)` folder.
4. Save — the site will be live at `https://<username>.github.io/<repo-name>/` (or `https://<username>.github.io/` if the repo is named `<username>.github.io`).

## Contact

- Email: bivafarzana12345@gmail.com
- LinkedIn: [linkedin.com/in/farzana-afroz-biva-38b489340](https://linkedin.com/in/farzana-afroz-biva-38b489340)

## License

© 2026 Farzana Afroz. All rights reserved. This repository contains personal portfolio content and is not licensed for reuse.
