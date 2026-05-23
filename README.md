# Instructional-Redesign

Static pages (minimal chrome) for OLI Torus **Webpage** blocks.

## Pages

### Root
- `intro-activity.html` — introductory financial statements activity (3-step: match, trace, connect)
- `simplified-example.html` — ExampleCo articulation exercise (3-layer, standalone; links to apple/)
- `homework.html` — Homework I

### module-1/
- `1.1-getting-organized.html` — Getting Organized

### Module-3/
- `01-imposing-the-identity.html` — Imposing the Identity
- `02-two-snapshots-1.html` — The Balance Sheet as a Snapshot (activity: Snapshot or Explanation?)
- `02-two-snapshots-2.html` — What Changed Between the Two Dates (activities: Which Statement Explains the Change?, drag-and-drop)
- `02-two-snapshots-3.html` — Recognition, Classification, and Quantification (accordion)
- `03-three-flow-statements.html` — Three Flow Statements reading page with end-of-page match activity
- `04-how-fit-together.html` — How They Fit Together
- `05-1st_activity.html` — Balance Sheet Identity (5-step progressive comparison)
- `06-structure-activity.html` — Financial Statement Structure (articulation activity)

### apple/
- `apple-example.html` — Apple FY2024 articulation exercise (links back to simplified-example.html)
- `apple-fy25-q3-p1.png`, `apple-fy25-q3-p2.png`, `apple-fy25-q3-p3.png` — source PDF pages

### entity-diagram/
- `entity-diagram.html` — entity boundary diagram (standalone)
- `entity-diagram-prompts.html` — Stuff, Rights, and Promises + writing prompts

### reflect4/
- `reflect4.html` — transaction sequencer
- `reflect4_rick.html` — Rick's original design variant

Shared: `shared.css`, `shared.js`, `config.js`

## GitHub Pages

Deploy from **`main`** / **`/(root)`**, then for example:

- `https://gaodegao35.github.io/Instructional-Redesign/intro-activity.html`
- `https://gaodegao35.github.io/Instructional-Redesign/simplified-example.html`
- `https://gaodegao35.github.io/Instructional-Redesign/module-1/1.1-getting-organized.html`
- `https://gaodegao35.github.io/Instructional-Redesign/Module-3/01-imposing-the-identity.html`
- `https://gaodegao35.github.io/Instructional-Redesign/Module-3/02-two-snapshots-1.html`
- `https://gaodegao35.github.io/Instructional-Redesign/Module-3/02-two-snapshots-2.html`
- `https://gaodegao35.github.io/Instructional-Redesign/Module-3/02-two-snapshots-3.html`
- `https://gaodegao35.github.io/Instructional-Redesign/Module-3/03-three-flow-statements.html`
- `https://gaodegao35.github.io/Instructional-Redesign/Module-3/04-how-fit-together.html`
- `https://gaodegao35.github.io/Instructional-Redesign/Module-3/05-1st_activity.html`
- `https://gaodegao35.github.io/Instructional-Redesign/Module-3/06-structure-activity.html`
- `https://gaodegao35.github.io/Instructional-Redesign/apple/apple-example.html`
- `https://gaodegao35.github.io/Instructional-Redesign/entity-diagram/entity-diagram.html`
- `https://gaodegao35.github.io/Instructional-Redesign/entity-diagram/entity-diagram-prompts.html`
- `https://gaodegao35.github.io/Instructional-Redesign/reflect4/reflect4.html`
- `https://gaodegao35.github.io/Instructional-Redesign/reflect4/reflect4_rick.html`

## Update

Copy updated files from your prototype and push to `main`.

**Note:** For a second Torus **Webpage** block, point it at `entity-diagram/entity-diagram-prompts.html` if you want prompts on a separate course page. Prompt answers use the same `localStorage` key as before (`prework_reflect_entity`) only when both pages are served from the **same origin** (same GitHub Pages site).
