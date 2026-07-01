# CarDetailingRiyadh.com

Local car detailing business website for Riyadh, Saudi Arabia.

## Stack

- Next.js 14 (App Router)
- TypeScript
- Tailwind CSS
- shadcn/ui

## Getting Started

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

## Before Launch

1. **Update contact info** in `src/content/site.ts` — phone, WhatsApp number, email
2. **Replace placeholder copy** in `src/content/services.ts` and `src/content/locations.ts`
3. **Add real photos** to the gallery (replace gradient placeholders in `src/content/gallery.ts`)
4. **Update Google Maps embed URLs** in site config and location pages
5. Deploy to Vercel and connect `cardetailingriyadh.com`

## Content Files

Edit copy without touching components:

| File | Purpose |
|------|---------|
| `src/content/site.ts` | Business name, phone, WhatsApp, hours |
| `src/content/services.ts` | All 6 service pages content |
| `src/content/locations.ts` | All 6 location pages content |
| `src/content/pricing.ts` | Package pricing |
| `src/content/testimonials.ts` | Customer reviews |
| `src/content/gallery.ts` | Gallery items |

## Site Structure

- `/` — Homepage
- `/services` + 6 service pages
- `/locations` + 6 location pages
- `/about`, `/pricing`, `/gallery`, `/testimonials`, `/contact`

## Phase 2 (Not Built Yet)

- Arabic version (`/ar/...`)
- Service + location combo pages (e.g. `/ceramic-coating-al-olaya`)
