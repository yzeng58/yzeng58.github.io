# yzeng58.github.io — Personal Homepage

## Overview
Yuchen Zeng's personal homepage / academic CV website.

## Tech Stack
- Single static `index.html` with inline CSS, inline SVG icons, and a small inline script (theme toggle, copy email, section highlight)
- Geist / Geist Mono from Google Fonts
- Layout modeled on Wonjun Kang's homepage (https://wonjunn.github.io/)

## Structure
- `index.html` — Main page
- `images/` — Profile photo (`me.JPG`, 3:4) and icon assets
- `favicon_io/`, `favicon.ico` — Site favicon
- `CV.pdf` — Linked from the profile panel

## Deployment
- GitHub Pages (public repo)
- URL: https://yzeng58.github.io/

## Notes
- Public repo — no sensitive info
- Branch: master
- Visual style target: Apple-like minimalism with subtle hairline dividers, restrained spacing, and no heavy card/button treatment unless explicitly requested.
- Sections: About Me / News / Selected Publications / Independent Project / Work Experience / Education. No Services and Leadership section.
- Publications: one `<li class="pub">` per paper, grouped by year (Preprints / YYYY / 2024 and Earlier) with short venue chips. No topic tags or filters, and never split by first/last author.
- News: dated paper/job milestones only; never list travel or trips.
- Favicon should use `favicon.ico` with separate 16/32/64px raster frames for browser tabs. Do not rely on browser-scaled SVG for tiny tab icons; self-check zoomed and actual-size PNG previews before showing the user.
