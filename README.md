# pixypump-site

The website for [PixyPump](https://www.pixypump.com), a pixel-art gym and calorie tracker for iPhone.

- `support/index.html` is the Support URL (`https://www.pixypump.com/support/`)
- `index.html` redirects the home page to the support page
- `CNAME` holds the custom domain

It is plain HTML with no build step. Pushing to `main` publishes it through GitHub Pages
(Settings → Pages → Deploy from a branch → `main` / root).
