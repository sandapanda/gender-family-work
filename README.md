# Gender, Family, and Work Inequalities — workshop website

Single-page site for the workshop at Nuffield College, Oxford, 23–24 June 2026.
Static HTML, no build step. Hosts on GitHub Pages as-is.

## Publish on GitHub Pages
1. Create a new repository (e.g. `gfw-workshop-2026`).
2. Upload `index.html`, the `img/` folder, and this README to the repo root.
3. Repo **Settings → Pages → Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main** / folder: **/ (root)** → Save.
4. Your site appears at `https://<your-username>.github.io/<repo-name>/`
   within a minute or two.

Tip: for a shorter URL, name the repo `<your-username>.github.io` and the site
will live at `https://<your-username>.github.io/`.

## Before you go live — two quick edits
1. **Registration email.** In `index.html` search for `REGISTRATION_EMAIL`
   (two places) and replace it with the address that should receive online
   registrations.
2. **Images.** See `img/README.md` for the organizer photos and the two logos.
   Until added, the site shows tidy initials-circles and text logo cards.

## Editing content
Everything is in `index.html` — plain HTML with comments marking each section.
No frameworks, no dependencies (fonts load from Google Fonts).
