# Engineering Portfolio

A personal engineering portfolio built with Astro.

## Pages
- `/` — Home
- `/projects` — Project summaries and implementation status
- `/deep-dives` — Architecture, design decisions, validation and experiments
- `/experience` — Education, teaching and professional experience
- `/about` — Interests, technical toolkit and contact links

## Local development

Requires Node.js 20.19+ or 22.12+ (Node.js 24 LTS is also suitable).

```bash
npm install
npm run dev
```

Open the local URL printed by Astro, usually `http://localhost:4321/`.

## Build

```bash
npm run build
npm run preview
```

## Deploy to GitHub Pages

1. Create a GitHub repository named `engineering-portfolio`.
2. Push this project to the `main` branch.
3. In the repository, open **Settings → Pages**.
4. Set the build/deployment source to **GitHub Actions**.
5. The included workflow builds the Astro site and deploys `dist/` to GitHub Pages.

The configured site URL is `https://Lengfeng88.github.io`.

## Updating content

- Edit `src/pages/index.astro` for the home page.
- Edit `src/pages/projects.astro` for project summaries.
- Edit `src/pages/deep-dives.astro` for architecture and technical evidence.
- Edit `src/pages/experience.astro` for education and experience.
- Edit `src/pages/about.astro` for interests and contact information.
- Edit `src/styles/global.css` for typography, spacing, colors and responsive layout.

Keep planned architecture separate from completed implementation and measured results. Add performance numbers only when they can be reproduced and explained.