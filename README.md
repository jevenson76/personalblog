# Personal Blog

This repository hosts a small blog built with [Astro](https://astro.build). The layout uses modern gradients and animations inspired by Linear.app, giving the site a polished feel while remaining minimal.

## Getting Started

Make sure you have network access to the npm registry so that dependencies can be downloaded. Install packages and start the development server with:

```bash
npm install
npm run dev
```

The dev server runs on `http://localhost:4321` by default.

## Dark Mode

The site automatically follows your system preference for light or dark mode. In `src/styles/global.css` a `@media (prefers-color-scheme: dark)` block overrides the color variables and backgrounds used by the rest of the stylesheet. Meta tags in `src/components/BaseHead.astro` also advertise `color-scheme: light dark` and provide matching `theme-color` values. No additional configuration is required; the browser toggles themes based on the user's setting.

