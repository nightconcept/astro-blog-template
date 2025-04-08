# Astro-Blog-Template

A blog starter template that I regularly use containing:

- Astro
- TailwindCSS 4
- Devenv with NodeJS 22 and pnpm
- Biome for formatting and linting
- GitHub CI Action
- Dependabot
- Lint-staged with pre-commit hooks to lint and format
- Playwright

Note: Vitest is not installed because I haven't figured out how to run unit tests with Astro _yet_.

## Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `pnpm install`            | Installs dependencies                            |
| `pnpm dev`                | Starts local dev server at `localhost:4321`      |
| `pnpm build`              | Build your production site to `./dist/`          |
| `pnpm lint`               | Run linter with no fixing                        |
| `pnpm format`             | Run formatter with fixing                        |
| `pnpm test`               | Run all unit and coverage tests                  |
