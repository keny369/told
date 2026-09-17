# told.media

Static site for Told. One HTML file, no build step.

- `index.html` is the site.
- `robots.txt`, `sitemap.xml`, `llms.txt` are for search engines and AI crawlers.
- `CNAME` binds the GitHub Pages deployment to told.media.
- `.nojekyll` stops GitHub running Jekyll over the files.
- `og.png` is the social preview image.

Deploy: push to `main`, GitHub Pages serves it from the repo root.
