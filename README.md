# Cayto Group – Nonprofit Bookkeeping Landing Page

Standalone ad landing page for nonprofits.caytogroup.com (Google Ads).

- `index.html` – the whole page (no build step)
- `assets/` – logo and favicon
- Booking: Calendly inline embed (calendly.com/mikehenzgen/caytogroup)
- Countdown banner: whole days to Dec 31, 2026 (Mountain Time); hides itself after the deadline
- Tracking: Google Tag Manager GTM-PQDLF7J3 (GA4 G-LX2PTQW9TX). A completed Calendly booking pushes `{event: "calendly_booking"}` to `window.dataLayer`; GTM fires the GA4 and Google Ads conversions on it

Deploy: Cloudflare Pages, no build command, output directory `/`.
