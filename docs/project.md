# Project Architecture Guidelines

## Repository Architecture

- `docs/`
  - `project.md` --> defines project architecture
  - `references/` --> stores external source material
  - `research/` --> stores information produced from investigation or analysis
  - `plans/` --> defines intended future work
- `README.md`
- `LICENSE`
- `.gitignore`

## Progression Architecture

**Stage**

A broad period of project development that groups related phases under a shared purpose.

**Phase**

A focused unit within a stage, defined by an objective, ordered steps, and completion criteria.

- Name
- Objective
- Steps
- Completion Criteria

## Shared Conventions

- Authored documentation uses Markdown and belongs under `docs/` according to purpose; external materials under `references/` or `research/` may retain original formats.
- File and directory names use `lower-kebab-case`; source-code paths follow the established conventions of their language, framework, or toolchain.
- Tool-generated and externally sourced filenames should not be renamed when doing so could break compatibility or provenance.
- Dates use the ISO `YYYY-MM-DD` format.
- Internal links use relative Markdown paths so they work in both Obsidian and Git.
- Each subject has one canonical document; duplicate formats are created only when submission or compatibility requires them.
