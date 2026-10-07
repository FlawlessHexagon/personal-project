# Project Architecture Guidelines

## Repository Architecture

- `docs/`
  - `project.md` --> defines project architecture
  - `references/` --> stores external source material
  - `research/` --> stores information produced from investigation or analysis
  - `feedback/` --> stores feedback from meetings
  - `process/` --> records drafts, reasoning, feedback analysis, and decisions
    - `project-definition.md` --> records how the project direction was developed
    - `success-criteria.md` --> records format research, structure decisions, and criteria development
  - `definition/` --> consolidates current project expectations without development history
    - `project-definition.md` --> defines the selected title, goals, purpose, and audience
    - `success-criteria.md` --> defines the selected structure and finalized product requirements
  - `plans/` --> defines intended future work
    - `phases/` --> stores phase plans
- `README.md`
- `LICENSE`
- `.gitignore`

## Progression Architecture

### Stage

A broad period of project development that groups related phases under a shared purpose.

### Phase

A focused unit within a stage, defined by an objective, ordered steps, and completion criteria.

- Name
- Objective
- Steps

## Shared Conventions

- Authored documentation uses Markdown and belongs under `docs/` according to purpose; external materials under `references/` or `research/` may retain original formats.
- File and directory names use `lower-kebab-case`; source-code paths follow the established conventions of their language, framework, or toolchain.
- Tool-generated and externally sourced filenames should not be renamed when doing so could break compatibility or provenance.
- AI-produced research artifacts, including deep research reports, analysis, and research indexes, use the filename prefix `ai-research-` (for example, `ai-research-acceptance-criteria.md`).
- Dates use the ISO `YYYY-MM-DD` format.
- Internal links use relative Markdown paths so they work in both Obsidian and Git.
- Each subject has one canonical document; duplicate formats are created only when submission or compatibility requires them.
- Process documents preserve how decisions developed; definition documents are the canonical source for current decisions. Link between them rather than maintaining duplicate final definitions.
