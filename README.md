# Visit Toronto Tours by Travaza

Static website for https://visittorontotours.com (no build step).

- `index.html`: the whole site (photos are embedded)
- `robots.txt`, `sitemap.xml`, `llms.txt`: search engine and AI discovery files
- `images/`: social preview image and logo

## Edit
- Tours: search `class="tour"` in index.html
- Bokun booking buttons: the `bokunButton` elements
- Blog posts: copy a `<details class="post">` block
- FAQ: add a `<details><summary>` block inside the FAQ section

## Deploy
Netlify: import this repo, leave build command empty, publish directory blank.
GitHub Pages: Settings > Pages > Deploy from branch > main > / (root).
