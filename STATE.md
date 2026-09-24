# llama.cpp (gitfork) — STATE.md

> **Living state document.** The single source of truth for this repo's current
> state: where we are, every outstanding work item (with enough context for a new
> session to pick up and continue without delay), blockers, versions, releases,
> and decisions. Updated at the end of every session pass (stop-hook:
> state-md-reminder). Mandatory in every repo alongside AGENTS.md, LEARNINGS.md
> and MEMORY.md (enforced by the mandatory-docs-guard).
>
> **Merge discipline (concurrent sessions):** never blind-overwrite. If this file
> has uncommitted edits or origin/main is newer, pull/merge first and accept the
> merged state as authoritative — never drop another session's information.
> Record new items under Outstanding; strike or remove completed ones. Update
> the counter at the bottom every time.

## Current state

- Controlled fork of the official llama.cpp (`typicaldigital/llama.cpp`,
  upstream `ggml-org/llama.cpp`), carrying the upstream lineage plus the world's
  contract set. Local chat-template work lives here.
- Ownership: PivotalContinuum (declared per Standard v0.2 §18).
- **World-convention note (2026-09-24):** the upstream `CLAUDE.md` was removed in
  this fork — the world convention is AGENTS.md-only (Claude reads AGENTS.md
  natively). The pristine `+repos/gitrepo/llama.cpp` clone keeps its upstream
  CLAUDE.md untouched (Standard §9). Expect a trivial upstream merge for that
  file on the next upstream sync.

## Outstanding

- None recorded in this ledger yet. Known follow-up: on the next upstream sync,
  keep the CLAUDE.md deletion (world convention) and re-apply the world AGENTS.md
  if upstream touches it.

## Blockers

- None recorded.

## Versions & releases

- Tracks upstream llama.cpp (no world version of its own).

## Decisions

- The fork follows the world's document conventions (AGENTS.md + STATE.md);
  upstream content is preserved except where the world convention deliberately
  diverges.

## Notes

- 2026-09-24: STATE.md created (mandatory-docs sweep).

<outstanding-items>1</outstanding-items>
