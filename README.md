# FOMO — Go where life happens

A mobile-first, dark-mode event discovery and community prototype for Dhaka.

## Run locally

No installation or API keys required. Open `index.html` in a browser, or use a static local server:

```bash
python3 -m http.server 5173
```

Then visit http://localhost:5173.

## Deploy

Import this repository into Vercel as an **Other** / static site project. No build command is needed. The output directory is the repository root.

## Features

- Responsive Discover feed with event categories, search, and detail pages
- Save and unsave events
- Demo ticket reservation with quantity selector and booking history
- Creator studio, event publishing form, and simple statistics
- Community posting feed
- Browser-local persistence via localStorage
- Keyboard-accessible native controls and mobile bottom navigation

## Important prototype limitations

- The six seeded events are **fictional examples**. They are not verified real events.
- Published events, saved items, social posts, and ticket reservations exist **only in the current browser's localStorage**. Clearing storage removes them; other users cannot see them.
- Ticket reservations are demonstrations only, not valid admission or payments.
- There is no authentication, database, moderation, payment gateway, or live social media ingestion.
- External Unsplash images and Google Fonts require internet access.

## Production roadmap

1. Migrate UI to component-based TypeScript app, add routing and automated tests.
2. Add hosted PostgreSQL (e.g. Supabase), secure authentication, profiles, and row-level authorization.
3. Add event management, image uploads, venue/location data, and moderation workflows.
4. Implement real inventory, server-side order lifecycle, verified payment gateway, webhooks, QR tickets, and check-in validation.
5. Ingest events through authorized feeds, organizer submissions, and platform-compliant integrations, with provenance and deduplication.
6. Add privacy policy, reporting, anti-abuse controls, analytics, accessibility testing, and CI/CD.

## Design direction

Minimal grayscale visual identity, editorial typography, immersive imagery, Threads/X-inspired social discovery, and a mobile-first experience.
