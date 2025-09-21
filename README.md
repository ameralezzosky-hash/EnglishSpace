# English Space (Vercel quick deploy)

This is a minimal Vite + React project that uses Tailwind via the CDN (no Tailwind build step)
and no shadcn/ui, so it can be deployed on Vercel easily.

## Run locally
```
npm install
npm run dev
```

## Build
```
npm run build
```

## Deploy on Vercel
- Push this folder to a GitHub repo (web upload works).
- On vercel.com: New Project → Import Git → Framework: **Vite** → Build: `npm run build` → Output: `dist`.
