# Luton International Church

One-page site for Luton International Church, built with Astro and Tailwind and hosted on Cloudflare Pages.

## Run locally

```
npm install
npm run dev
```

## Deploy

Pushing to `main` publishes the site (Cloudflare Pages, connected to this repo).
Other branches get a preview address.

Cloudflare Pages settings: framework **Astro**, build command `npm run build`, output folder `dist`, `NODE_VERSION` = `22`.
