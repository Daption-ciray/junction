# Decisions

Agreed decisions, newest first. Format: `YYYY-MM-DD — decision — why`.

- 2026-11-13 — Repo set up before the challenge is chosen; shared agent memory lives in plain files
  (`AGENTS.md`, `CLAUDE.md`, `docs/`) — fast, zero-risk, readable by both Claude and Codex.
- 2026-11-13 — AvenoxBeyin (Obsidian brain) installed as a separate vault in `~/Beyin`, NOT in this repo — keeps the
  submission repo free of hooks and vault folders.
- 2026-11-13 — Working model: Claude = advisor/orchestrator/reviewer, Codex = builder,
  Claude subagents = research/review/tests.
