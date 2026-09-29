# Kibo Goods  — Lightweight E-Commerce Storefront

A clean,  zero-dependency storefront starter template built with semantic HTML5, modern CSS, and vanilla JavaScript.

## Project Structure

```text
shop-project /
├── index.html      # Complete storefront UI, styles, product catalog, and cart logic
└── README.md       # Project documentation  and setup guide
```

## Features

- **Responsive Product Grid:** Adaptive  CSS Grid layout that scales cleanly across mobile, tablet, and desktop screens.
- **Category Filtering & Live Search:** Filter items by category (`All`, `Workspace`, `Kitchen`, `Carry`) or search by keyword in real time.
- **Interactive Shopping Cart  Drawer:** Slide-ov er cart supporting item additions, quantity adjustments,  subtotal calculation, and `localStorage` persistence across   reloads.
- **Zero Build Tools Required:** Runs directly in any modern browser with no bundlers, frameworks,  or e xternal dependencies.

## Getting Started

1. Unzip the archive and open the `shop-project` folde r.
2. Double-click `index.html` to open it i n your web browser, or serve it locally:
   ```bash
   python3 -m http.server 8000
   ```
   Then visit `http://localhost:8000`.

## Customization

- **Products:** Edit the `PRODUCTS` array insi de the `<script>` tag in `index.html` to update names, categories, prices, descriptions, or replace emoji placeholders with `<img>` tags.
- **Theme Colors:** Adjust the CSS custom properties (`--bg`, `--accent`, `--text`, `--border`) inside `:root` at th e top of `index.html`.
- **Checkout Integration:** Replace the click handler on `#checkoutBtn` with a call to your payment provider (e.g., Stripe Checkout, Paystack, or M-Pesa Daraja API) .
