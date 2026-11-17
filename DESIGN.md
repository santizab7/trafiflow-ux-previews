# DESIGN.md — Trafilea Teaser (navy v2)

## Direction
**Mission-control console × product-reveal keynote.** Trafilea's operating system reporting on itself. Confident, data-forward, one electric signal color on a navy drench. Not editorial-serif, not SaaS-cream.

Named references for calibration: Bloomberg-terminal data density, a keynote product reveal's pacing, Vercel-grade dark restraint — recombined, not copied.

## Color (committed / drenched)
- `--navy` #081726 (body drench) · `--navy-2` #0B1F33 · `--panel` #0E2841 · `--ink-well` #050E18 (reveal panels)
- `--ink` #EAF2FA (headings) · `--ink-2` #B7C8DA (body, ≥4.5:1 on navy) · `--muted` #7C93AB (labels only, never body)
- `--green` #00C389 (the single voice color) · `--green-2` #19E39E (glow/peaks) · `--green-deep` #00875E
- Green is decisive, not hedged. Used for the signal, the peak, the action — not sprinkled.

## Type
- Display: **Bricolage Grotesque** (continuity with the house, off the reflex-reject list).
- Body/UI: **Hanken Grotesk** (clean grotesque; not Inter/DM/Plex).
- Data readouts only: **Geist Mono** — genuine console data (KPIs, timestamps, status), never decorative eyebrows.
- Scale: fluid clamp(), ≥1.25 steps. Light-on-dark gets +0.05–0.1 line-height.

## Anti-slop decisions (vs v1)
- **No per-section numbered eyebrows.** Numbering survives only where the content is a real sequence (revenue timeline; proof→wedge→flywheel).
- **No hero-metric card template.** $405M lives inside the headline + a console status line, not a big-number/small-label/gradient card.
- **No identical card grids.** Capabilities and stats use asymmetric / bento / list compositions with varied weight.
- **Mono is genuine,** justified by the console concept; not "technical costume."

## Signature
A generative **agent-network canvas** in the hero (drifting nodes, proximity links, traveling pulses) = the agentic-OS thesis as imagery. One orchestrated page-load. Everything else stays quiet.

## Motion
Orchestrated hero load; count-up on the trajectory peak; bars draw in; section reveals varied per content (no uniform fade-up reflex). Full `prefers-reduced-motion` fallbacks; canvas renders a static frame when reduced or printing.

## Print
Navy prints with exact colors; canvas freezes to a static frame; major sections page-break.
