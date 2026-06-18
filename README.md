# Kota Murayama Academic Website

This is a simple static academic website for Kota Murayama. It is built with plain HTML, CSS, and minimal JavaScript so that it can be edited without a build system.

## File Structure

```text
/
  index.html
  research.html
  teaching.html
  favicon.svg
  assets/
    css/
      style.css
    js/
      main.js
  README.md
```

## Local Preview

Open `index.html` directly in a browser, or run a local server from this directory:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000/`.

## Publishing With GitHub Pages

Expected URL for the `kotamurayama/webpage` repository:

```text
https://kotamurayama.github.io/webpage/
```

For the shorter root URL `https://kotamurayama.github.io/`, rename the repository itself to `kotamurayama.github.io`.

1. Create a GitHub repository.
2. Copy the files in this directory to the repository root.
3. Commit and push the files.
4. In GitHub, open Settings -> Pages.
5. Choose the `main` branch and the repository root as the Pages source.
6. Save the setting and wait for GitHub to publish the site.

## Updating Content

- Papers: edit the paper entries in `research.html`. Working papers are under the `Working Papers` section; published papers are under `Publications`.
- Selected research on the home page: edit the `Selected research` section in `index.html`.
- CV link: update the Google Drive URL in the header navigation on all three HTML files and in the hero button on `index.html`.
- Teaching: edit the course entries in `teaching.html`. The page is separated into undergraduate and graduate sections.
- Contact: edit the `Contact` section in `index.html` and the navigation/footer text if needed.
- Design tokens: adjust colors, fonts, spacing, and layout variables at the top of `assets/css/style.css`.

## Verified Source Information

The current CV, contact details, paper titles, paper details, and research links were copied from the existing Weebly site on June 18, 2026.
