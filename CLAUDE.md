# Still Here

A static site with no build step: `index.html` (landing page), `about.html` (story) and `app/index.html` (the app), deployed by Vercel from `main`. Each page keeps its CSS and JS inline; keep it that way unless asked.

## Design skills

Two design skills live in `.claude/skills/`. When they disagree, **antislop wins**:

- **antislop** (`antislop`, `antislop-ui`, `antislop-copywriting`, `antislop-human`, `antislop-layoutmobile`, `antislop-code`) sets the rules: accessibility, honest content, no em dashes, purpose for every technique, and the Delivery Gate.
- **awwwards** is a source of ideas: art direction, type, motion and layout techniques. Use them only where they pass antislop's purpose test and keep the brand below.

Known conflicts, already decided in favour of antislop:
- No uppercase wide-tracked labels; use sentence case.
- No bento grids, mesh or "gradient universe" backgrounds unless there's a written reason.
- No new animation, smooth-scroll or 3D libraries (GSAP, Lenis, Three.js) unless the owner asks.
- Don't split CSS/JS into separate files; the pages stay single-file.

The awwwards skill's reference notes are in `.claude/skills/awwwards/references/` (its SKILL.md says `~/.claude/skills/awwwards/references/`).

## Brand direction

The current look is the design direction: plum base, honey accent, leaf for good days, Pixelify Sans headings with Nunito body, and the cozy isometric pixel island with its sprites in `assets/sprites/`. Dials: ENERGY 2 / RHYTHM 2 / MOTION 2.
