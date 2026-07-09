# Walkie — PWA Push-to-Talk

Two independent apps:

| Folder | What | Deploy to |
|---|---|---|
| [`walkie-frontend/`](walkie-frontend/) | React + TS installable PWA | Cloudflare Pages · Netlify · Vercel · GitHub Pages |
| [`walkie-backend/`](walkie-backend/)  | Node.js + Express + Socket.IO API & signaling | Any VPS / Railway / Render / AWS (Docker, PM2, NGINX included) |

Quick start:
```bash
# terminal 1
cd walkie-backend && cp .env.example .env && npm install && npm run dev
# terminal 2
cd walkie-frontend && cp .env.example .env && npm install && npm run dev
```
Open http://localhost:5173 in two browser profiles, pair with a code, hold to talk.
