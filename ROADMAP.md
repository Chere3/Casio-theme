# ROADMAP

## Quick wins (1-2 weeks)
- Add CI workflow to run `pnpm lint` and `pnpm format --check`.
- Add release checklist (version bump, changelog, VS Code Marketplace publish).
- Normalize screenshot naming and optimize image sizes.
- Add issue templates for bug reports and color token suggestions.

## Medium initiatives (1-2 months)
- Build palette token source (`tokens.json`) and generate theme JSON files from it.
- Add contrast audit script for common syntax/UI token groups.
- Add visual regression screenshot workflow for theme variants.

## Big bets (quarter)
- Introduce light variant family maintaining Casio identity.
- Add semantic token customization per language ecosystem.
- Build website/showcase page with side-by-side comparisons.

## Strategic rewrites
- Migrate manual theme files to source-of-truth token system + generator pipeline.
- Split metadata/publishing flow from color design source for cleaner maintenance.
- Introduce automated release pipeline with quality gates and marketplace publish checks.
