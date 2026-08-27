# Agent Guidance

## Repository Shape

- This is currently a minimal repository, not an established application or package.
- `fruit` is a plain-text data file containing fruit names.
- `README.md` is the project overview; update it when the repository purpose or workflow becomes defined.

## Development Workflow

- No build, test, lint, or package-management commands are currently defined.
- Before introducing a workflow, inspect the repository and document new commands in `README.md`.
- Keep changes small and preserve the existing plain-text format unless the task explicitly establishes a new project structure.

## Configuration and Secrets

- `.env` is local configuration and is ignored by Git. Never commit real credentials or copy its values into tracked files.
- Treat placeholder API keys and other secrets as sensitive even when they are not production values.

## Documentation

- Link to or extend `README.md` rather than duplicating project documentation in this file.
- Add focused instructions here only when they are stable, repository-specific guidance that agents cannot discover from the files or standard tooling.
