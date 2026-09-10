# rooted-in-rahmah-website

Personal website for Rooted in Rahmah: home of Sourdough Studio and Career Compass.

Live at [rootedinrahmah.com](https://rootedinrahmah.com), hosted free on GitHub Pages.

## Structure

Each venture is its own standalone page, no shared multi-page site, plus a thank-you page per venture:

- **`index.html`**: root landing page. Just the Rooted in Rahmah logo, tagline, and two links out to the ventures below. No other content.
- **`career-compass.html`**: the full Career Compass site: hero, about, pricing, resume snapshot, and a request-a-session form.
- **`sourdough-studio.html`**: the full Sourdough Studio site: hero, about, the menu (with a separate "made with sourdough discard" section), ordering info, an order form, and a questions form.
- **`thank-you-career-compass.html`**: confirmation page shown after submitting either Career Compass form.
- **`thank-you-sourdough-studio.html`**: confirmation page shown after submitting either Sourdough Studio form.

## Pending

- **Resume PDF**: `career-compass.html` has a "Download full resume (PDF)" button linking to `resume-aneeza.pdf`, but that file doesn't exist yet. Add a polished resume PDF named exactly `resume-aneeza.pdf` at the site root (next to `career-compass.html`, not in `images/`) or the link will 404.

## Images

All images live in `images/`:
- `rooted-in-rahmah-logo.png`, `career-compass-logo.png`, `sourdough-studio-logo.png`: brand logos
- `jalapeno-cheddar-sourdough.jpg`: product photo (more to be added as they're taken)

## Forms

Order requests, session requests, and general questions are all handled by [Formspree](https://formspree.io), free tier, no backend needed; each form posts to a Formspree endpoint and submissions arrive by email. Nothing is charged or booked automatically; every order and session is confirmed personally before payment (Venmo or Zelle) is collected.

## Hosting

Static HTML hosted on GitHub Pages, with `rootedinrahmah.com` pointed at it via DNS through Squarespace. No build step. Just push changes to `main` and they go live.
