# Exhibit Stamp — website

Support page and privacy policy for Exhibit Stamp, a macOS app that marks PDFs
and images as court exhibits. Published with GitHub Pages, served from the root
of `main`.

Plain HTML and one hand-written stylesheet. No framework, no build step, no
external font, no remote asset of any kind: the site makes the same promise the
app does — it loads nothing from anywhere else.

## Editing

Do not edit these files here. They are copied from `site/` in the application
repository, which is where the site is written and reviewed. Publishing runs:

```sh
./publish-site.sh
```

from that repository, which copies `site/` over this working copy, commits and
pushes. Anything edited here directly is overwritten on the next publish.

## Files

| | |
|---|---|
| `index.html` | sends visitors to the support page |
| `support.html` | contact address and FAQ |
| `privacy.html` | privacy policy |
| `style.css` | the whole stylesheet |
| `icon.png` | the app icon |
| `.nojekyll` | serve the files as they are, without running Jekyll |
