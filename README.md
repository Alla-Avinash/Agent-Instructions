# Portable Cursor rules & skills

A self-contained copy of the generic (non-project-specific) rules and skills from this repo, so you can reuse them in any other project.

- **Rules** (`.cursor/rules/*.mdc`) are loaded automatically. Files marked `alwaysApply: true` are always in context; the rest load on demand when the topic comes up.
- **Skills** (`.cursor/skills/<name>/SKILL.md`) are read when the user's request matches the skill's description.



## What's included

**Rules (generic, apply to any codebase):**
- `domain-explanation.mdc` — teach the domain before explaining the code
- `explain-code.mdc` — explain code in plain terms with an end-to-end flow
- `project-phases.mdc` — how to onboard onto a new or existing codebase
- `rules.mdc` — development & codebase-change rules (structure, naming, small diffs)
- `specs.mdc` — the "specs folder" documentation convention
- `response-workflow.mdc` — how to phrase chat responses and the dev workflow

**Skills:**
- `explain-code` — explain code/architecture in plain, simple terms
- `explain-concept` — explain a whole technology "like a beginner" (structured cheat-sheet)

