# danika-wright.github.io

Pages shared by link for a while, then taken down.

Each page carries a takedown date in its head:

```html
<meta name="takedown" content="2026-11-20">
<meta name="robots" content="noindex, nofollow">
```

`.github/workflows/pages.yml` runs on every push and once an hour. From the takedown
date (Sydney time) it deletes that page's folder from `main` and redeploys the site
without it. Any missing URL shows the plain `404.html`.

A deleted page **stays in this repo's git history**. The live site stops serving it;
the repo's commit history does not forget it.
