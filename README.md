# client-pages

Shareable pages Boolean sends to clients (walkthroughs, timelines, audits).
Published with GitHub Pages at `https://boolean-automation.github.io/client-pages/`.

## Layout

```
<client-slug>/<page-slug>/index.html   one self-contained page per folder
<client-slug>/<page-slug>/img/         that page's images
index.html                             blank on purpose, so nothing is listed
robots.txt                             blocks search engines
.nojekyll                              serve files as-is
```

A page's link is `https://boolean-automation.github.io/client-pages/<client-slug>/<page-slug>/`.

## Adding a page

1. Create `<client-slug>/<page-slug>/` with an `index.html` and an `img/` folder.
2. Keep the page self-contained (inline CSS/JS, no outside libraries).
3. Add `<meta name="robots" content="noindex,nofollow">` to the page head.
4. Commit and push to `main`. The page is live within a minute or two.

## Before you publish

This repo and its pages are **public**. Anyone with the link can open them.

- Redact personal details: phone numbers, emails, home addresses, customer names.
- Use solid bars for redaction, not blur.
- Use test bookings or sample data where you can.
- Nothing else links here. Share each page's link directly with the client.

## Pages

| Client | Page | Purpose |
|---|---|---|
| prorise | gutter-timeline | Customer-facing YCBM sequence for gutter estimates, booking to arrival |
