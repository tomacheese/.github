# AGENTS.md

## Purpose

This is the tomacheese organization's community health repository. This repository is the org-wide reference for Copilot and agent conventions; each repository overrides it with its own `AGENTS.md`.

## Language

- Default: English for commit messages (Conventional Commits, English description), PR/Issue titles and bodies, review comments, code comments/docstrings, and documentation.
- Private repositories use Japanese. Public repositories whose audience is Japanese-only may use Japanese.
- Each repository's own root `AGENTS.md` is the source of truth and wins over this org-wide default; if it is absent or ambiguous, default to English.
- `package.json` is always English.
- Exceptions: end-user-facing UI/notification text, quotations, technical identifiers, generated files, external source text.
- This repository itself is written in English.

## Files

- `README.md`: short description of the repository.
- `.github/copilot-instructions.md`: org-wide reference for Copilot instructions (language policy, commit conventions, common coding standards).

Keep `.github/copilot-instructions.md` to minimal, project-agnostic rules.
