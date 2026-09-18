# Project conventions

## Stack

- Node.js LTS for scripts and tooling
- npm for dependency management
- Markdown for project documentation
- GitHub for source control and collaboration

## Conventions

- Use Conventional Commits: `type(scope): imperative description`.
- Prefer small, focused commits that explain one change.
- Keep documentation concise, scannable, and accurate.
- Use ASCII by default unless a file already requires another character set.
- Do not commit secrets, local environment files, dependency folders, or generated output.

## Validation

- Check Markdown changes by reading the rendered structure for clarity.
- Run `git diff --check` before committing.
- Confirm `git status` is clean after each completed change.
