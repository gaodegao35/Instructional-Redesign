# Instructional-Redesign

Static HTML/CSS/JS prototypes for OLI Torus **Webpage** blocks.

This repo is used to prototype and revise interactive accounting learning activities before they are finalized for implementation.

### Root
- `intro-activity.html` — introductory financial statements activity (3-step: match, trace, connect)
- `1st_activity.html` — balance sheet identity activity (5-step progressive comparison)
- `simplified-example.html` — ExampleCo articulation exercise (3-layer, standalone; links to apple/)
- `homework.html` — Homework I

### module-1/
- `1.1-getting-organized.html` — Getting Organized

### module-4/
- `01-imposing-the-identity.html` — Imposing the Identity
- `02-two-snapshots-1.html` — The Balance Sheet as a Snapshot (activity: Snapshot or Explanation?)
- `02-two-snapshots-2.html` — What Changed Between the Two Dates (activities: Which Statement Explains the Change?, drag-and-drop)
- `02-two-snapshots-3.html` — Recognition, Classification, and Quantification (accordion)
- `03-three-flow-statements.html` — Three Flow Statements reading page with end-of-page match activity
- `04-how-fit-together.html` — How They Fit Together

### apple/
- `apple-example.html` — Apple FY2024 articulation exercise (links back to simplified-example.html)
- `apple-fy25-q3-p1.png`, `apple-fy25-q3-p2.png`, `apple-fy25-q3-p3.png` — source PDF pages

### entity-diagram/
- `entity-diagram.html` — entity boundary diagram (standalone)
- `entity-diagram-prompts.html` — Stuff, Rights, and Promises + writing prompts
- `homework.html` — homework / related page
- `reflect4_rick.html` — Rick’s original design reference

## Shared files

- `shared.css` — shared styling
- `shared.js` — shared logic/helpers
- `config.js` — configuration values
- image files (`.png`) — supporting visuals for activities

## Current working branch

- Main working branch for prototype revisions: `sarah-activity-edits`

## GitHub Pages preview

This repo is published through GitHub Pages.

Repo root:
- `https://sarahshlim.github.io/iframe-prototyping/`

Prototype pages:
- `https://sarahshlim.github.io/iframe-prototyping/reflect4.html`
- `https://sarahshlim.github.io/iframe-prototyping/reflect4_sarah.html`
- `https://sarahshlim.github.io/iframe-prototyping/entity-diagram.html`
- `https://sarahshlim.github.io/iframe-prototyping/entity-diagram-prompts.html`
- `https://sarahshlim.github.io/iframe-prototyping/homework.html`
- `https://sarahshlim.github.io/iframe-prototyping/m4_articulate1_sarah.html`
- `https://sarahshlim.github.io/iframe-prototyping/m4_balancesheet_sarah.html`
- `https://sarahshlim.github.io/iframe-prototyping/m4_snapshot_change_sarah.html`

## Notes on workflow

- `reflect4_sarah.html` is the main sandbox for design/content/layout revisions.
- `reflect4.html` should remain as a stable baseline reference unless intentional changes are needed.
- Most visual/layout revisions should be made in:
  - `reflect4_sarah.html`
  - `shared.css` (only when a shared styling change is necessary)
- Avoid changing `shared.js` or `config.js` unless the change truly requires logic updates.
### reflect4/
- `reflect4.html` — transaction sequencer
- `reflect4_rick.html` — Rick's original design variant

Shared: `shared.css`, `shared.js`, `config.js`

## Purpose of the Transaction Activity prototype ('System in Action: Simple Case' activity)

The goal of the transaction-sequencer activity is to help learners see the architecture of financial statements:

- the two balance sheets are snapshots of financial position at different dates
- the three flow statements (Statement of Changes in Equities, Cash Flow Statement, Income Statement) decompose the difference between the two balance sheets
- the Statement of Changes in Equities explains the full change in equities
- the Cash Flow Statement explains the full change in cash
- the Income Statement explains net income, which is one part of the change in equities
- `https://gaodegao35.github.io/Instructional-Redesign/intro-activity.html`
- `https://gaodegao35.github.io/Instructional-Redesign/1st_activity.html`
- `https://gaodegao35.github.io/Instructional-Redesign/module-1/1.1-getting-organized.html`
- `https://gaodegao35.github.io/Instructional-Redesign/module-4/01-imposing-the-identity.html`
- `https://gaodegao35.github.io/Instructional-Redesign/module-4/02-two-snapshots-1.html`
- `https://gaodegao35.github.io/Instructional-Redesign/module-4/02-two-snapshots-2.html`
- `https://gaodegao35.github.io/Instructional-Redesign/module-4/02-two-snapshots-3.html`
- `https://gaodegao35.github.io/Instructional-Redesign/module-4/03-three-flow-statements.html`
- `https://gaodegao35.github.io/Instructional-Redesign/module-4/04-how-fit-together.html`
- `https://gaodegao35.github.io/Instructional-Redesign/simplified-example.html`
- `https://gaodegao35.github.io/Instructional-Redesign/apple/apple-example.html`
- `https://gaodegao35.github.io/Instructional-Redesign/entity-diagram/entity-diagram.html`
- `https://gaodegao35.github.io/Instructional-Redesign/entity-diagram/entity-diagram-prompts.html`
- `https://gaodegao35.github.io/Instructional-Redesign/reflect4/reflect4.html`
- `https://gaodegao35.github.io/Instructional-Redesign/reflect4/reflect4_rick.html`

`https://sarahshlim.github.io/iframe-prototyping/reflect4_sarah.html`

## Status

This repo contains working prototypes and iterative revisions. Some files may be experimental or in progress.
