# Lucid Terrors — Teaser Website

A teaser landing page for *Lucid Terrors: An Anthology of Short Stories Exploring Cosmic Horror, Science-Fiction, and Fantasy*, currently in progress.

## Overview

This is a single-file static website built to collect early interest and email signups ahead of the anthology's release. It requires no framework, build step, or dependencies — just two files served from the same directory.

## Files

| File | Description |
|------|-------------|
| `index.html` | The entire site — HTML, CSS, and JS in one file |
| `lt-graphic.png` | Hero background image — must be in the same folder as `index.html` |

## Features

- Full-screen hero with the anthology's key art
- Genre overview section (Cosmic Horror, Science Fiction, Fantasy)
- Atmospheric teaser copy
- Author bio placeholder
- Email signup form connected to Google Forms
- Scroll-reveal animations
- Fully responsive (mobile-friendly)

## Email Signups

Submissions are sent to a Google Form and stored in the linked Google Sheet. To view collected emails:

1. Open the [Google Form](https://docs.google.com/forms/d/e/1FAIpQLSfPq34lp6ijP1t6fVBwzPvKeiZXlD8689a_4xy7gSP4ssA-gg/viewform)
2. Click the **Responses** tab
3. Or open the linked Google Sheet if you've set one up

## Deployment

This is a plain static site — no build process needed. You can host it anywhere that serves static files:

- **GitHub Pages** — push to a repo, enable Pages in Settings → Pages → set source to `main` branch / root
- **Netlify** — drag and drop the folder at [netlify.com/drop](https://netlify.com/drop)
- **Vercel** — connect the GitHub repo and it deploys automatically

## Customization

Things you'll likely want to update as the book progresses:

- **Author bio** — find the `#about` section and replace the placeholder text (and optionally add a real photo)
- **Story previews** — a stories section can be added back in once titles and excerpts are ready
- **Release date** — update the hero tagline and add a countdown timer when a date is set
- **Fonts** — loaded from Google Fonts (Cinzel Decorative, Cinzel, Crimson Pro); requires an internet connection to render correctly

## Local Preview

No server required for most features. Just open `index.html` in a browser directly. Note that the Google Forms submission uses `fetch`, which may be blocked in some browsers when opening a local file — this will work correctly once deployed.

---

*Anthology in progress. All rights reserved.*
