# 1BB Owners Club — Two Website Versions

Built 2026-09-04 for Drey, from Kevin's `1bb-owners-map.vercel.app` + Kevin's requested additions
+ the visual approach from `app.1bbclub.com`.

## The files

| File | What it is |
|------|-----------|
| `v1-pillar-map.html` | Kevin's site recreated 1:1 (copy, layout, dark/brass theme) **plus** a new "Two ways in the door" section with his two requested offers |
| `v2-visual-merge.html` | Same copy foundation, rebuilt to **show the product** — real app screenshots in device frames, the narrated trailer, member proof, exactly like app.1bbclub.com does |
| `assets/` | The 8 app screenshots + trailer video + captions, pulled from app.1bbclub.com/showcase (all public, verified 200) |

## What Kevin asked to add (in both versions)

1. **The Coach — $1K/month** — standalone coaching, pick a lane: content or business
2. **The Mastermind — $1K/month** — business owners room + in-person events

Both live in a "Two ways in the door" section placed after the three pillars, upselling to the
full Owners Club ("the app, the coaching, and the room, together").

## View locally

Open either HTML file in a browser — zero dependencies, no build step. `assets/` must stay in the
same folder (images + trailer are referenced with relative paths).

## Deploy

Any static host (Vercel/Cloudflare Pages): upload the folder as-is. If you'd rather hotlink the
showcase images instead of bundling them, they're permanently at
`https://app.1bbclub.com/showcase/<name>.png`.

## Design tokens (inherited from Kevin's site — matches the 1BB brand)

- Ground `#0F1011` · Surface `#16181A` · Brass `#C9A24C` · Ink `#ECEBE7`
- Fonts: Archivo (headlines) · Newsreader italic (claims) · Martian Mono (tags/prices)
- Light mode auto-supported via `prefers-color-scheme`
