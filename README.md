# A Local Flower Shop — Front End

A static front-end page built with pure HTML and CSS, following the structure of the mini-project-01-spring2026 example.

## Folder structure (same as example)

```
flower-shop/
├── index.html
├── styles/
│   └── style.css
├── assets/
│   ├── 232938650 copy.png   (logo / favicon)
│   ├── hero-flower.png
│   ├── lilly_blossom.jpeg
│   ├── mixed_rose.png
│   ├── fall_blossom.jpg
│   ├── news-letter-bg.png
│   └── icon-linkedin.png, icon-twitter.png, icon-facebook.png, icon-youtube.png
└── README.md
```

## Sections

- **Navbar** — Logo, Home, Shop, About Us, Cart (Font Awesome icon)
- **Banner** — Hero text (“Always Fresh Flowers”) + hero image
- **Product display** — Our Bouquets (9 cards: Lilly, Mixed Rose, Fall in small/mid/large)
- **Newsletter** — “Join the Colorful Bunch” with email input and Subscribe
- **Footer** — Logo, vertical menus (links), social icons

## CSS

- External styles in `styles/style.css`
- Classes: `primary-font`, `secondary-font`, `navbar`, `banner`, `cards`, `card`, `news-letter-container`, etc.
- Fonts: Noto Serif, Inter
- Accent color: `--special-color: #ff9900`
- Fixed navbar, hover effects, responsive layout (mobile breakpoint at 768px)

## How to run

Open `index.html` in a browser, or use a local server:

```bash
cd flower-shop
npx serve .
```
