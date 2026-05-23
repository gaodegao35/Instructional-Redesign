# Instructional-Redesign

Static pages (minimal chrome) for OLI Torus **Webpage** blocks.

## Pages

### Module-3/
- `01-imposing-the-identity.html` — Imposing the Identity
- `02-two-snapshots-1.html` — The Balance Sheet as a Snapshot (activity: Snapshot or Explanation?)
- `02-two-snapshots-2.html` — What Changed Between the Two Dates (activities: Which Statement Explains the Change?, drag-and-drop)
- `02-two-snapshots-3.html` — Recognition, Classification, and Quantification (accordion)
- `03-three-flow-statements.html` — Three Flow Statements reading page with end-of-page match activity
- `04-how-fit-together.html` — How They Fit Together
- `05-1st_activity.html` — Balance Sheet Identity (5-step progressive comparison)
- `06-structure-activity.html` — Financial Statement Structure (articulation activity)

Shared: `shared.css`, `shared.js`, `config.js`

## GitHub Pages

Deploy from **`main`** / **`/(root)`**, then for example:

- `https://gaodegao35.github.io/Instructional-Redesign/Module-3/01-imposing-the-identity.html`
- `https://gaodegao35.github.io/Instructional-Redesign/Module-3/02-two-snapshots-1.html`
- `https://gaodegao35.github.io/Instructional-Redesign/Module-3/02-two-snapshots-2.html`
- `https://gaodegao35.github.io/Instructional-Redesign/Module-3/02-two-snapshots-3.html`
- `https://gaodegao35.github.io/Instructional-Redesign/Module-3/03-three-flow-statements.html`
- `https://gaodegao35.github.io/Instructional-Redesign/Module-3/04-how-fit-together.html`
- `https://gaodegao35.github.io/Instructional-Redesign/Module-3/05-1st_activity.html`
- `https://gaodegao35.github.io/Instructional-Redesign/Module-3/06-structure-activity.html`

## CSS Convention

> **All pages must use `shared.css` as the single source of truth for styles.**

- Every page links `../shared.css` (or `./shared.css` at root level).
- **Do not** redefine colors, typography, spacing, or component styles locally if they are already in `shared.css`.
- If a page requires inline `<style>` for page-specific layout or one-off overrides, add a comment at the top of that block explaining why it cannot live in `shared.css`. Example:
  ```css
  /* NOTE: page-specific two-column balance sheet grid — not shared across pages */
  .bs-two-col { ... }
  ```
- When adding a new reusable component, add it to `shared.css` first, then reference it in the page.
- Dark mode overrides belong in `shared.css` unless they target a class that is itself page-specific.

## Update

Copy updated files from your prototype and push to `main`.
