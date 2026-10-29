# Dev Kumar — OCI infrastructure portfolio

A responsive portfolio built as a static HTML/CSS/JavaScript site for GitHub Pages. The visual direction centers on durable control-plane state, distributed coordination, fleet automation, fault recovery, and operations. The hero background is a project-specific generated cloud data-center image with CSS drift motion; the SVG control-loop diagram animates state flow and responds to Provision, Partition, and Recover controls.

## Contents

- `index.html` — portfolio, all resume experience bullets, project cards, and links
- `styles.css` — responsive visual design, scroll reveals, background motion, and diagram states
- `script.js` — rotating focus text, interactive lifecycle diagram, and project filters
- `oci-control-plane.jpg` — generated hero background
- `.github/workflows/pages.yml` — deploys the static site to GitHub Pages on pushes to `main`
- `ROLE_RESEARCH.md` — role and company research notes, sources, and the exact-posting caveat

## GitHub Pages

The repository Pages source is GitHub Actions. Every push to `main` runs the Pages deployment workflow. The site uses no build tooling or external runtime dependencies; Google Fonts are loaded remotely.

## Content notes

The Experience section preserves all 15 experience bullets from the supplied resume. The Projects section contains the 23 projects and all source URLs supplied in the request. It includes Technical Demo links only for projects with supplied demo URLs. The site does not display a LinkedIn link, phone number, email address, or footer.
