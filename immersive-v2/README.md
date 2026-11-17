# Immersive Portfolio V2 — isolated migration prototype

This directory is intentionally NOT connected to GitHub Pages production. The existing root site and all existing assets remain untouched.

## Verified audit (2026-11-16)
- Production repo: SidneyMagana/sidneymagana.github.io; default branch main.
- Root index.html is a single large HTML document with overlapping inline CSS and scripts.
- Existing navigation and content live at /about/, /portfolio/, /contact/, /services/, /sidsgermination/ and other routes. Preserve them.
- Existing SM logo path is /assets/brand/logo%20without%20backround.png; do not redraw.
- The root homepage already supports a skip link, menu toggle, motion pause and reduced-motion preference; retain these behaviors.
- /portfolio/index.html contains professional and creative work; full asset inventory and route verification remain pending.

## Five priorities
1. Stronger creative identity and cinematic visual hierarchy.
2. Verified Living Archive media as flagship, labeled speculative.
3. Outcome-grounded professional case studies.
4. Shared brand/navigation/components.
5. Accessible responsive architecture and deployment checks.

## Phased release plan
- Phase 0: audit routes, assets, URLs, image/video sizes and approved logo; capture production baseline.
- Phase 1: prototype design system and homepage here, without changing main.
- Phase 2: inventory Living Archive assets and create verified media story; no invented assets or metrics.
- Phase 3: migrate all pages and links, preserve legacy paths and metadata; implement redirects only after testing.
- Phase 4: add GSAP only for editorial scroll moments and React Three Fiber only if a verified 3D interaction adds value; always offer static/reduced-motion fallback.
- Phase 5: build and run responsive, keyboard, accessibility, media-loading, performance and route smoke tests. Deploy only after review.

## Local preview
Run `npm install`, then `npm run dev` inside this directory. This is a partial working React/Vite prototype, not a production-ready replacement. Current links intentionally point to existing published pages. The Living Archive media slot is intentionally not populated until exact asset paths are verified.
