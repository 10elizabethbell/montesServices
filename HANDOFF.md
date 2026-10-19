# Montes Services LLC: not built (they already have a website)

**Repo:** https://github.com/10elizabethbell/montesServices (public, contains only `.gitignore` and this note) · **Checked:** 2026-10-19 from Muse brief of 2026-10-19

## Why I stopped
The brief says "Existing website: none", but the flyer Muse attached prints **MONTESSERVICES.COM** along its bottom edge, and the site is live:
- https://www.montesservices.com: Next.js on Vercel, footer reads "Website by Treasure Coast Networks". Domain registered 2025-08-21 at IONOS.
- It has: Home, Services, About and Contact pages, a gallery with before/after photos, a free-quote form, `contact@montesservices.com`, hours (Mon–Sat 8:00 AM–5:30 PM), "Based out of Jackson, NJ", towns (Jackson, Lakewood, Toms River, Brick, Freehold, Howell, Manalapan), NJHIC # 13VH13805900, "Bonded | Registered | Insured".
- Weak spots, in case this is reopened as an upgrade pitch: on phones a dark, blurry hero photo fills the screen and pushes the headline down; the headline is just the business name; the orange buttons clash with the navy-and-gold logo; there's a sticky "Call now" button; and the copy is generic. Screenshots are in the session scratchpad, not committed.

Ellie decided to stop (2026-10-19): the prospect premise is wrong, and they already pay an agency.

## For Muse
- Read every word on a flyer image, footer domains included, before writing "Existing website: none". This one printed the domain, and a single `curl` would have found the site.
- The brief's web search turned up only unrelated "Montes" businesses because it searched by name; checking for `<businessname>.com` would have caught it.

## If reopened
Run `/pitch-site` again in this folder. The logo (`src-assets/logo-og.jpg`, 720px, from Facebook's og:image) and the flyer (`src-assets/flyer-post.jpg`) are already downloaded but not committed.
