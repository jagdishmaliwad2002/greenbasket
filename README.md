# 🌿 GreenBasket – Organic Grocery Store Website

A responsive, single-page e-commerce website for an organic fruits and vegetables store, built with plain HTML, CSS and JavaScript. No frameworks, no build step and no external images.

**Created by Jagdish Maliwad**

---

## Features

- **Hero banner** with a farm-fresh basket photo and call-to-action buttons
- **Category navigation:** the top tabs, photo category circles and footer links all filter products
  - Fruits, Vegetables, Berries, Exotic Fruits, Root Veggies, Greens & Beans, Mushrooms, Offers Zone
- **Product grid** with 18 products, real photos, prices, discounts and badges (Organic, Best Seller, Offer)
- **Search** by product name (click the search button or press Enter)
- **Shopping cart** drawer with quantity +/−, live total and checkout
- **Wishlist** heart toggle on every product
- **Login / Sign Up** popup
- **Newsletter** subscribe form
- **Customer reviews** slider that rotates automatically
- **Promo and story banners**, a "Why Choose GreenBasket?" section and an app download section
- **Fully responsive** for desktop, tablet and mobile

## Project structure

```
index.html   # the whole website (HTML + CSS + JS + embedded photos)
README.md    # this file
```

All photos are embedded inside `index.html` as base64 images, so the site works offline and can be moved anywhere as one file.

## How to run

1. Download `index.html`.
2. Double-click it to open it in any modern browser (Chrome, Edge, Firefox, Safari).

To host it online, upload `index.html` to any static host such as Vercel, Netlify or GitHub Pages.

## Customising

**Add or edit products:** open `index.html` and find the `P` array in the `<script>` section. Each product looks like this:

```js
["Name", "Weight", price, oldPrice, "Category", "imageKey", "Badge", isOffer]
```

**Change photos:** the `IM` object holds the embedded images. To use a normal image file instead, replace a value with a path, for example `"photos/apple.jpg"`.

**Change colours:** edit the CSS variables at the top of the `<style>` block:

```css
:root{--g:#4c7a14; --gd:#3b5f0e; --gl:#eef5e0; ...}
```

## Tech stack

- HTML5
- CSS3 (grid, flexbox, media queries)
- Vanilla JavaScript (ES6)
- Poppins font (Google Fonts)

## Notes

- The cart, login and newsletter are front-end demos only. There is no backend or payment gateway.
- Footer links such as "Track Order" and "FAQs" show a "coming soon" message.

## Author

**Jagdish Maliwad**

© 2024 GreenBasket. All rights reserved.
