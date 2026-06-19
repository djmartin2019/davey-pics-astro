# DaveyPics Studio

Static portfolio site for **DaveyPics Studio** — Houston-area wildlife photography by David Martin. The homepage introduces the work, previews future sections (gallery, bird index, blog, locations), and serves as the foundation for a larger field archive.

Based in Humble, Texas. Focused on birds and wildlife across the Houston area and Southeast Texas — from Jesse H. Jones Park and Brazos Bend to the Galveston coast.

## Live sections (homepage)

The site is currently a single-page landing experience with anchor navigation:

| Section | Description |
| --- | --- |
| **Gallery** | Editorial grid of featured wildlife photographs |
| **Bird Index** | Species cards — a preview of a future photographed-species index |
| **Blog** | Article previews for Houston wildlife photography writing |
| **Locations** | Photography location guides (Jesse H. Jones Park, Brazos Bend, Galveston) |
| **About** | Background on David Martin and Houston-area wildlife photography |

## Tech stack

- [Astro](https://astro.build) 6 — static site generation
- [Tailwind CSS](https://tailwindcss.com) 4 — styling via `@tailwindcss/vite`
- No CMS or dynamic routes yet — content is defined in Astro components/pages

## Project structure

```text
/
├── public/
│   └── images/          # Wildlife photography assets
├── src/
│   ├── components/
│   │   └── Header.astro # Site nav + mobile hamburger menu
│   ├── layouts/
│   │   └── Layout.astro # Base HTML shell, fonts, meta
│   ├── pages/
│   │   └── index.astro  # Homepage
│   └── styles/
│       └── global.css   # Tailwind + design tokens
├── astro.config.mjs
└── package.json
```

## Commands

Run from the project root:

| Command | Action |
| --- | --- |
| `npm install` | Install dependencies |
| `npm run dev` | Start dev server at [localhost:4321](http://localhost:4321) |
| `npm run build` | Build static site to `./dist/` |
| `npm run preview` | Preview the production build locally |

Requires **Node.js >= 22.12.0**.

## Links

- **Photography:** [Instagram @davey.pics](https://www.instagram.com/davey.pics)
- **Built by:** [DJM Tech](https://djm-tech.dev/)

## Roadmap

Planned additions beyond the current homepage:

- Full gallery pages
- Bird index with individual species entries
- Field journal / blog posts
- Location guides for photographers and birders
