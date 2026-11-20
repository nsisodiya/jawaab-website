# Jawaab — landing page

Marketing site for **Jawaab**, an AI-powered WhatsApp inbox for D2C brands
(the product behind Brahmi Store's WhatsApp, offered as a SaaS showcase).

- Single static page: `index.html` (inline CSS/JS, Google Fonts), `favicon.svg`.
- No build step. Open `index.html` in a browser to preview.
- Hosted on **GitHub Pages** from the `main` branch root; every push to `main` redeploys.
- Leads come in by email (mailto links to hello@sisodiyaa.com).

This repo is only the website. The product itself lives in a separate private repo
(`brahmi-whatsapp-bot`).

## Custom domain (later)

1. Add a `CNAME` file containing the domain (e.g. `jawaab.example.com`).
2. Point DNS: a `CNAME` record to `nsisodiya.github.io` (subdomain), or the four GitHub Pages `A` records (apex).
3. In repo Settings → Pages, tick "Enforce HTTPS" once the certificate is issued.
