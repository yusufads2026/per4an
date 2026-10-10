# Per4an — Premium Editorial Redesign

A responsive English-language editorial site for Indonesian destinations, food, culture, craft, and thoughtful travel. The build script generates 40 standalone article pages, targeting 1,200–1,500 words each, plus the homepage, information pages, sitemap, and robots.txt.

## Cloudflare Pages settings
- Repository: `yusufads2026/per4an`
- Production branch: `main`
- Build command: `npm run build`
- Build output directory: `dist`

The site has no runtime framework or external package dependencies. Once a Cloudflare Pages project is connected to this GitHub repository, commits to `main` can trigger builds automatically. Cloudflare supplies the actual `*.pages.dev` address after a successful deployment; it cannot be pre-created from GitHub alone.

Editorial note: These are general travel and culture guides. Verify current official/local details before publishing time-sensitive claims. Images load from Unsplash.
