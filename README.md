# Kota Murayama Academic Website

This repository contains a simple static academic website for Kota Murayama. It is designed for GitHub Pages and uses plain HTML, CSS, and minimal JavaScript. There is no build step and no framework dependency.

Content should not be invented; use TODO comments for unverified information.

## File Structure

```text
/
  index.html
  research.html
  teaching.html
  404.html
  favicon.svg
  .nojekyll
  assets/
    css/
      style.css
    js/
      main.js
  README.md
```

## Local Preview

From the repository root, run:

```sh
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000/
```

You can also open `index.html` directly in a browser, but a local server is closer to the GitHub Pages environment.

## Publishing With GitHub Pages

Expected public URL:

```text
https://kotamurayama.github.io/
```

If the site does not appear or returns a 404, check the repository settings:

1. Open GitHub repository settings.
2. Go to Settings -> Pages.
3. Source: Deploy from a branch.
4. Branch: `main`.
5. Folder: `/root`.
6. Save and wait a few minutes for GitHub Pages to publish.

Make sure `index.html` is in the repository root and that `.nojekyll` is present.

## Updating Content

- CV link: update the Google Drive URL in the header navigation on `index.html`, `research.html`, and `teaching.html`, and in the hero link on `index.html`.
- Research entries: edit `research.html`. Working papers are under `Working Papers`; published papers are under `Publications`.
- Selected research: edit the `Selected Research` section in `index.html`.
- Teaching entries: edit `teaching.html`. The page is separated into `Undergraduate` and `Graduate`.
- Contact information: edit the `Contact` section in `index.html` and the navigation contact links if the section ID changes.
- Colors, typography, and spacing: edit the CSS variables at the top of `assets/css/style.css`.

## Last Updated Policy

The footer contains a visible `Last updated` date. Update this date when content or design changes are published. The JavaScript in `assets/js/main.js` only updates the copyright year.

## Verified Source Information

The current CV link, contact details, paper titles, paper details, and research links were copied from the existing website and subsequent local edits. Do not add unverified positions, affiliations, coauthors, abstracts, or profile links without confirming them first.
