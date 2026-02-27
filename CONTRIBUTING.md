# Contributing

Thanks for helping improve Casio Theme.

## Setup
```bash
pnpm install
```

## Editing theme files
- Theme definitions live in `themes/*.json`.
- Keep naming consistent with existing variants.
- Prefer small, focused changes by token group (editor, syntax, terminal, etc.).

## Quality checks
Run before opening a PR:

```bash
pnpm lint
pnpm format
```

## Branch and commit style
- Branches: `feat/*`, `fix/*`, `chore/*`, `docs/*`
- Commits: Conventional Commits (`feat:`, `fix:`, `docs:`, etc.)

## PR checklist
- [ ] Changes are scoped and explained.
- [ ] Screenshots included when visual output changes.
- [ ] Lint/format commands executed locally.
- [ ] Changelog updated if user-facing behavior changed.
