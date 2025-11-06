# Movie Picker (Vite) - Simple Web App

This is a minimal Vite + React project containing the **Movie Picker** component you provided.
It uses **localStorage** to persist data in the browser so anyone can open the page and save their movies.

## Quick start (locally)

1. Install dependencies:
```bash
npm install
```

2. Run the dev server:
```bash
npm run dev
```
Open the URL printed by Vite (usually http://localhost:5173).

## Build & Deploy

This project can be deployed to **Vercel** easily:

1. Push this repository to GitHub.
2. Go to https://vercel.com/import and import your repo (Vercel will detect Vite).
3. Click Deploy — your site will be live on a vercel.app URL.

Alternatively, run:
```bash
npm run build
npx vercel deploy --prod
```

## Notes

- Tailwind CSS is loaded via CDN (script tag) for simplicity — no Tailwind build step.
- The original external AI suggestions call was removed to avoid needing an API key. The app includes a simple fallback suggestion by genre.

Enjoy — share the deployed URL with your friend!
