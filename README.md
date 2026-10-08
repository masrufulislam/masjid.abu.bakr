# Masjid Abubakar & Community Center website

A responsive, single-page website inspired by Quran.org's spacious editorial design. No build tools required.

## Run locally
Open `index.html` in a browser, or serve the folder with `python3 -m http.server 8000` and visit `http://localhost:8000`.

## Deploy
Upload `index.html` to Netlify, Cloudflare Pages, GitHub Pages, or any static web host. HTTPS is recommended for clipboard functionality.

## Working features
- Responsive navigation and section links
- Persistent light/dark theme with system preference fallback
- Live *calculated adhan times* via AlAdhan API, refreshed by local NYC date, and next-prayer countdown
- Google Maps embedded map and directions
- Copy-address action
- SEO description, keyboard focus styles, reduced-motion support

## Before official launch
1. Obtain masjid approval, logo, photographs, official contact details, program descriptions, and verified Jumu'ah/iqamah schedules.
2. Prayer times currently use AlAdhan method 2 (ISNA), Hanafi Asr (school 1), and coordinates for the masjid. These are calculations, NOT verified congregational times. Confirm preferred calculation method with masjid leadership.
3. Add a verified donation processor only after receiving the masjid's authorized donation destination. No payments are collected by this template.
4. Test in production across browsers and phones, confirm maps and API availability, and connect a custom domain.

This is a launchable static site, but it is not an official masjid website until content and authorization are verified.
