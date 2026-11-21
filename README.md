# Personal website – Dhanush Satish Reddy

Bilingual (DE/EN) one-page CV site for GitHub Pages. No build step.

## Files
- `index.html` – the whole site. All texts live in the `JOURNEY`, `LANGUAGES`, `DIGITAL`, `CERTIFICATES`, `NAME_STEPS` and `TEXT` blocks near the bottom.
- `photo.png` – profile photo (portrait). If it is missing, the site shows "DR".
- `og.png` – the 1200×630 preview image LinkedIn and other apps show when the link is shared.
- `Dhanush_Reddy_CV_GH.pdf` – the CV behind the download button.

## Editing tips
- New job or course: add an entry to the right city in `JOURNEY` (`type`, `start`, `end`, `title`, `org`, optional `desc`/`note`). `end: null` means "ongoing".
- The map labels are placed by hand in the `.map` block of the HTML.
- After changing `og.png`, LinkedIn may keep the old preview for a while. Paste the URL into the LinkedIn Post Inspector to refresh it.

Link straight to the English version with `?lang=en`.
