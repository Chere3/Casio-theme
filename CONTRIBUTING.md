# Contributing to Casio Theme

Thanks for helping improve Casio Theme.

## Prerequisites
- Node.js 20+
- pnpm 9+

## Local setup
```bash
pnpm install
pnpm run validate
```

## Development workflow
1. Create a feature branch from `main`.
2. Update theme JSON files under `themes/`.
3. Run formatting and linting:
   ```bash
   pnpm run format
   pnpm run lint
   ```
4. If visuals changed, update screenshots in `public/` and reference them in README.
5. Commit with clear, conventional-style messages.

## Pull request checklist
- [ ] Theme files are formatted.
- [ ] `pnpm run validate` passes.
- [ ] README/screenshots are updated when visuals changed.
- [ ] Changes are scoped and explained in PR description.

## Release checklist (maintainers)
- [ ] Bump version in `package.json`.
- [ ] Update `CHANGELOG.md`.
- [ ] Validate extension metadata and icon paths.
- [ ] Publish package and verify marketplace listing.
