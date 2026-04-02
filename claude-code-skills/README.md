# Claude Code Development Style Guide (Skill)

This is a [Claude Code skill](https://docs.anthropic.com/en/docs/claude-code/skills) that teaches Claude how to work with the Claude Code codebase following its established patterns and conventions.

## Installation

To use this skill in your Claude Code sessions:

```bash
# From the repo root
claude skill add ./claude-code-skills
```

Or reference it directly in your `CLAUDE.md`:

```markdown
/skill:claude-code-dev
```

## What's Included

| Guide | Description |
|-------|-------------|
| [Project Overview](01-project-overview.md) | Tech stack, build system, dependencies |
| [Directory Structure](02-directory-structure.md) | File organization and where things go |
| [Import Conventions](03-import-conventions.md) | ESM imports, type imports, feature flags |
| [Naming Conventions](04-naming-conventions.md) | Casing rules for files, variables, types |
| [TypeScript Patterns](05-typescript-patterns.md) | Branded types, unions, Zod schemas |
| [Commenting Style](06-commenting-style.md) | JSDoc, why-not-what philosophy |
| [Error Handling](07-error-handling.md) | Custom errors, graceful degradation |
| [Function Patterns](08-function-patterns.md) | Factories, memoize, async generators |
| [Tool Architecture](09-tool-architecture.md) | How to add new tools |
| [Command Architecture](10-command-architecture.md) | How to add new commands |
| [State Management](11-state-management.md) | Module state, AppState threading |
| [Testing Conventions](12-testing-conventions.md) | Test patterns and helpers |
| [Formatting Rules](13-formatting-rules.md) | Code style (no semicolons, single quotes) |
| [Quick References](14-quick-references.md) | Step-by-step checklists |

## Usage

Once installed, Claude will automatically use this skill when you work on the Claude Code source code. It ensures all contributions match the existing codebase style.
