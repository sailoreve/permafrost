# PermaFrost Marine Services

One-page website for PermaFrost Marine Air Conditioning & Refrigeration, built with Astro and deployed as a static site on Cloudflare Workers.

- `src/pages/index.astro` – the page markup
- `public/style.css`, `public/script.js`, `public/assets/` – styles, animations/scripts and images (served as-is)

```sh
npm install
npm run dev      # local dev server
npm run build    # outputs to dist/
npx wrangler deploy   # builds and deploys to Cloudflare
```
