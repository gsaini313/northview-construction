# Northview Construction Co. — Demo Website

A single-page static demo website for a fictional GTA construction company,
built in the same style as the `elite-barber` / `btown-barbershop` demo sites
but with a distinct construction-industry look and content.

## Structure

- `index.html` — the entire site (inline CSS + JS, no build step)
- `images/` — AI-generated project photography
  - `hero.jpg` — framing crew at golden hour
  - `kitchen.jpg`, `bathroom.jpg`, `basement.jpg`, `exterior.jpg` — project gallery
  - `blueprints.jpg` — "why us" section

## Sections

Hero → services marquee → 8 services → project gallery → why-us →
4-step process → reviews → service area → quote form → contact → footer

## Run locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

Or deploy as-is to GitHub Pages / Netlify / Vercel.

## Notes

Business details (name, phone, address) mirror the real Northview Construction
Co. listing in Vaughan, ON. All other content — services, reviews, stats — is
illustrative placeholder content for demo purposes.
