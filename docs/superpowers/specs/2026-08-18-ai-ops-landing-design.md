# AI Ops landing page — design spec

**Date:** 2026-08-18 · **Repo:** np-founders/ai-ops · **URL:** https://np-founders.github.io/ai-ops/

## Purpose

Public showcase of the five AI workflows the nullplatform team runs on its own
production, aimed at prospects and the internal team. English copy, visual
style cloned from the nullplatform.com home.

## Source content

`Documento sin título.pdf` (12 pages): Deployments Analyzer, Library Analyzer,
Costs, Self-Documenter (WIP), Smart Checklists. Screenshots extracted from the
PDF at 2048px and published as-is (approved by Gabriel).

## Tech

Static site, no build step: `index.html` + `styles.css` + `assets/*.png`,
served by GitHub Pages from `main`. Public repo (Pages requirement).

## Brand tokens (measured on nullplatform.com)

- Fonts: Instrument Sans (display+body), JetBrains Mono (data chips)
- Ink `#212B36`, body gray `#637381`, page bg `#F4F6FA`, accent `#3E8BFF`,
  hero/footer dark `#0B0F17`
- H1 82px/700, letter-spacing -0.035em; H2 48px/300; eyebrows 12px/700
  uppercase, ls 0.16em, blue; buttons 14px/600 white on blue, radius 6px
- Devices: inverted black-highlight phrase inside section H2s; alternating
  media-card + text feature rows; white cards radius 16px with subtle border

## Page structure

1. Dark hero: eyebrow pill, H1 with blue phrase, subhead, CTAs (Book a demo →
   nullplatform.com/contact-us, See the workflows → anchor), workflow chip nav
2. Deployments Analyzer (two rows: deploy analysis + engineering insights)
3. Library Analyzer
4. Cost Intelligence
5. Self-Documenter — dark band, "Experimental" badge
6. Smart Checklists
7. Closing CTA dark band + footer

Each section: blue eyebrow, headline, one paragraph, 3–4 bullets, screenshots
in browser-frame cards. Scroll-reveal animation honoring
`prefers-reduced-motion`. Responsive to mobile.
