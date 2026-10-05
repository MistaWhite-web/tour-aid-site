# Tour-Aid — coming soon page

A single static "under development" page for the Tour-Aid domain. No build step, no dependencies: plain HTML, CSS and a few lines of JavaScript. Fonts load from Google Fonts.

```
index.html                  the page
favicon.ico                 16/32/48 px tab icon
assets/
  touraid-mark-reversed.svg the logo used on the page
  touraid-mark.svg          full-color mark (light backgrounds)
  touraid-app-icon.svg      SVG favicon
  apple-touch-icon.png      iOS home-screen icon (180 px)
  icon-512.png              large icon for app manifests
  og-image.png              1200 × 630 social share image
```

## Deploy

Upload the folder as-is to any static host, or connect this repo:

- **Netlify / Vercel / Cloudflare Pages:** import the repo, no build command, publish directory is the repo root.
- **GitHub Pages:** Settings → Pages → deploy from branch `main`, folder `/ (root)`, then add your domain under Custom domain.

## Before going live

- Set the share image to an absolute URL so link previews work on Slack, iMessage, LinkedIn, etc. In `index.html`, change
  `<meta property="og:image" content="assets/og-image.png">` to `https://YOUR-DOMAIN/assets/og-image.png`.

## Brand

Colors, type and logo rules follow the Tour-Aid brand style guide. The name is always written **Tour-Aid**, with the hyphen.
