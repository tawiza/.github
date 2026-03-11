# Contributing to Tawiza

Thank you for your interest in contributing to Tawiza! This guide applies to all repositories in the organization.

## How to Contribute

### 1. Fork & Branch

1. Fork the repository
2. Create a feature branch from `main`: `git checkout -b feat/your-feature`
3. Make your changes
4. Push to your fork

### 2. Commit Conventions

We follow [Conventional Commits](https://www.conventionalcommits.org/):

- `feat:` — New feature
- `fix:` — Bug fix
- `docs:` — Documentation only
- `refactor:` — Code refactoring (no feature change)
- `test:` — Adding or updating tests
- `chore:` — Maintenance tasks

Example: `feat: add SIRENE API integration`

### 3. Pull Request Process

1. **All PRs must target `main`** and will be reviewed by a maintainer before merge
2. Fill in the PR template completely
3. Ensure your code passes existing tests
4. Keep PRs focused — one feature or fix per PR
5. Update documentation if your change affects public APIs or behavior

> **Note:** Only maintainers can merge pull requests. External contributions require approval before being integrated.

### 4. Code Style

- **Python (Backend):** Follow PEP 8, use type hints, docstrings for public functions
- **TypeScript (Frontend):** ESLint + Prettier config from the repo
- **Naming:** English for code, French is acceptable for domain-specific terms (e.g., `commune`, `departement`)

### 5. Issues

- Use issue templates when available
- Search existing issues before creating a new one
- Be specific: include steps to reproduce for bugs, clear description for features

## What We're Looking For

- Bug fixes with tests
- Documentation improvements
- New data source integrations (French open data APIs)
- Performance improvements
- Accessibility improvements
- Translations

## Code of Conduct

By participating, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).

## Questions?

Open a [discussion](https://github.com/orgs/tawiza/discussions) or an issue — we're happy to help.
