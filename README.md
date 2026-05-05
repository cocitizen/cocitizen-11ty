# cocitizen.com

Source for [cocitizen.com](https://cocitizen.com) — a volunteer home for open-source civic-tech tools.

Built with [Eleventy](https://www.11ty.dev/). Deployed via Cloudflare Pages.

## Local development

```bash
npm install
npm run dev
```

Site serves at `http://localhost:8080`.

## Build

```bash
npm run build
```

Output goes to `_site/`.

## Deployment

Cloudflare Pages build settings:
- **Build command:** `npm run build`
- **Build output directory:** `_site`

## Styleguide

Internal design reference lives at `/styleguide/` (not indexed).
