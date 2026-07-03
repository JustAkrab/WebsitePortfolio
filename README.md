# Reda Akrab — Portfolio (Live Site)

The live, deployed source for [redaakrab.org](https://redaakrab.org), Reda Akrab's personal portfolio site, hosted via GitHub Pages and built on the "Highlights" template by HTML5 UP.

## Overview

A clean, scroll-driven, fully responsive one-pager introducing Reda Akrab: a Computer Science senior at the City University of New York with experience as a software developer intern in Japan, game development passion projects, and hackathon experience. The site links out to social profiles and a resume.

This repository is a GitHub Pages site — because it's named `justakrab.github.io`, GitHub automatically serves its contents at that URL (and at the custom domain configured below).

## Live Site

- **Custom domain:** [redaakrab.org](https://redaakrab.org) (configured via the `CNAME` file)
- **GitHub Pages URL:** [justakrab.github.io](https://justakrab.github.io)

## Sections

- **Header** — name, tagline, and a "Begin" call-to-action that scrolls into the page.
- **About Me** — background as a CS senior at CUNY, software developer internship in Japan, game dev and hackathon experience.
- **Stuff I Do** — an icon grid highlighting game development (Unreal Engine), learning Japanese, coding skills, and community involvement.
- **One More Thing** — personal interests outside of computer science: travel, basketball, and swimming.
- **Footer** — links to YouTube, LinkedIn, Instagram, GitHub, and a resume.

## Built With

- [Highlights by HTML5 UP](https://html5up.net/highlights) — free HTML/CSS/JS template (CCA 3.0 license)
- HTML5, CSS3/SCSS, vanilla JavaScript
- jQuery, [Scrollex](https://github.com/ajlkn/jquery.scrollex) (scroll-triggered animations), Responsive Tools
- Font Awesome icons

## Project Structure

```
├── index.html         # Page content — must live at repo root for GitHub Pages
├── CNAME                # Custom domain configuration (redaakrab.org)
├── LICENSE.txt            # Template license (CC BY 3.0)
├── assets/
│   ├── css/                 # Compiled CSS (main.css) and SCSS source
│   └── js/                   # jQuery, Scrollex, breakpoints, and other template scripts
└── images/                     # Profile photo and other page images
```

## Running Locally

This is a static site with no build step required.

```bash
# open index.html directly in a browser, or serve it locally:
npx serve .
```

## Deployment

This repo deploys automatically via **GitHub Pages** on every push to `main` (Settings → Pages in the repo). The `CNAME` file points the custom domain `redaakrab.org` at this GitHub Pages deployment — if the domain ever changes, update or remove that file and adjust the DNS records accordingly.

## Customization

- Edit the copy directly in `index.html` (About Me, Stuff I Do, One More Thing sections).
- Replace images in `images/` to update the profile and section photos.
- Update the footer links (YouTube, LinkedIn, Instagram, GitHub, resume) as needed.

## Attribution

Template: ["Highlights" by HTML5 UP](https://html5up.net/highlights) (AJ / @ajlkn), licensed under [Creative Commons Attribution 3.0](https://creativecommons.org/licenses/by/3.0/) (see `LICENSE.txt`). Icons by [Font Awesome](https://fontawesome.com). Scroll effects via [jquery.scrollex](https://github.com/ajlkn/jquery.scrollex).
