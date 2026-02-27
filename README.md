## WIKI.md

Universal Agent Skill for generating and maintaining `WIKI.md` as a verified repository architecture map.

Works across tools that support AgentSkills-style folders (`SKILL.md`), including OpenClaw and other compatible coding-agent environments.

## What it does

- Builds a concise repo brief
- Maps repository/package structure with real links
- Captures key file/symbol references (verified only)
- Generates Mermaid diagrams for dependency/runtime/tooling flow
- Keeps `WIKI.md` in sync incrementally after changes

## Repository structure

```text
repo-wiki-architect-public/
└── repo-wiki-architect/
    └── SKILL.md
```

## Install

### OpenClaw

```bash
# from this repo root
cp -R repo-wiki-architect ~/.openclaw/workspace/skills/
# restart/new session for skill discovery if needed
```

Or publish/install via ClawHub.

### Cursor / Claude Code / Other tools

If your tool supports AgentSkills-compatible folders, copy `repo-wiki-architect/` into that tool's skills/prompts directory.

Generic steps:
1. Locate tool's local skills directory.
2. Copy the `repo-wiki-architect` folder as-is.
3. Reload/restart the tool session.

## Usage examples

Trigger phrases:
- "Create WIKI.md for this repository"
- "Update WIKI.md after recent refactor"
- "Map architecture and dependency graph in WIKI.md"

## Compatibility notes

This skill is vendor-neutral in content and avoids tool-specific operational commands in `SKILL.md`.

## License

MIT (see [LICENSE](./LICENSE)).
