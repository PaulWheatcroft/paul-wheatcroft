# paulwheatcroft.me

Personal portfolio site — product developer, founder of BandSynq, builder of Cocktail Shaker, and owner of 8 Meg Stick Records.

Built with [Astro](https://astro.build).

## Development

Requires Node.js 22.12+ (see `.nvmrc`).

```bash
nvm use
npm install
npm run dev
```

Open [http://localhost:4321](http://localhost:4321).

## Build

```bash
npm run build
npm run preview
```

## Deploy to Vercel

1. Push this repo to GitHub (`PaulWheatcroft/paulwheatcroft`)
2. Import the project in [Vercel](https://vercel.com)
3. Framework preset: **Astro** (auto-detected)
4. Add custom domain **paulwheatcroft.me** in Project Settings → Domains
5. At your domain registrar, point DNS to Vercel:
   - **A record** `@` → `76.76.21.21`
   - **CNAME** `www` → `cname.vercel-dns.com`
6. Optional: redirect `www.paulwheatcroft.me` → apex in Vercel domain settings

## Structure

```
src/
  components/   # Hero, WhoIAm, Work, Music, Contact, etc.
  layouts/      # BaseLayout with meta/OG
  pages/        # index.astro (single page)
  styles/       # global.css design tokens
public/
  images/       # portrait
```
