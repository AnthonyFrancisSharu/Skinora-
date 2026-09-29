# Skinora

Skinora is a front-end e-commerce demo for a Sri Lankan skincare store, offering clinical (Cetaphil, CeraVe) and K-Beauty products. It's built as static HTML/CSS/JavaScript with no build step or backend required.

## Features

- **Product catalog** — 36 products across three categories (Cetaphil, CeraVe, K-Beauty), 12 per category, with brand filtering and live search.
- **Product detail pages** — image gallery, pricing, skin-type badge, tabbed details (Description, Benefits, How to Use, Ingredients, Shipping), and related products.
- **Shopping bag** — add/remove items, persisted in `localStorage`, with a slide-out cart panel and running subtotal.
- **Newsletter signup** in the footer.
- Responsive layout for mobile and desktop.

## Screenshots

### Home Page
<img src="screenshots/home-hero.png" width="800" alt="Homepage hero section" />
<img src="screenshots/home-collection.png" width="800" alt="Homepage product collection grid" />

### Category Filters
<img src="screenshots/category-cetaphil.png" width="800" alt="Cetaphil category filter" />
<img src="screenshots/category-cerave.png" width="800" alt="CeraVe category filter" />
<img src="screenshots/category-kbeauty.png" width="800" alt="K-Beauty category filter" />

### Search
<img src="screenshots/search.png" width="800" alt="Live search results" />

### Product Details Page
<img src="screenshots/product-detail.png" width="800" alt="Product detail view" />
<img src="screenshots/related-products.png" width="800" alt="Related products section" />

### Shopping Cart
<img src="screenshots/cart-sidebar.png" width="800" alt="Shopping bag sidebar" />

### Footer
<img src="screenshots/footer.png" width="800" alt="Site footer" />

## Tech Stack

- Plain HTML, CSS, and vanilla JavaScript (no frameworks, no build tools)
- [Google Fonts](https://fonts.google.com/) (Cormorant Garamond, Inter)
- [Font Awesome](https://fontawesome.com/) for icons
- [AOS](https://michalsnik.github.io/aos/) for scroll animations

## Running Locally

No installation or build step is needed — just open the file in a browser:

```bash
open index.html   # macOS
start index.html  # Windows
```

Or serve it with any static file server, e.g.:

```bash
npx serve .
```

## Project Structure

```
index.html    # Homepage — hero, product grid, filters, search, cart
product.html  # Product detail page (accessed via product.html?id=<id>)
screenshots/  # README screenshots
```

Product data currently lives inline in each page's `<script>` block.
