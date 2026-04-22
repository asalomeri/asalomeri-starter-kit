# asalomeri-starter-kit

Ready-to-use GitHub project templates: README, LICENSE, issue/PR templates,
and CI workflows.

## What's included

- `README.md` – project description template
- `LICENSE` – MIT license
- `CONTRIBUTING.md` – contribution guidelines
- `.github/workflows/ci.yml` – CI workflow with Markdown linting

## Usage

1. Fork or use this repository as a template.
2. Replace placeholder content with your project details.
3. Push changes – the CI workflow will lint all Markdown files automatically.

## Linting

This repository uses [markdownlint-cli2] to enforce Markdown style.

[markdownlint-cli2]: https://github.com/DavidAnson/markdownlint-cli2

Run locally:

```bash
npx markdownlint-cli2 "**/*.md" "!node_modules/**"
```
