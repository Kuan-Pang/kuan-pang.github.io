# kuan-pang.github.io

My personal homepage — a single static page served by GitHub Pages at
[kuan-pang.github.io](https://kuan-pang.github.io).

## Structure

```
index.html                       the entire page (HTML + inline CSS)
assets/img/headshot.jpg          profile photo
assets/img/publication_preview/  paper preview GIFs
.nojekyll                        serve files as-is (no Jekyll build)
```

## Editing

- **Text / links / layout** — edit `index.html` directly.
- **Add a publication** — drop a GIF in `assets/img/publication_preview/` and
  copy an existing `<article class="pub">…</article>` block in `index.html`.

No build step. Push to `master` and GitHub Pages serves it.
