# STAY HUSTLE — Interactive Streetwear Store

High-end, minimalist streetwear e-commerce experience inspired by experimental brands like Corteiz / Sicko.

## Features

- **Preloader**: Full-screen black splash with pulsing red brand emblem that fades out.
- **Announcement Ticker**: Continuous scrolling marquee.
- **Navigation**: Minimal header with tilted logo and live bag counter.
- **Interactive Clothes Rail**: 6 colorways hanging on a metallic rail. Hover or focus rotates a hoodie into full front view with realistic spring physics (Framer Motion), pushing neighbors aside.
- **Product Detail Page**:
  - 360° scrubbable rotation slider (red thumb)
  - 2D / 3D view mode toggle
  - Size selector with active red state
  - Add to bag → slide-out cart drawer
  - Stock / shipping status, specs accordion
- Fully responsive, crisp Inter + Space Grotesk typography, tactile micro-interactions.

## Tech

- React 18 (CDN)
- Tailwind CSS (CDN)
- Framer Motion 11 (CDN) for springs & page transitions
- Pure client-side, no build step required

## How to run

Simply open `index.html` in a modern browser (Chrome / Safari / Firefox recommended).

Or serve locally:

```bash
npx serve .
```

## Notes

Hoodie visuals are CSS-generated placeholders representing the six colorways. In a production build you would replace them with high-resolution product photography + multi-angle sequences or a real 3D model viewer.
