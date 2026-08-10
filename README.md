# asalomeri-starter-kit

Ready-to-use GitHub project templates for a clean repository setup.

## What is included

- `README.md` for the project overview
- `LICENSE` for the repository license
- `CONTRIBUTING.md` for contribution guidance
- `.github/ISSUE_TEMPLATE/` for issue templates
- `.github/pull_request_template.md` for pull requests
- `.github/workflows/ci.yml` for Markdown linting in CI

## How to use this repository

1. Use this repository as a starter or template.
2. Replace the placeholder content with your project details.
3. Keep documentation updated as the project grows.
4. Open focused pull requests for small, reviewable changes.

## Markdown linting

The CI workflow checks all Markdown files on every push and pull request.

Run the same check locally before you open a pull request:

```bash
npx markdownlint-cli2 "**/*.md" "!node_modules/**" "!**/vendor/**"
```

## Recommended next steps

- Review the issue and pull request templates before publishing the project.
- Update `CODEOWNERS` to match your team.
- Replace this README with project-specific details when the repository is
  ready.
