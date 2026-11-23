# sethjmarcus.us

Personal homepage. Plain HTML/CSS, no build step.

## Deploy
Cloudflare Pages, connected to this repo:
- Build command: *(none)*
- Build output directory: `site`
- Custom domain: `sethjmarcus.us`

`site/_headers` sets the security headers (same as jays-game, plus `font-src 'self'`).
Fonts are self-hosted in `site/fonts/`: Doto (the LED sign) and Public Sans (body), both SIL Open Font License.

## To do
- Add a photo: put `seth.jpg` in `site/` and uncomment the `<img class="photo">` line in `index.html` (instructions in the HTML comment).
- Add LinkedIn link (commented out in `index.html`).
