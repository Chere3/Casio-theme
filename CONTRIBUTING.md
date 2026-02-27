# Contributing to Casio Theme

Thanks for helping improve Casio Theme.

## Local setup

```bash
pnpm install
```

## Development workflow

1. Create a branch from `main`.
2. Edit theme files in `themes/`.
3. Run local checks before pushing.

```bash
pnpm lint
pnpm format
```

## Pull request checklist

- [ ] Theme changes are intentional and tested in VS Code.
- [ ] JSON files are formatted.
- [ ] README/CHANGELOG updated when relevant.
- [ ] PR includes screenshots for visual changes.

## Commit style

Use Conventional Commits when possible:
- `feat:` new palette/variant
- `fix:` bug or contrast issue
- `docs:` documentation-only updates
- `chore:` maintenance
