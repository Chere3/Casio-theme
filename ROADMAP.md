# ROADMAP

## Quick wins
- Add contributor docs for editing theme tokens and validating contrast changes.
- Add CI to run `pnpm lint` and `pnpm format --check` on pull requests.
- Refresh README install instructions for Visual Studio Code marketplace flow.
- Add before/after screenshots for each bundled theme variant.

## Medium
- Introduce semantic token coverage matrix (TS, Rust, Python, Markdown, JSON).
- Add accessibility pass for WCAG-aware contrast levels in core token groups.
- Add release checklist and changelog automation for marketplace-ready publishing.
- Add issue templates for bug reports and theme requests.

## Big bets
- Build theme preview docs site with token explorer and live examples.
- Add design token source-of-truth (JSON) and generate all variant themes from it.
- Create dedicated light variant family with consistent Casio identity.

## Strategic rewrites
- Move to a token pipeline (Style Dictionary/custom scripts) that compiles all theme JSON outputs.
- Add visual regression snapshots for syntax scopes to prevent accidental palette drift.
- Introduce versioned design system docs so theme changes are intentional and reviewable.
