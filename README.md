# 👤 Roy Chu — Personal Website

A modern, single-page personal website for **Roy Chu**, featuring a live clock, glassmorphism UI, animated backgrounds, and a fully responsive layout.

---

## ✨ Features

| Section | Description |
|---|---|
| **Hero** | Bold animated introduction with name, tagline, and call-to-action buttons |
| **Live Clock** | Real-time clock (ticks every second) showing time, date, and UTC+8 timezone |
| **Stats Cards** | Highlights — 5+ years experience, 30+ projects, 100% dedication |
| **Skills** | Hover-animated skill/interest chips |
| **Navigation** | Pill-shaped glassmorphism navbar with smooth scroll links |
| **Footer** | Social links and copyright |

---

## 🎨 Design Highlights

- **Dark theme** with deep navy background (`#0b0e1a`)
- **Animated gradient orbs** — purple, cyan, and pink floating blobs
- **Subtle grid overlay** for depth
- **Glassmorphism** navbar with `backdrop-filter: blur`
- **Gradient typography** on name using purple → cyan → pink
- **Micro-animations** — fade-slide-up on page load, hover lifts on cards and chips
- **Google Fonts** — *Outfit* (headings) + *Inter* (body)
- **Fully responsive** — adapts to mobile screens

---

## 🗂 Project Structure

```
W1/
├── index.html   # Single-page website (all HTML, CSS, JS inline)
└── README.md    # This file
```

---

## 🚀 Getting Started

No build tools or dependencies required. Just open the file in any modern browser:

```bash
# Simply open in browser
start index.html        # Windows
open index.html         # macOS
xdg-open index.html     # Linux
```

Or serve locally:

```bash
npx serve .
```

---

## 🌐 GitHub Pages

To host this site for free via GitHub Pages:

1. Go to your repo → **Settings → Pages**
2. Set **Source** to `main` branch, folder `/root`
3. Save — your site will be live at:

```
https://roy12358.github.io/0225DICDRL/
```

---

## 🛠 Built With

- **HTML5** — Semantic markup
- **CSS3** — Custom properties, animations, glassmorphism, grid/flexbox layout
- **Vanilla JavaScript** — Live clock with `setInterval`
- **Google Fonts** — Outfit & Inter

---

## 📄 License

© 2026 Roy Chu. All rights reserved.
