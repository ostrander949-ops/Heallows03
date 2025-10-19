# Heallows — Dual-Entry Next.js (Vercel-proof)

This repo includes **both** `app/` and `pages/` so Vercel will always find an entrypoint.
`pages/index.tsx` simply renders the App Router page.

## Run locally
```bash
npm i
npm run dev
```

## Build test
```bash
npm run build
```

## Deploy
Push to GitHub; in Vercel, just import and deploy (no Root Directory setting needed).
