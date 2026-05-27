1) How to read each page .md and implement .html
Treat each page X.md as the source of truth for:
page order
section structure
scenario text
activity requirements
When the .md contains content in [...], interpret it as activity design specs and build full activity content from it (items, prompts, options, feedback, logic).
Keep section order in HTML aligned to markdown order:
header/context
scenario
activity
callout
next scenario/activity
Convert markdown prose into learner-facing HTML text directly (light editing for readability only).

2) Styling/component rules you want
Use only components already defined in shared.css.
Do not create new visual components or new custom style systems.
Prefer existing shared classes such as:
text-block, section-tag, section-title, section-sub
prose, info-box, callout
section-card, activity-card, activity-tag, activity-title, activity-desc
shared activity classes (dnd-*, mcq-*, btn-*, etc.)
If a style similar to a requested look already exists in shared.css, use that class directly.

3) Scenario block design preference (latest)
Scenario sections should be visually salient using shared styles.
Current preferred style for Scenario content:
section-tag = “Scenario”
body inside analogy-box (purple emphasized box, matching your screenshot style)
Avoid plain paragraph-only scenario rendering unless requested.

4) Dark mode requirement
Pages must support dark mode through shared.css conventions.
Reuse shared components that already have dark mode support.
Avoid adding local dark-mode-only custom styles unless truly necessary.

5) Activity implementation expectations
Build complete interactive behavior from md specs, not placeholder content.
Typical pattern:
Activity 1: drag/drop + validation + reset + progress
Activity 2: MCQ tied to Activity 1 output (e.g., group names)
feedback text exactly follows provided wording when specified
Use shared classes for activity UI and states (correct/wrong/locked/feedback).

6) Local preview workflow
Run local server from repo root so relative assets load correctly:
python3 -m http.server 8000
Open pages via localhost (not file://), e.g.:
http://localhost:8000/Module-1/page%201.html

7) Repository/path handling lessons
There are both module-1/ and Module-1/ paths in this repo history.
Confirm and edit the intended file path each time before changes.
Keep page updates targeted to the requested file only.
Quick “agent instruction” version for your README
Read page X.md first; implement page X.html strictly in that order/structure.
Treat bracketed [...] text as implementation specs for activities.
Use only shared.css components; no new custom visual components.
Use section-tag + analogy-box for all Scenario blocks unless I say otherwise.
Ensure dark mode compatibility via shared styles.
Build full activity logic (not placeholders), including reset/progress/feedback.
Preview through localhost from repo root.