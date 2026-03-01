# 🕹️ Casio Theme

A retro-inspired Visual Studio color theme focused on readability, contrast balance, and long coding sessions.

## Why Casio Theme
- Distinct palette inspired by classic Casio aesthetics.
- Multiple dark variants to match different contrast preferences.
- Language-friendly syntax colors for day-to-day development.

## Included themes
- Casio Theme
- Casio Theme Darker
- Casio Theme Darker Flat
- Casio Theme Flat
- Casio Theme Dark Pro
- Casio Theme High Contrast

## Installation (Visual Studio)
1. Open **Extensions → Manage Extensions**.
2. Search for **Casio Theme**.
3. Install and restart Visual Studio.
4. Select via **Tools → Options → Environment → General → Color theme**.

## Screenshots
![Rust](./public/Dark.png)
![HTML/CSS](./public/html_and_css.png)
![TypeScript](./public/typescript.png)

## Development
### Requirements
- Node.js 20+
- pnpm 9+

### Commands
```bash
pnpm install
pnpm run lint          # lint JSON/theme files
pnpm run format        # auto-format theme files
pnpm run format:check  # verify formatting only
pnpm run validate      # lint + formatting checks
```

## Release flow
1. Update theme files and screenshots.
2. Run `pnpm run validate`.
3. Bump version and changelog.
4. Publish extension package.

## Compatibility
- Visual Studio engine target: `^1.77.0`
- Category: `Themes`

## Troubleshooting
- Theme not listed: restart Visual Studio after install.
- Colors look stale: disable/re-enable the theme and reload VS.
- Contributor lint failures: run `pnpm run format` before committing.

## Contributing
See [CONTRIBUTING.md](./CONTRIBUTING.md) for branch, quality, and PR expectations.

## License
MIT © ElShyrux
