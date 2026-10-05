# Miniature Market Tracker — legal pages

Public website for **Miniature Market Tracker**, published with GitHub Pages. It contains only
legal pages; it holds no API code, no credentials and no data.

## Contents

| File | Purpose | Public URL |
|---|---|---|
| `index.html` | Terms of Use (required by the RapidAPI listing) | `https://<user>.github.io/<repo>/` |
| `privacy.html` | Privacy Policy (required by most marketplaces) | `https://<user>.github.io/<repo>/privacy.html` |

Links between the two pages are added in the header/footer of each page.

## Publishing

1. Settings → Pages → Source: **Deploy from a branch** → branch `main`, folder `/ (root)`
2. The site is live at `https://<user>.github.io/<repo>/` after a minute or two

`.nojekyll` prevents GitHub Pages from running Jekyll, so files are served exactly as written.


