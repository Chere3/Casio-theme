# Contributing

Thanks for helping improve **Casio Theme**.

## Branch naming
Use one of the following formats:
- `feat/<scope>-<description>`
- `fix/<scope>-<description>`
- `chore/<scope>-<description>`
- `docs/<scope>-<description>`

## Commit messages
Use Conventional Commits, for example:
- `feat(theme): add semantic token override for rust`
- `fix(colors): improve comment contrast`
- `docs(readme): clarify installation steps`

## Local setup
```bash
pnpm install
```

## Validation checklist
Before opening a PR, run:
```bash
pnpm lint
pnpm format
```

## Pull request checklist
- [ ] Change is scoped and explained.
- [ ] Screenshots added for visual changes.
- [ ] `CHANGELOG.md` updated when release-impacting.
- [ ] Lint/format completed.
- [ ] Roadmap/docs updated when introducing new direction.

## PR template sections
1. Summary
2. Visual impact (before/after)
3. Validation
4. Risk and rollback
5. Follow-up tasks
