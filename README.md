# Root & Ritual — Haircare storefront

A responsive, static demo storefront built with plain HTML, CSS and JavaScript. No build step or backend is required.

## Preview locally

Open `index.html` directly, or run a simple static server:

```sh
python3 -m http.server 8000
```

## Deploy to Netlify

The repository is Netlify-ready (`netlify.toml` publishes the repository root). Connect this Git repository in Netlify and use the defaults, or drag and drop the project folder into Netlify Drop. No build command is needed.

## Demo functionality

- 24 products across shampoo, conditioner, treatments and styling
- Category filtering, sort-by-price, product search, product detail modal
- Product sizes/cap colors, quick add and persistent shopping bag
- Guest checkout with contact/shipping fields and demo card/PayPal selection
- Order confirmation is simulated; payment is never collected

Product catalog and demo behavior are in `script.js`. Product imagery and typefaces load from Unsplash and Google Fonts respectively. Replace demo images and wire a secure payment provider/server before accepting real orders. Never collect or process real card details using this static demo.
