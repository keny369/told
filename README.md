# told.media

Static site for Told. One HTML file, no build step.

- `index.html` is the site.
- `hero-book.jpg` and `hero-book.webp` are the hero photograph (the finished book); `og.jpg` is the social preview image.
- `robots.txt`, `sitemap.xml`, `llms.txt` are for search engines and AI crawlers.
- `CNAME` binds the GitHub Pages deployment to told.media.
- `.nojekyll` stops GitHub running Jekyll over the files.
- `other/` is ignored by git: working documents and bundles that are not published.

Deploy: push to `main`, GitHub Pages serves it from the repo root.
