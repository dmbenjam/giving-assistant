# Giving Assistant

Single-page landing + chat prototype for Syracuse University’s Clementine platform.

## Deploy to Vercel (from GitHub)

1. **Push this repo to GitHub** (if it is not already): commit and push `main`.
2. Go to [vercel.com](https://vercel.com), sign in with GitHub, and click **Add New… → Project**.
3. **Import** your `giving-assistant` repository.
4. Leave defaults: **Framework Preset** “Other”, no **Build Command**, **Output Directory** empty (site root). Vercel will serve `index.html` at `/`.
5. Click **Deploy**. Your site will get a `*.vercel.app` URL; you can add a custom domain under **Project → Settings → Domains**.

The Supabase anon key in `index.html` is intended for public client use; keep service role keys out of the repo.

## Local preview

Open `index.html` in a browser from this folder, or run a static server, for example:

`npx serve .`