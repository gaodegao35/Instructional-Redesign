# Instructional-Redesign

Static pages (minimal chrome) for OLI Torus **Webpage** blocks.

**Live site (GitHub Pages):** [https://gaodegao35.github.io/Instructional-Redesign/](https://gaodegao35.github.io/Instructional-Redesign/)

Published from the **`main`** branch, root folder (`/`). Only files on `main` appear at these URLs.

Shared assets (repo root): `shared.css`, `shared.js`, `config.js`

## Pages

### Module-1/
- `1.1-getting-organized.html` — Getting Organized (entity boundary, assets & liabilities activities)

### Module-2/
- `reflect4_sarah.html` — Transaction articulation activity (React; opening → decomposition → closing balance sheets)

### Module-3/
- `01-imposing-the-identity.html` — Imposing the Identity
- `02-two-snapshots-1.html` — The Balance Sheet as a Snapshot (activity: Snapshot or Explanation?)
- `02-two-snapshots-2.html` — What Changed Between the Two Dates (activities: Which Statement Explains the Change?, drag-and-drop)
- `02-two-snapshots-3.html` — Recognition, Classification, and Quantification (accordion)
- `03-three-flow-statements.html` — Three Flow Statements reading page with end-of-page match activity
- `04-how-fit-together.html` — How They Fit Together
- `05-1st_activity.html` — Balance Sheet Identity (5-step progressive comparison)
- `06-structure-activity.html` — Financial Statement Structure (articulation activity)

## GitHub Pages URLs

Base: `https://gaodegao35.github.io/Instructional-Redesign/`

### Module-1
- [1.1-getting-organized.html](https://gaodegao35.github.io/Instructional-Redesign/Module-1/1.1-getting-organized.html)

### Module-2
- [reflect4_sarah.html](https://gaodegao35.github.io/Instructional-Redesign/Module-2/reflect4_sarah.html)

### Module-3
- [01-imposing-the-identity.html](https://gaodegao35.github.io/Instructional-Redesign/Module-3/01-imposing-the-identity.html)
- [02-two-snapshots-1.html](https://gaodegao35.github.io/Instructional-Redesign/Module-3/02-two-snapshots-1.html)
- [02-two-snapshots-2.html](https://gaodegao35.github.io/Instructional-Redesign/Module-3/02-two-snapshots-2.html)
- [02-two-snapshots-3.html](https://gaodegao35.github.io/Instructional-Redesign/Module-3/02-two-snapshots-3.html)
- [03-three-flow-statements.html](https://gaodegao35.github.io/Instructional-Redesign/Module-3/03-three-flow-statements.html)
- [04-how-fit-together.html](https://gaodegao35.github.io/Instructional-Redesign/Module-3/04-how-fit-together.html)
- [05-1st_activity.html](https://gaodegao35.github.io/Instructional-Redesign/Module-3/05-1st_activity.html)
- [06-structure-activity.html](https://gaodegao35.github.io/Instructional-Redesign/Module-3/06-structure-activity.html)

## CSS Convention

> **All pages must use `shared.css` as the single source of truth for styles.**

- Module pages link `../shared.css` (and `../shared.js` / `../config.js` when needed).
- **Do not** redefine colors, typography, spacing, or component styles locally if they are already in `shared.css`.
- If a page requires inline `<style>` for page-specific layout or one-off overrides, add a comment at the top of that block explaining why. Example:
  ```css
  /* NOTE: page-specific two-column balance sheet grid — not in shared.css */
  .bs-two-col { ... }
  ```
- **Dark mode:** reusable components (`.prose`, `.mc-opt`, `.btn-*`, `.bs-two-col`, etc.) → add overrides in `shared.css` under `@media (prefers-color-scheme: dark)`. Classes used on only one page → keep light and dark styles in that page’s inline `<style>`.

## Update

Copy updated files from your working branch, push to **`main`**, and wait a minute or two for GitHub Pages to refresh.
