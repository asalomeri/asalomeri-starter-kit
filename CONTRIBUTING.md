# Contributing

Thanks for your interest.

## How to contribute

- Open an issue describing the change.
- Create a small PR (focused change).
- Use the provided PR template.

## Running Markdown lint locally

Before opening a PR, verify that all Markdown files pass the linter:

```bash
npx markdownlint-cli2 "**/*.md" "!node_modules/**"
```

The same check runs automatically in CI (`Markdown (lint)` job) on every push
and pull request.

## Notes

- Do not commit secrets (tokens/keys).
- Keep changes simple and documented.
