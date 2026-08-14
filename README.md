# Little Sprouts of Tomorrow — Website

A free, static website for Little Sprouts of Tomorrow Homeschool Program, built to host on GitHub Pages at no cost.

## How to publish this on GitHub Pages

1. Create a new repository on GitHub (e.g. `little-sprouts-of-tomorrow`).
2. Upload every file in this folder to the repository, keeping the same folder structure (`css/`, `images/`, `js/`, and the `.html` files) at the root of the repo.
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set Source to **Deploy from a branch**, branch **main**, folder **/(root)**.
5. Save. GitHub will give you a live URL like `https://yourusername.github.io/little-sprouts-of-tomorrow/` within a minute or two.

## Updating the site later

- To change text, edit the `.html` files directly (they're plain, readable HTML).
- To change colors/fonts, edit `css/style.css` — the color values are all defined at the top in one place.
- To add gallery photos, drop new images into `images/` and add a matching `<a>/<img>` block in `gallery.html`.
- Curriculum and Enrollment are currently placeholder "Coming Soon" pages — replace the content inside the `.placeholder-card` in `curriculum.html` and `enrollment.html` once that content is ready.

## File structure

```
index.html        Home
about.html         About
program.html       Program
curriculum.html    Curriculum (placeholder)
enrollment.html     Enrollment (placeholder)
gallery.html       Photo gallery
contact.html       Contact info
css/style.css      All styling
js/nav.js          Mobile menu toggle
images/            Logo + gallery photos
```
