# CryptoVault Dashboard

A responsive cryptocurrency dashboard UI built with **only HTML5 and CSS3**. No JavaScript, no frameworks. Built as Task 3 of the GDG on Campus Canadian International College Front-End track, with a focus on **CSS Grid** and **Flexbox**.

> This is a front-end layout project. All prices, balances and charts are static sample data.


| Page | File | Description |
|---|---|---|
| Dashboard | `index.html` | Sidebar, top bar, statistics, BTC/USD and ETH/USD cards, asset allocation, portfolio health and risk level |
| Settings | `settings.html` | Settings tabs, four dropdowns, Compact View toggle, Save and Reset buttons |
| Sign In | `signin.html` | Email and password form with native validation |
| Sign Up | `signup.html` | Full name, email, password and confirm password form with native validation |

## Features

- **Dark and light mode** switched with a pure CSS toggle (a checkbox and `:has()`), no JavaScript
- **Fully responsive** on desktop, tablet and mobile, with no horizontal scrolling
- **Compact View** toggle that really tightens the spacing
- **CSS-only charts**: a conic-gradient donut, flexbox bar and candle charts, and one inline SVG area chart
- **Native form validation** using `required`, `type="email"` and `minlength`
- **Accessible**: semantic landmarks, correct heading order, labelled form fields, visible `:focus-visible` outlines and hover states

## Layout approach

- **CSS Grid** for the page structure (sidebar and content), the dashboard cards (`grid-template-areas`), the settings form and the auth pages
- **Flexbox** for the navbar, user area, buttons, legends and chart internals
- **Breakpoints** at 1200px, 900px, 600px and 380px; the sidebar becomes a top navigation bar on tablet

## Color palette (Midnight + Electric Violet)

| Role | Dark | Light |
|---|---|---|
| Background | `#0B0D17` | `#F4F5FB` |
| Surface | `#151827` | `#FFFFFF` |
| Border | `#232842` | `#E3E6F3` |
| Text | `#EDEEF7` | `#14172B` |
| Accent | `#7C5CFF` | `#6A48F2` |
| Positive | `#2DD4A0` | `#12A97C` |
| Negative | `#FF5C7A` | `#E0405F` |

## Project structure

```
.
├── index.html
├── settings.html
├── signin.html
├── signup.html
├── style.css
├── screenshots/
│   ├── desktop.png
│   ├── tablet.png
│   └── mobile.png
└── README.md
```

## Run it locally

1. Clone the repo
   ```bash
   git clone https://github.com/khlouddahmed/cryptovault-dashboard.git
   ```
2. Open `index.html` in your browser, or use the VS Code **Live Server** extension.

Light mode uses the CSS `:has()` selector, so use a recent version of Chrome, Edge, Safari or Firefox.

## What I practised

- Building a full layout with `grid-template-areas`, `repeat()` and `minmax()`
- Aligning components with Flexbox
- Theming with CSS custom properties
- Responsive design with media queries
- Accessible, semantic HTML

## Credits

Design reference: CryptoVault template by TemplateMo. This is my own implementation; no source code was copied.

Built by **Khloud Ahmed** for GDG on Campus Canadian International College.
