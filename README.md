# BIKE-IT Website Repository

## Overview
BIKE-IT is a responsive, mobile-first web app for a local delivery service. Features include WhatsApp booking, manual tracking, a clear pricing structure, FAQs, and a design optimized for speed, usability, and local customer convenience. This repository contains the complete source for the BIKE-IT front-end (HTML & CSS).

Languages: HTML (61.9%), CSS (38.1%)

## Key Files & Their Purpose

- **index.html**: Main landing page — hero, quick booking CTA (WhatsApp), service highlights, and navigation.
- **booking.html** or booking section in index.html: WhatsApp booking flow or instructions for placing an order via WhatsApp.
- **tracking.html** or tracking section: Manual tracking interface/instructions for customers to check delivery status.
- **pricing.html**: Pricing structure, zone/weight-based fares, and any extra-fee notes.
- **faq.html**: Frequently asked questions about ordering, delivery times, coverage, and policies.
- **contact.html**: Contact details, WhatsApp link, and hours of operation.
- **terms.html / privacy.html**: (If present) Legal and privacy information for customers.
- **style.css** (or styles/ folder): Central stylesheet implementing mobile-first responsive layouts and visual system.
- **assets/** or **images/**: Icons, logos, and other site images used across pages.
- **fonts/**: Any local web fonts used (if included).
- **sitemap.xml / robots.txt**: SEO and crawler guidance (if present).
- **README.md**: This document — project overview and contributor info.

(If your repo uses different filenames or organizes pages into subfolders, update the list above to match your structure.)

## Features & Functionality

- Responsive, mobile-first design focused on small-screen usability and quick access.
- WhatsApp-first booking: one-tap booking via WhatsApp link or pre-filled message template.
- Manual tracking: simple tracking instructions or tracking UI for customers to monitor deliveries.
- Clear pricing structure: transparent fees, zone/weight rules, and examples to reduce support requests.
- FAQ section to cover common questions about orders, cancellations, and delivery windows.
- Lightweight HTML & CSS only — built for speed, minimal load, and compatibility with low-bandwidth connections.
- Accessibility-minded markup (semantic HTML, readable type sizes, clear call-to-action contrast).
- Local customer convenience: localized copy, contact methods, and business hours tailored to the service area.

## How to Use / Deploy

- This is a static site built with HTML and CSS — no build tools required.
- To preview locally: open index.html in a browser or serve with a simple static server (e.g., python -m http.server).
- To publish: push the repo to GitHub Pages, Netlify, Vercel, or any static hosting provider.

## Contributing

- For updates, bug fixes, or content changes: fork the repo, make changes, and open a pull request.
- Keep changes focused, mobile-first, and performant (optimize images, avoid large libraries).
- Include screenshots or a short demo URL in PR descriptions when UI changes are made.

## Credits
- Developed by Peacemaker Dev (they/them)

## License
No license file provided. All rights reserved by the project owner unless they specify otherwise. Contact the repository owner to request permission, contributions, or to clarify licensing.

## Contact
- GitHub: https://github.com/peacemaker-dev
- For urgent booking support: use the WhatsApp booking link provided in the site pages.

## Notes
- Built with HTML5 and CSS3.
- No JavaScript frameworks required for core features (may be added if the repo includes scripts).
- Update this README if you add server-side components, JS features, or third-party services (analytics, maps, payments).
