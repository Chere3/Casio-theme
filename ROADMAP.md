# ROADMAP

## Quick wins (0-4 weeks)
- Add contributor onboarding docs (`CONTRIBUTING.md`) with local setup and release checklist.
- Add CI for dependency install + JSON/theme validation on pull requests.
- Standardize npm scripts (`lint`, `lint:fix`, `format`, `format:check`, `validate`).
- Expand README with compatibility matrix and troubleshooting.

## Medium-term improvements (1-2 months)
- Add visual regression snapshots for theme previews to detect accidental palette drift.
- Publish a changelog automation flow (release notes from conventional commits).
- Introduce semantic versioning guardrails for VS extension releases.
- Add issue templates for bug reports and palette requests.

## Big bets (1-2 quarters)
- Build a token-driven palette system and generate all six theme variants from shared tokens.
- Add accessibility contrast checks (WCAG-inspired thresholds for syntax scopes).
- Add automated packaging and publish pipeline for Visual Studio Marketplace releases.

## Strategic rewrites
- Refactor static JSON themes into a build pipeline (TypeScript + schema validation).
- Split theme foundations (syntax, UI, semantic tokens) to make experimentation safer.
- Create a docs site with side-by-side screenshots across language ecosystems.
