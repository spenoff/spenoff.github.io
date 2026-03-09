# AGENTS.md

## Project Overview

Personal portfolio website for Spencer Nisonoff — Software Engineer and Game Programmer. Hosted on GitHub Pages at [spenoff.github.io](https://spenoff.github.io).

## Tech Stack

- Static HTML/CSS/JS site (no build step, no package manager)
- Based on the "Dimension" template by [HTML5 UP](https://html5up.net) (CCA 3.0 license)
- jQuery 3.7.1 (vendored in `assets/js/`)
- SASS source in `assets/sass/`, compiled CSS in `assets/css/`

## Project Structure

```
index.html          # Main (and only) page — all sections are single-page articles
bandaid/            # Subpage
assets/
  css/              # Compiled stylesheets
  sass/             # SASS source files
  js/               # Vendored JS libraries (jQuery, breakpoints, browser, util, main)
  fonts/            # Web fonts
images/             # All site images (photos, logos, favicons)
```

## Sections in index.html

The site is a single-page app with modal-style articles:
- `#aboutme` — Bio and introduction
- `#cs` — Computer Science background, projects, hackathons, internships
- `#music` — Drumming, marching band, rock band
- `#whyme` — Personal qualities and story
- `#contactme` — Contact info (email, LinkedIn)
