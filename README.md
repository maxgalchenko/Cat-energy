# Cat Energy

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?logo=sass&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=000)
![Gulp](https://img.shields.io/badge/Gulp-EB4A4B?logo=gulp&logoColor=white)
![Webpack](https://img.shields.io/badge/Webpack-2B3A42?logo=webpack&logoColor=8DD6F9)
![Babel](https://img.shields.io/badge/Babel-F9DC3E?logo=babel&logoColor=000)
![PostCSS](https://img.shields.io/badge/PostCSS-DD3A0A?logo=postcss&logoColor=white)

</div>

## Overview

Responsive marketing site and catalog for a pet nutrition brand. Static site built with a Gulp pipeline, optimized assets, and live-reload dev workflow.

## Key Features

- Gulp-based build: SCSS → CSS with Autoprefixer and CSSO, JS bundling via Webpack + Babel + Uglify
- Image optimization, including WebP generation for JPEG/PNG assets
- Live reload with BrowserSync and minified HTML/CSS/JS outputs

## Tech Stack

HTML5, SCSS, JavaScript (ES6), Gulp 4, Webpack 4, Babel 7, PostCSS/Autoprefixer, BrowserSync

## Architecture

Source in `src/` (`sass`, `js`, `img`, HTML). Build pipeline outputs to `docs/` for static hosting. Tasks: `dev` (serve + watch) and `build` (clean + optimize assets).

## Performance & Accessibility

Minified HTML/CSS/JS, image compression and WebP variants, and vendor prefixing via Autoprefixer. Semantic HTML markup with attention to basic keyboard and contrast considerations.

## Quality

- Linting: — • Formatting: Prettier
- Type safety: —
- Tests: —
- CI: — • Coverage: —

## Prerequisites

- Node.js: `18.17.0`

## Installation

```bash
git clone https://github.com/maxgalchenko/Cat-energy.git
cd Cat-energy
npm install
```

## Quick Start

```bash
npm run dev
# Production
npm run build
npm start
```

Open http://localhost:3000

## Available Scripts

- `npm run dev` – Gulp development server with live reload (use `npx gulp dev`)
- `npm run build` – Production build to `docs/` (use `npx gulp build`)
- `npm test` – Placeholder script; no tests configured

---

<div align="center">

Built with ❤️ by [Maksym Galchenko](https://github.com/maxgalchenko)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/galchenko-max/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-green?style=for-the-badge&logo=web)](https://portfolio-green-six-29.vercel.app/)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:galchenko.maksym@gmail.com)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</div>


