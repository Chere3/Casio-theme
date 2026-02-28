# ROADMAP

## Quick wins (0-2 weeks)
- Add CI workflow to validate theme JSON and repository hygiene on every PR.
- Add contributor onboarding docs with branch/commit/PR conventions.
- Normalize repository metadata and maintenance commands.

## Medium bets (2-6 weeks)
- Add screenshot generation automation for each theme variant.
- Add semantic release workflow for marketplace-ready versioning and changelog generation.
- Add issue/PR templates for bug reports, visual regressions, and palette proposals.

## Big bets (1-2 quarters)
- Build a design token source (`tokens/*.json`) and generate all theme files from tokens.
- Introduce accessibility contrast checks per syntax scope.
- Add compatibility matrix for VS versions and language packs.

## Strategic rewrites
- Move to a token-driven architecture so visual updates are deterministic and testable.
- Split theme variants into composable layers (base UI + syntax + accents).
- Introduce a validation pipeline to catch malformed scopes, duplicate keys, and low-contrast pairs before publish.
