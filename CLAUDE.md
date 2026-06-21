# CLAUDE.md

This file provides guidance to Claude Code (and other AI assistants) when working
with code in this repository.

## ⚠️ Current state: empty repository

As of the last update to this file, **MAZARA contains no source code yet** — no
commits, no files, no build configuration. This document is therefore a *scaffold*.
The sections below are intentionally marked as placeholders and should be filled in
as the project takes shape.

When you (an AI assistant) add the first real code to this repository, please
**update this file in the same change** so it accurately reflects:

- What the project does and its high-level architecture
- The directory/module layout
- How to install dependencies, build, run, test, and lint
- Naming, formatting, and code-style conventions
- Any non-obvious patterns or gotchas

Do not invent or document structure that does not exist. Keep this file truthful to
the actual state of the codebase.

## Repository

- **Name:** MAZARA (`fim-z/mazara`)
- **Default branch:** not yet created (the repository has no commits)

## Project overview

> _Placeholder — describe the project's purpose, the problem it solves, and its
> primary technologies once code is added._

## Codebase structure

> _Placeholder — document the top-level directory layout and the responsibility of
> each major module/package once code is added._

## Development workflow

### Setup

> _Placeholder — document how to install dependencies and configure a local
> environment (e.g. package manager, runtime versions, env vars)._

### Common commands

> _Placeholder — list the canonical commands once a build system exists, e.g.:_
>
> - Install dependencies: `…`
> - Build: `…`
> - Run locally: `…`
> - Run tests: `…`
> - Lint / format: `…`

Always prefer the project's own scripts (e.g. `Makefile`, `package.json` scripts,
`justfile`) over ad-hoc commands once they are defined.

## Conventions

> _Placeholder — document code-style, naming, commit-message, and review
> conventions once established._

## Git workflow

- Develop changes on a dedicated feature branch; do not commit directly to the
  default branch once one exists.
- Write clear, descriptive commit messages.
- Push with `git push -u origin <branch-name>`.
- Do **not** open a pull request unless explicitly asked to.

## Notes for AI assistants

- This repository currently has no code. Before answering questions about "the
  codebase," verify the current contents first — do not rely on this scaffold's
  placeholders as if they were real.
- Keep this file in sync with reality. An out-of-date CLAUDE.md is worse than none.
