# AA.MAGAJI Electronics & Solar

Responsive navy-and-gold storefront with product filters, a browser-saved shopping cart, stock photography, and two showroom videos.

## Run locally

From this repository run `python -m http.server 8000`, then open http://localhost:8000.

## Deploy

Static website: no dependencies or build step. Publish the repository root. On Vercel, choose Other with no build command and the root output directory.

## Content

Edit the product catalogue in `app.js`, page content in `index.html`, and styling in `style.css`. Media is in `assets/`. Stock photo sources are recorded in `PHOTO-CREDITS.md`.

## Current scope

This is the HTML/CSS/JavaScript version. Cart selections persist on the visitor’s device. Checkout prepares a copyable order request; the business WhatsApp number, confirmed prices, online payments, product database, and admin login are not configured.
