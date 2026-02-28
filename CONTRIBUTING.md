# Contributing

Thanks for helping improve **Casio Theme**.

## Local setup

```bash
pnpm install
pnpm run lint
pnpm run format:check
```

## Branching and commits

- Branch naming: `feat/<topic>`, `fix/<topic>`, `chore/<topic>`, `refactor/<topic>`
- Commit format (conventional commits):
  - `feat(theme): add ...`
  - `fix(theme): correct ...`
  - `chore(ci): improve ...`

## Pull requests

1. Keep PRs focused on one concern.
2. Add before/after screenshots when changing theme visuals.
3. Confirm CI passes.
4. Describe verification steps in the PR body.

## Release note guidance

Document any user-visible color/token changes in `CHANGELOG.md`.
