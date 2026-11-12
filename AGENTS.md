# Repository Guidelines

## Project Structure & Module Organization

This repository is currently an empty project directory. No application code, tests, assets, or package manifests exist yet. When establishing the project, group application code under `src/`, static assets under `public/` or `assets/`, and automated tests beside their modules or under `tests/`. Choose one layout and document it in `README.md` before expanding the codebase.

## Build, Test, and Development Commands

No development, build, lint, or test commands are configured. When adding tooling, expose consistent commands through the chosen package manager or build system and document their prerequisites in `README.md`. For a JavaScript project, suggested script names are `dev`, `build`, `lint`, and `test`; these are conventions to establish, not commands currently available. Commit the corresponding dependency lockfile.

## Coding Style & Naming Conventions

Follow the conventions of the language and framework selected for the project. Configure a formatter and linter early, and use their configuration as the source of truth for indentation and formatting. Use descriptive names, keep modules focused, and follow a consistent filename convention. Avoid introducing competing formatting tools or unrelated style changes in functional patches.

## Testing Guidelines

No testing framework or coverage threshold is configured. Add tests alongside new behavior once a framework is selected. Use descriptive test names that identify the behavior and expected outcome; follow the framework’s discovery pattern, such as `*.test.ts` if applicable. Document how to run the suite and any required environment setup.

## Commit & Pull Request Guidelines

No Git history is available to establish existing commit conventions. Use concise, imperative commit subjects, such as `Add application shell`. Keep contributions focused. Pull requests should explain the change, include verification steps and results, and link relevant issues. Include screenshots for visible interface changes and identify any configuration or setup changes.

## Security & Configuration

Keep credentials and local environment files out of version control. Provide placeholder values in an example configuration file when configuration becomes necessary.
