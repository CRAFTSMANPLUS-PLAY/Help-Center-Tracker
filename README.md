# Hugo PLAY Enablement Track

Internal CS training tracker for Hugo Aguilera. Built to support a structured 4-week ramp on PLAY, INTELLIGENCE, and ANALYTICS — so Hugo can operate independently on partner onboarding, support, and escalation.

## What it is

A single-page static web app that tracks Hugo's progress through 20 study sessions across 4 weeks. Each session includes assigned documentation from [help.craftsmanplus.com](https://help.craftsmanplus.com/), a hands-on application task, a rubric check question, and fields for notes and open questions.

Progress, confidence scores, rubric ratings, and certification status all save to the browser via localStorage.

## How to use it

**Hugo** — open the Roadmap tab each day, expand the current week, and work through the session. Mark your status, score your confidence, and log notes and open questions before closing out.

**Shane** — check the dashboard snapshot at the top of the Roadmap tab for a quick read on where Hugo is. Use the Rubric Scores tab to rate Hugo's skill development by category. The Certification tab is the final gate — all 15 items checked means Hugo is client-ready.

## Structure

| Week | Focus |
|------|-------|
| 1 | Platform Foundation + Core PLAY Workflow |
| 2 | PLAY Feature Depth + Support Readiness |
| 3 | INTELLIGENCE + ANALYTICS |
| 4 | Applied CS Certification |

## Deployment

This is a static GitHub Pages site. No backend, no dependencies beyond a Google Fonts CDN call for Poppins.

To deploy: push `index.html` to any GitHub repo and enable Pages under **Settings → Pages → branch `main` / root**.

## Editing the roadmap

All session content lives in the `WEEKS` array at the top of the `<script>` block in `index.html`. Sessions, study items, application tasks, and rubric questions can all be edited there without touching the UI code.

## Support documentation

[help.craftsmanplus.com](https://help.craftsmanplus.com/)
