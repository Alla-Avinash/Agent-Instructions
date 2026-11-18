---
name: explain-concept
description: Explains a technology, framework, or system "like a beginner" — a structured cheat-sheet covering its components, architecture, languages/libraries, project structure, workflow, and conventions, each with a concrete example. Use when the user says "explain X like a beginner", "what is X and how do I write it", or wants to understand and build with a new tool/framework.
disable-model-invocation: false
---

# Explain a concept (beginner cheat-sheet)

When the user wants to understand a technology, framework, or system from scratch, produce a clear outline that teaches it in layers. Plain words, real examples, no jargon unless defined.

## The structure to follow

For the concept being explained (MCP, React, SQLite, Docker, …), fill this outline in order:

1. **What it is** — one plain sentence: what problem it solves and why it exists.
2. **Components** — the named pieces it's made of (e.g. a "tool card", a "component", a "table").
3. **Architecture & how they interact** — the user flow: what actions the user takes and how the components interact through the entire workflow.
4. **Languages / libraries / frameworks / tools** — what it's typically built with and why each is used.
5. **Project structure** — the typical files & folders in a standard project using it.
6. **Conventions & best practices** — how good developers write it; the patterns they reach for.
7. **Each component explained** — one short explanation plus a small example per component.

## Rules

- **Plain English first.** Everyday words; define every term the first time it appears.
- **Analogies over acronyms** ("like a filing cabinet" beats a wall of terms).
- **Stay layered.** Present the outline first, then fill in only the sections the reader doesn't know — don't dump everything at once.
- **Give one concrete example per idea**, not a long definition.
- **Keep each explanation short enough to remember.**
- **Be honest.** If a part is redundant, legacy, or confusing, say so.
- **Generic and reusable** — explain it the way it works anywhere, so the reader can reuse the knowledge in other projects.

## Example shape (generic)

Use this outline for any concept/technology. Replace `<concept>` with the name being explained.

```
<concept>
  components
    list of the named pieces it's made of
  architecture & how the components interact
    the user flow: what actions the user takes, and how the components interact through the entire workflow
  widely used programming languages / libraries / frameworks / tools for this concept
  project structure of files and folders
  conventions to write the code and best practices
  each component explained
    one short explanation + a small example per component listed above
```

When the user already knows part of it, skip what they know and teach only the gaps.
