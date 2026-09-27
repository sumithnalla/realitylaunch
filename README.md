# RealtyLaunch website

A static, multi-page website for RealtyLaunch and its projects. No build step, no server code — just upload the files.

## Pages & files

| File | Purpose |
|------|---------|
| `index.html` | Home (hero slider, both projects, why-us) |
| `projects.html` | Projects hub — lists both projects |
| `tranquil-farms.html` | Project: Gupta's Nature Tranquil Farms (managed farmland, Jangaon) |
| `golden-heights.html` | Project: Gupta's Golden Heights II (HMDA homes near AIIMS, Bibinagar) |
| `gallery.html` | Gallery — Projects & Events, with lightbox |
| `about.html` | About the company |
| `contact.html` | Contact + enquiry form |
| `properties.html` | Redirects to the Projects hub (kept so old links don't break) |
| `styles.css` | All styling |
| `logo.svg`, `logo-mark.svg` | Full logo + icon/favicon |
| `tranquil-layout.png` | Tranquil Farms master layout plan |
| `gh-1.png`, `gh-2.png` | Golden Heights brochure pages (elevation + location map) |
| `tranquil-farms-brochure.pdf` | Tranquil Farms brochure download |
| `golden-heights-brochure.pdf` | Golden Heights brochure download |

## How to put it live

**Option A — drag & drop (easiest):** go to Netlify Drop (app.netlify.com/drop), Cloudflare Pages, or Vercel, and drag this whole folder in. You get a live URL in seconds; then connect your custom domain.

**Option B — traditional hosting (cPanel / FTP):** upload every file in this folder to `public_html`, keeping them together. `index.html` loads automatically.

## Contact details (already set)

- **Phone:** +91 87905 32078 · **Email:** Realtylaunch2025@gmail.com (used across the site, WhatsApp button and forms).

## Forms — one-time activation needed

Both the **Contact enquiry** and the **Channel Partner application** forms now send submissions straight to **Realtylaunch2025@gmail.com** using FormSubmit (no server required).

**Activate once after going live:** submit either form yourself one time from the live site. FormSubmit will email `Realtylaunch2025@gmail.com` an activation link — click it once, and all future submissions arrive automatically in that inbox. (Until activated, the first submission won't be delivered.)

## Optional tweaks
- **Office address:** the Financial District line in footers/contact — update if different.
- **Map:** the contact page shows a placeholder — replace `.map-box` with a Google Maps embed iframe.
- **Photos:** project pages use the real brochure/layout images; the rest of the gallery uses styled placeholders. Send real photos to swap them in.

## Notes
- Fonts (Cormorant Garamond + Montserrat) load from Google Fonts; falls back to system serif/sans offline.
- Fully responsive; no database required.
- Pricing reflects the brochures provided. Confirm current prices/availability before publishing.
