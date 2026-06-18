# Images to add

Drop these files into this `img/` folder. The site already references them —
no code changes needed, the filenames just need to match.

## Organizer photos (square works best, ~400×400px)
- `juliana.jpg`  — Juliana de Castro Galvão
- `sander.jpg`   — Sander Wagner

After adding them, in `index.html` find each organizer's
`<div class="avatar" aria-hidden="true">JG</div>` (or `SW`) and replace it with:
  <img class="avatar" src="img/juliana.jpg" alt="Juliana de Castro Galvão">
  <img class="avatar" src="img/sander.jpg" alt="Sander Wagner">
(Until you do, a clean navy initials-circle shows instead.)

## Logos (PNG with transparent background preferred)
The logos appear in two places — the dark hero strip (near the top) and the
Acknowledgements section (near the bottom). For the hero, white/light versions
read best on navy; for the footer, the standard colour versions are fine.

- `lcds-logo.png`        — Leverhulme Centre for Demographic Science (colour, for Acknowledgements)
  Download from: https://www.demography.ox.ac.uk/themes/custom/olamalu_leverhulme/images/branding/OxLCDSlogo.png
  (and for a Leverhulme-only mark: .../images/leverhulme-logo.png)
  The Nuffield wordmark logo is on nuffield.ox.ac.uk — grab it from the College's brand/press assets.
- `nuffield-logo.png`    — Nuffield College, University of Oxford (colour, for Acknowledgements)
- `lcds-logo-white.png`  — white/mono version for the hero strip (optional)
- `nuffield-logo-white.png` — white/mono version for the hero strip (optional)

In the hero, find the two `<a class="hlogo">…</a>` blocks and replace the text
with e.g.:
  <a href="https://www.demography.ox.ac.uk/" class="hlogo"><img src="img/lcds-logo-white.png" alt="Leverhulme Centre for Demographic Science"></a>
In the Acknowledgements section replace the two `<div class="logo-fallback">…</div>`
blocks with:
  <img src="img/lcds-logo.png" alt="Leverhulme Centre for Demographic Science">
  <img src="img/nuffield-logo.png" alt="Nuffield College, University of Oxford">

## College map
The official Nuffield College map is already included (`img/college-map.png`)
and live in the Venue section, with the "Designed by Kaeden Brough" credit shown
beside it. No action needed. (`college-map-source.png` is the original extract,
kept for reference.)

## Hero / logo
The hero uses the workshop's logo lockup (gender · family · work), embedded
inline in `index.html`. A standalone copy lives at `img/logo.svg` — reuse it on
slides, name badges, or email signatures. To use a photo instead, replace the
whole inline `<svg>…</svg>` inside `<div class="hero-art" id="hero-art">` with:
    <img src="img/hero.jpg" alt="Gender, family, and work inequalities" style="width:100%;display:block">

## Optional presenter photos
You said presenter photos may come later. The programme currently lists names
+ links only (clean and standard for a workshop). If you later want headshots
next to each talk, tell me and I'll add a photo column.
