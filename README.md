# Lukas Schmid — Academic Website

Source for [lschmid94.github.io/Lukas-Website](https://lschmid94.github.io/Lukas-Website) (once GitHub Pages is enabled).

## Structure

- `index.html` — the entire site (single page, sections: About, Research, Publications, Teaching, CV, Contact). All CSS/JS is inlined; no build step.
- `assets/Lukas_Schmid_CV.pdf` — downloadable CV, linked from the site.
- `.nojekyll` — tells GitHub Pages to serve the site as-is (skip Jekyll processing).

## Editing

Open `index.html` in any editor. Content for each section lives in its own `<section id="...">` block. To swap in a photo later, add an `<img>` inside the `.hero` block in the markup and a matching rule in the `<style>` section.

## Publishing with GitHub Pages

Repo → Settings → Pages → Source: `main` branch, `/ (root)`. The site will be live at the URL above a minute or two after the first push.
