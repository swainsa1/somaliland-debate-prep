# Somaliland Debate Prep

A beginner-friendly prep package for the resolution:

> **The United States should recognize Somaliland as a sovereign nation.**

It covers both sides: background, history, a map of the neighbors, the strongest Affirmative and Negative arguments, evidence cards, cross-examination practice and sources.

## View it

Live site: **https://swainsa1.github.io/somaliland-debate-prep/**

## PDF version

If the website is blocked, use the PDFs in [`pdf-version/`](pdf-version/): one per page, plus [`complete-guide.pdf`](pdf-version/complete-guide.pdf) with everything.

## How it's built

Plain static HTML and CSS, with no build step:

- `*.html`: one page per topic (start at `index.html`)
- `assets/style.css`: shared dark purple design, with iPad and print/PDF styles
- `assets/horn-of-africa-map.svg`: simplified map of the region
- `site.json`: page order and navigation labels
- `.nojekyll`: tells GitHub Pages to serve the files as-is

The shared header, navigation and footer sit between `<!-- HEADER:START/END -->`-style markers and are kept in sync by a script, so edit page content inside `<main>` only.

Facts marked **verify** still need to be checked against a source before quoting.
