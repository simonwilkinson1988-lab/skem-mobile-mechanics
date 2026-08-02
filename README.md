# Skem Mobile Mechanics

Static website for **Skem Mobile Mechanics** — a mobile mechanic service covering Skelmersdale, Up Holland, Ormskirk, and surrounding areas.

## Pages

- `index.html` — Home page
- `services.html` — Full services list with pricing
- `about.html` — About the business
- `areas.html` — Coverage area details
- `contact.html` — Contact info, hours, and FAQ

## Deployment

This is a **static HTML site** — no build step required.

### Deploy to Vercel

1. Connect this repo to [Vercel](https://vercel.com)
2. Framework Preset: **Other** (no framework)
3. Build Command: leave empty
4. Output Directory: `.` (root)
5. Add your custom domain in Vercel project settings

The `vercel.json` file handles:
- Clean URLs (e.g., `/services` instead of `/services.html`)
- Image caching headers for performance
- Proper HTML cache control

### Local Development

```bash
npx serve .
```

Then open `http://localhost:3000`

## Domain Setup

Once deployed on Vercel:
1. Go to Project Settings > Domains
2. Add your domain (e.g., `skemmobilemechanics.co.uk`)
3. Update DNS records as instructed by Vercel

## Tech Stack

- Pure HTML + CSS (no JavaScript framework)
- Google Fonts (Chakra Petch)
- Schema.org structured data for SEO
- Mobile-first responsive design
- Sticky CTA bar on mobile devices
