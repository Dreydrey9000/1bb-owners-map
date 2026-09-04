# Changelog

## [2026-09-04] — Favicon + head polish ("and everything")

### Added
- `assets/favicon.svg` — the app icon's 4-piece mark in brass (same geometry as app.1bbclub.com's blue icon, club palette) — why: brand family without palette clash
- `assets/favicon.ico` (16/32/48 via PIL) + `assets/apple-touch-icon.png` (180 via rsvg-convert) — fallbacks for Safari/iOS
- `assets/og-card.png` — custom 1200x630 share card (dark ground, brass rule frame, "Talk once a week. We do the other forty hours.", mark right) — why: the screenshots are near-square and would crop badly in X/LinkedIn wide cards
- Full head set on both pages: description, theme-color #0F1011, favicon links, apple-touch-icon, Open Graph (title/description/url/image/alt), Twitter summary_large_image

### Verified
- Mark visually checked at 64px; favicon renders in Safari tab; all 4 assets + meta tags confirmed 200/live on owners.1bbclub.com

## [2026-09-04] — Math section restructured to price ladder

### Changed
- Math section in BOTH versions: left column is now a 3-rung price ladder (agency $3,000 to $8,000 in drain gray, The Coach $1,000/mo, The Mastermind $1,000/mo in brass) with a "detailed at the bottom of this page" note; right panel is The Owners Club — price slot now reads "Everything" with subline "THE COACHING + THE MASTERMIND + THE APP" — why: Drey wanted the math to show the full price ladder with the club as the everything-option
- Added containment bullet to the club panel: "The $1,000 coaching and the $1,000 mastermind, both included" — why: makes the value stack explicit ($2K of standalone value inside the club)

### Verified
- New section Safari-screenshotted locally before deploy; deployed to owners.1bbclub.com + pages.dev + GitHub mirror, all serving the updated HTML (200s confirmed)

## [2026-09-04] — Initial build + deploy

### Added
- `v1-pillar-map.html` — faithful recreation of Kevin's owners-map site (1bb-owners-map.vercel.app) with proper HTML5 document wrapper — why: it's the base Kevin wants iterated on
- "Two ways in the door" section with Kevin's two requested standalone offers — The Coach ($1K/mo, content or business lane) and The Mastermind ($1K/mo, owners + events) — why: Kevin asked for exactly these two adds
- `v2-visual-merge.html` — the merge version: Kevin's copy + app.1bbclub.com's show-don't-tell approach (hero device-frame composition, embedded 24s narrated trailer, per-pillar product screenshots, "AI drafts. You review." control section, member proof cards) — why: Drey's site wins on visuals, Kevin's wins on copy; this is both
- `assets/` — 8 showcase screenshots + trailer mp4 + vtt captions pulled from app.1bbclub.com (all verified publicly reachable) — why: self-contained folder that works offline and deploys anywhere
- README.md — how to view/deploy + the design tokens

### Verified
- Both pages screenshotted live in Safari (desktop full-scroll + mobile-width): hero, math, trailer, all three pillars, control, proof, doors, guarantee, CTA all render with scroll-reveal animations firing
