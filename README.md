# Kamalesh-Kavin.github.io

Personal portfolio site for [Kamalesh S](https://kamalesh-kavin.github.io) — Backend Software Engineer.

Live at: **https://kamalesh-kavin.github.io**

## Stack

- Static HTML + [Tailwind CSS CDN](https://tailwindcss.com) — zero build step, no npm
- Vanilla JS for all animations and interactivity
- GitHub Pages for hosting (auto-deploys on push to `main`)

## Features

- Particle canvas background (animated with `requestAnimationFrame`)
- Typing effect cycling through role titles
- IntersectionObserver fade-in on scroll
- Hover lift on all cards
- Active nav link tracking via IntersectionObserver
- Projects section: 3 hardcoded featured cards + live GitHub API fetch for remaining repos
- Experience timeline
- Resume PDF download

## Structure

```
index.html        ← entire site (single file)
assets/
└── resume.pdf    ← downloadable CV
README.md
```

## Local preview

No build step needed. Just open `index.html` in a browser:

```bash
open index.html
```
