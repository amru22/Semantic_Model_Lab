# Facilitator Guide

## Lab title

Reuse Shared Semantic Models with the DIAD Semantic Model

## Duration

40 minutes (works in 35–45)

## Learning objectives

By the end, participants can:

1. Explain when shared model reuse is appropriate.
2. Build a thin report without rebuilding model logic.
3. Validate Build/workspace role behavior.
4. Identify downstream impact from central KPI changes.

## Instructor setup (before session)

1. Publish **DIAD semantic model** to source workspace.
2. Prepare target workspace for participant report publishing.
3. Configure access:
   - Authors: **Build** on DIAD model + **Contributor** in target workspace.
   - Consumers: **Viewer** only.
4. Prepare one viewer test account/group for permission validation.
5. Share the scenario card (`docs/scenario-card.md`) and templates folder.

## Timed agenda

### 1) Reuse triage (7 min)

- Teams choose: **reuse**, **extend**, or **new model**.
- Must justify via:
  - domain fit
  - security fit
  - data grain/refresh fit
- Capture in `templates/decision-log.md`.

### 2) Thin report build (12 min)

- Connect to DIAD shared model.
- Build one page with:
  - KPI card
  - trend visual
  - breakdown visual
  - slicer
  - at least one interaction

### 3) KPI consistency proof (6 min)

- Answer 2 KPI questions from report output.
- Prove official DIAD measures were used.

### 4) Permission simulation (8 min)

- Validate behavior for:
  - Author
  - Consumer
  - Optional over-privileged user
- Fill `templates/permissions-matrix.csv`.

### 5) Change-impact drill (5 min)

- Instructor announces a central measure change.
- Teams complete `templates/change-impact-response.md`.

### 6) Debrief (2 min)

- Collect submissions and score with `rubric/scoring-rubric.md`.

## Facilitator prompts

- What would make you avoid reusing this model?
- Where could Build permission become risky?
- How would you notify downstream report owners before KPI changes?

## Success criteria

Each team submits:

1. Reuse decision and rationale.
2. Published thin report using DIAD model.
3. Permission matrix.
4. Change-impact response.

