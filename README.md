# Elara — Musician Portfolio Site

An immersive, animation-driven portfolio site for a fictional musician — 
exploring high-end editorial web design with custom cursors, scroll-triggered 
animations, and a horizontal-scroll discography section.

## Live Demo
https://[your-netlify-url].netlify.app

## Features

- **Custom cursor** with hover states using `mix-blend-mode: difference`
- **Smooth scrolling** via Lenis, integrated with GSAP's ticker
- **Scroll-triggered animations** using GSAP ScrollTrigger
- **Horizontal scroll** section with pinning for the discography
- **Parallax effects** on the hero and gallery
- **Magnetic buttons** that respond to cursor proximity
- **Image reveals** using animated `clip-path`
- **Accessibility** — respects `prefers-reduced-motion`
- **Responsive** down to mobile, with touch-friendly fallbacks

## Tech Stack

- HTML + Tailwind CSS (via CDN)
- GSAP 3.12 + ScrollTrigger
- Lenis (smooth scroll)
- Vanilla JavaScript

## Design Philosophy

Inspired by editorial sites like Awwwards winners — restrained palette, 
serif/sans-serif type pairing, generous whitespace, and motion that supports 
the content instead of distracting from it.

## Running Locally

Just open `index.html` in a browser. All dependencies load via CDN.

## License

MIT
