# Decisions

Agreed decisions, newest first. Format: `YYYY-MM-DD — decision — why`.

- 2026-11-13 — Repo set up before the challenge is chosen; shared agent memory lives in plain files
  (`AGENTS.md`, `CLAUDE.md`, `docs/`) — fast, zero-risk, readable by both Claude and Codex.
- 2026-11-13 — Do not install AvenoxBeyin (Obsidian brain) in this repo during the hackathon — it adds
  hooks and vault folders to the submission repo and costs setup time. Revisit afterwards in `~/Beyin`.
- 2026-11-13 — Working model: Claude = advisor/orchestrator/reviewer, Codex = builder,
  Claude subagents = research/review/tests.
