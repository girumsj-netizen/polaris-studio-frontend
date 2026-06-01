# Polaris Studio â€” Frontend (Astro)

## Quick Start

```bash
npm install
npm run dev
```

The dev server runs on `http://localhost:4321` by default.

## Environment Variables

| Variable | Description | Local | Production |
|---|---|---|---|
| `PUBLIC_API_URL` | Backend API base URL | `http://localhost:3001` | `https://your-app.onrender.com` |

Set `PUBLIC_API_URL` in your Vercel/Netlify dashboard to point to your live Render backend.

## Deploy to Vercel

1. Push this `frontend/` folder to a GitHub repo
2. Import project on Vercel
3. Set env var: `PUBLIC_API_URL` = `https://your-app.onrender.com`
4. Deploy

## Deploy to Netlify

1. Push this `frontend/` folder to a GitHub repo
2. Import project on Netlify
3. Build command: `npm run build`
4. Publish directory: `dist`
5. Set env var: `PUBLIC_API_URL` = `https://your-app.onrender.com`
