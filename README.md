# Florida Bid Search — Checkout page

Static single-page checkout for **Florida Bid Search** (product: Florida County RFP Bid Search, $29.95/month).

## Local only

This folder is a **local draft**. It is not published. Do not push or create a GitHub repo from this copy until Sylvester approves.

## Layout

| Path | Purpose |
|------|---------|
| `README.md` | This file (repo root) |
| `docs/index.html` | Checkout page (inline CSS, no JavaScript) |
| `docs/logo.png` | Original Sylvester Spinetta LLC logo (from `_sq_raw.jpg`, PNG format only) |
| `docs/product.png` | Full 2000×2000 product ad |
| `docs/product-1000.png` | Web-optimized ~1000×1000 product image used on the page |
| `preview-desktop.png` | Desktop screenshot (1280×800 viewport, full page) |
| `preview-mobile.png` | Mobile screenshot (390×844 viewport) |

Site files live under `docs/` so a future GitHub Pages deploy can use the `/docs` folder option without moving files.

## Stripe payment link

The **Subscribe** button points to:

`https://buy.stripe.com/test_6oU8wQ7Xc9vu9mPaVY7N601`

**This is a TEST Stripe payment link.** Swap it for the live payment link before going public. No Stripe secret keys are used or stored anywhere in this site.

## Preview locally

From this directory:

```bash
python3 -m http.server 8080 --directory docs
```

Then visit `http://localhost:8080`.

Or open `docs/index.html` directly in a browser.

## Copy

- Site title / headline / og:title: **Florida Bid Search**
- Product subtitle: Florida County RFP Bid Search
- Price: $29.95/month
- Description: No setup fee. Four Florida counties covered. Monday and Thursday bid reports delivered to your email. One-year contract.
