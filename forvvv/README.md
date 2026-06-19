# forvvv — ISIMS Static Site (Vercel)

Static HTML/CSS/JS clone of the ISIMS public homepage, ready to deploy on Vercel.

## Deploy to Vercel

### Option A — Vercel CLI
```bash
npm i -g vercel
cd forvvv
vercel
```

### Option B — Vercel Dashboard
1. Push this folder to a GitHub repo
2. Go to https://vercel.com/new
3. Import the repo — Vercel auto-detects it as a static site
4. Click **Deploy**

## Files
```
forvvv/
├── index.html       ← Public homepage
├── login.html       ← Login page (static preview)
├── register.html    ← Register page (static preview)
├── vercel.json      ← Vercel routing config
└── assets/
    ├── css/app.css
    └── js/app.js
```

## Notes
- Login and Register forms are **UI previews only** — form submission requires the live PHP backend.
- To connect to the live backend, update the form `action` attributes in `login.html` and `register.html` to point to your deployed PHP server URL.
