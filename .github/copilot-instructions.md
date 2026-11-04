# GitHub Copilot Instructions - tomacheese Organization

This file is the org-wide reference for Copilot and agent conventions in the tomacheese organization. It contains only the minimal rules that hold regardless of project specifics. For project-specific conventions, see each repository's `AGENTS.md`, README, and docs.

## Language Policy

- The default language is English for commit messages (Conventional Commits with an English description), PR and Issue titles and bodies, review comments, code comments and docstrings, and documentation.
- Private repositories use Japanese.
- Public repositories whose audience is Japanese-only may use Japanese.
- Each repository's own root `AGENTS.md` is the source of truth and takes precedence over this org-wide default. When it is present, follow it. When it is absent or ambiguous, default to English.
- `package.json` is always written in English.
- Exceptions: end-user-facing UI and notification text, quotations, technical identifiers, generated files, and external source text.

## Commit Conventions

PR titles and commit messages must follow [Conventional Commits](https://www.conventionalcommits.org/). The description language follows the Language Policy above.

### Format examples

- `feat: add new feature`
- `fix: resolve authentication issue`
- `docs: update README`
- `style: fix eslint issues`
- `refactor: improve code structure`
- `test: add unit tests`
- `chore: update dependencies`

## Common Coding Standards

### Project structure

- **License**: refer to each repository's LICENSE file.
- **Node.js package manager**: prefer pnpm.
  - Install it if the command is not available.
  - Use the package manager that matches the lockfile. If the wrong package manager was used and a new lockfile was created, delete it.
- **Primary language**: TypeScript is preferred.

### Code quality

- **Linter**: use ESLint (`@book000/eslint-config` is recommended).
- **Formatter**: use Prettier.
- **Type checking**: enable strict TypeScript type checking.

### Development workflow

- **CI/CD**: use GitHub Actions.
- **Pull requests**: review is required to maintain code quality.
- **Automation**: automate with scripts and workflows wherever possible.
