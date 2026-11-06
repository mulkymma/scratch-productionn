# Scratch Production

Exact recreation of [scratch-production.vercel.app](https://scratch-production.vercel.app) — a creative media studio portfolio site.

## Features

- Hero section with rotating background images
- Selected work gallery
- Services section
- Contact form + social/phone links
- Responsive layout matching the original design
- Same assets, copy, and structure

## Run locally

```bash
cd scratch-production
npx serve public -p 3000
```

Open http://localhost:3000

## Deploy to Vercel

```bash
npx vercel --prod
```

Or connect the repo / folder to Vercel and set the root directory to `public` (or leave as-is; Vercel will serve `public/` automatically if configured, or point output to `public`).

For a zero-config static deploy, upload the contents of the `public` folder.

## Stack

- Static HTML / CSS / vanilla JS
- Original images and logo from the live site
- Design matched to the v0.app / Next.js original

© Scratch Production 2026
