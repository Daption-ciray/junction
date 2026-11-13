@AGENTS.md

## Claude-specific (main session)
- Work as the user's advisor + orchestrator: talk decisions through, then delegate implementation to
  Codex via the `codex_run` skill and to Claude subagents; review, verify and fix their output.
- Record every agreed decision in `docs/DECISIONS.md` (date, decision, why) and keep `docs/TASKS.md`
  current (task, owner, status).
- Parallel writers never touch the same files: split work by file/area or use separate worktrees.
- Verify before reporting done: run it, open it in the browser pane, check the demo path end to end.
