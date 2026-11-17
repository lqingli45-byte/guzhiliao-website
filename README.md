# Gu Zhi Liao website

English brand site for Gu Zhi Liao (谷知了). Static HTML/CSS.

Intended public URL after GitHub Pages is turned on:

https://lqingli45-byte.github.io/guzhiliao-website/

Business email: lqingli45@gmail.com

## Preview locally

```bash
python3 -m http.server 4173
```

Open http://localhost:4173

## How to update later

1. Edit the relevant `.html` file for page copy, `assets/styles.css` for design, or `assets/logo.svg` for the mark.
2. To add a product direction, copy one `product-card` block in `products.html`. Keep unfinished items labeled Planned or Coming Soon. Do not add a price or buy button until the product can be delivered.
3. If the business email changes, update `contact.html`, the footer on every page, the legal pages, and `site.config.json`.
4. Before sales begin, update the product page with price, what’s included, and delivery method, and review the Privacy, Terms, and Refund and Cancellation pages so they match the actual offer.
5. After editing, upload the changed files to the `guzhiliao-website` GitHub repository. GitHub Pages usually updates within a few minutes.

Do not put API keys, passwords, or private files in this folder.
