# Printables4self — Free Printables

A lightweight, mobile-friendly landing page for free downloadable printables from **Printables4self**.

## What's included

- `index.html` — static landing page (no build tools needed)
- `december-family-activity-calendar.pdf` — free printable December family activity calendar

## Purpose

Help visitors discover and download useful free printables, with a link to the [Printables4self Etsy shop](https://printables4self.etsy.com).

## Local preview

Open `index.html` in a browser. For the most reliable test of PDF links, serve the folder locally with a static web server (for example, `python3 -m http.server 8000`) and open `http://localhost:8000`.

## Deploy to Cloudflare Pages

1. Push the contents of this folder to a GitHub repository, keeping `index.html` at the repository root.
2. In Cloudflare, open **Workers & Pages** and create a **Pages** project connected to that repository.
3. Use no framework and no build command. Set the output directory to the repository root (`.`) if requested.
4. Deploy, then verify that the homepage loads and the PDF download works.

## Update the freebies

Add new PDFs to the repository, then edit `index.html` to add their preview cards and download links. A connected Cloudflare Pages project can redeploy automatically when changes are pushed to the production branch.

## Notes

- The December calendar is a free download; no purchase or email signup is required.
- The Etsy shop link is promotional, not an affiliate link.
- Before sharing a Pinterest destination link, test the live download on mobile.
