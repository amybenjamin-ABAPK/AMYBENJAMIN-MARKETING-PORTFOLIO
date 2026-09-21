# Files to add before this goes live

Put these in a folder named `assets/` right next to `AMY_BENJAMIN.html`
(so the paths are `assets/camera-lens.png`, etc.). Everything else in the
page — all your project photos, the intro, the whole layout — is already
built into the HTML file and needs nothing extra.

## Your own content (required for those sections to show correctly)
- `assets/Amy-Benjamin-CV.pdf` — the CV/portfolio PDF behind the "Download
  portfolio" button on the Contact page.
- `assets/p2_2.png` — your photo on the About page.

## Personal-interest photos ("Through my lens" / moodboard section)
- `assets/camera-lens.png` — the compact camera photo.
- `assets/p3_1.png` through `assets/p3_9.png` — the tote bag, lip gloss,
  and other personal items in that grid (9 images).

## Decorative graphics (small illustrations, not photos)
- `assets/p4_1.png` — the iced-coffee cup graphic in the "Career brew" cup
  animation.
- `assets/p6_1.png` — the fork/knife graphic (used twice, mirrored) and
  `assets/p6_2.png` — the plate graphic, both in the "Career brew" menu.

## Optional — showreel/case-study videos
The page already handles these gracefully if missing (shows a static
placeholder instead), so these are nice-to-have, not required:
- `assets/showroom-1.mp4`, `assets/showroom-2.mp4`, `assets/showroom-3.mp4`
  — the three showroom films on the "Showroom content" case study.
- `assets/showreel.mp4` — an optional hero reel; even with the file
  present you'd also need to open the HTML and set `HERO_VIDEO` to
  `'assets/showreel.mp4'` near the top of the component script (it's
  `null` by default).

Once `assets/` is sitting next to the HTML file in your repo, push it to
GitHub Pages as-is — no build step, no other files needed.
