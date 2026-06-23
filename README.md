# HANSYBAY — Roller Skates Brand Website

- **Domain**: hansybay.com
- **Target**: United States & Canada
- **Category**: Roller Skates, Inline Skates, Wheeled Footwear
- **Deploy**: Vercel (free static hosting, auto-deploy on push)
- **CMS**: Page Editor + Product Database + Media Library (local API at 119.29.230.54/brand-api/)

## Architecture

```
public/
  index.html           # Homepage (Nike-style Hero)
  page-config.json     # Site configuration (brand-specific)
  product-db.json      # Product database (shared with gimkounn)
  media-list.json      # Media library index (shared)
  products/            # Product listing page
  videos/              # Video page
  activities/          # Community page
  brand-story/         # Brand story page
  privacy-policy/      # Legal pages
  terms/
  images/              # Shared image assets
  assets/              # CSS files
  cp-fiuk6t/           # Admin panel (password protected)
    index.html         # Login page
    page-editor.html   # Visual page builder
    product-editor.html # Product database editor
    media-manager.html  # Media library manager
```

## Data Flow

Local server → Flask API (write files + git push) → GitHub → Vercel auto-deploy

## Brand

- Primary Color: #E91E63 (Pink)
- Brand: HANSYBAY
