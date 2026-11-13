# AGENTS.md — Junction hackathon project

Shared instructions for every coding agent working in this repo (Codex, Claude and subagents).
Read this file, `docs/CHALLENGE.md`, `docs/DECISIONS.md` and `docs/TASKS.md` before starting work.

## Context
- This repo is our entry for the **Junction** hackathon. The challenge is not chosen yet; once it is,
  its brief, judging criteria and deadline live in `docs/CHALLENGE.md`.
- Time is the scarcest resource. Optimize for a **working, demoable end-to-end flow** first, polish later.
- The team communicates in Turkish; code, comments, commit messages and docs are in English.

## Roles
- **Claude (main session)** — advisor and orchestrator: discusses decisions with the user, splits work,
  writes task briefs, reviews and verifies results, fixes mistakes.
- **Codex** — primary builder: writes code, UI, visuals and assets from Claude's briefs.
- **Claude subagents** — research (APIs, datasets, docs), independent review, tests and verification.

## Rules for agents
1. Stay inside the scope of your brief. Don't refactor or add files outside it.
2. Before finishing: run the build / tests / lint that exist and report the results honestly.
3. End with a short summary: files changed, how to run it, anything left undone or uncertain.
4. Never commit secrets. Use `.env.local` (gitignored) and document new variables in `.env.example`.
5. Don't install heavy dependencies without a reason; prefer what the stack already has.
6. If a decision is needed that isn't in `docs/DECISIONS.md`, stop and ask instead of guessing.
7. Don't edit `docs/DECISIONS.md` — Claude records decisions there after agreeing them with the user.
   You may update your own task's line in `docs/TASKS.md`.

## Stack
_Not decided yet — see `docs/DECISIONS.md`._

## Commands
_Filled in once the project is scaffolded (install, dev, build, test, lint, deploy)._
