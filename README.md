# Polymarket Oracle Bot – Dashboard (HTML only)

Static dashboard for the [Polymarket Oracle Bot](https://github.com/kashrifu/polymarket-oracle-bot). Deploy to **Vercel** (or any static host).

## Deploy to Vercel

1. [Vercel](https://vercel.com) → **Add New** → **Project** → Import this repo.
2. Deploy. No build step – static HTML only.

## Use the dashboard

Open your Vercel URL with your Railway bot URL as the `api` param (no trailing slash):

```
https://your-app.vercel.app?api=https://YOUR-RAILWAY-APP.up.railway.app
```

Example:  
`https://olymarket-oracle-bot-dashboard.vercel.app?api=https://polymarket-oracle-bot-production.up.railway.app`

The bot (Railway) must have a public URL and CORS enabled on `/api/status` (it does).
