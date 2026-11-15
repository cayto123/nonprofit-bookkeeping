# Cayto Group – Nonprofit Bookkeeping Landing Page

Standalone ad landing page for nonprofits.caytogroup.com (Google Ads).

- `index.html` – the whole page (no build step)
- `assets/` – logo and favicon
- Booking: Calendly inline embed (calendly.com/mikehenzgen/caytogroup)
- Countdown banner: whole days to Dec 31, 2026 (Mountain Time); hides itself after the deadline
- Conversion hook: a completed Calendly booking pushes `{event: "calendly_booking"}` to `window.dataLayer` for Google Tag Manager

Deploy: Cloudflare Pages, no build command, output directory `/`.
