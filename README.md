## WIKI.md

Agent Skill for generating and maintaining `WIKI.md` as a verified repository architecture map.

Works with Claude Code, Cursor, Codex, OpenCode, Amp, Goose, VS Code, Windsurf, and any tool that supports the [AgentSkills](https://agentskills.io) format.

## What it does

- Builds a concise repo brief
- Maps repository/package structure with real, verified links
- Captures key file/symbol references (verified only — never inferred)
- Generates Mermaid diagrams for dependency/runtime/tooling flow
- Keeps `WIKI.md` in sync incrementally after changes

## Install (one command)

```bash
npx skills-installer install @eveiljuice/wiki.md-skill/repo-wiki-architect
```

### Install for a specific tool

```bash
# Claude Code (default)
npx skills-installer install @eveiljuice/wiki.md-skill/repo-wiki-architect --client claude-code

# Cursor
npx skills-installer install @eveiljuice/wiki.md-skill/repo-wiki-architect --client cursor

# OpenCode
npx skills-installer install @eveiljuice/wiki.md-skill/repo-wiki-architect --client opencode

# Codex
npx skills-installer install @eveiljuice/wiki.md-skill/repo-wiki-architect --client codex

# Amp
npx skills-installer install @eveiljuice/wiki.md-skill/repo-wiki-architect --client amp

# Goose
npx skills-installer install @eveiljuice/wiki.md-skill/repo-wiki-architect --client goose

# VS Code / GitHub Copilot
npx skills-installer install @eveiljuice/wiki.md-skill/repo-wiki-architect --client vscode

# Windsurf
npx skills-installer install @eveiljuice/wiki.md-skill/repo-wiki-architect --client windsurf
```

### Project-local install (instead of global)

```bash
npx skills-installer install @eveiljuice/wiki.md-skill/repo-wiki-architect --local
```

## Usage

Trigger phrases:

- "Create WIKI.md for this repository"
- "Update WIKI.md after recent refactor"
- "Map architecture and dependency graph in WIKI.md"
- "Refresh the wiki"

## Repository structure

```
wiki.md-skill/
└── repo-wiki-architect/
    └── SKILL.md
```

## Registry

This skill is listed on [claude-plugins.dev](https://claude-plugins.dev/skills) — the open community registry for AgentSkills.

## License

MIT
