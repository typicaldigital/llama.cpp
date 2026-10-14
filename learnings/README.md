# learnings/ - the structured learnings store

This directory is the authoritative learnings store of this repository.
Write records with `env memory add --kind learning`, or write files here directly.

- `candidates/` - hypotheses and observations under review.
- `validated/` - lessons with recorded evidence.
- `superseded/` - retired lessons, kept for traceability.

Every record keeps its own date and its provenance in the frontmatter.
Do not create a `LEARNINGS.md` file. The 2026-10-13 migration moved the former
`LEARNINGS.md` entries into this store. The file was deleted on 2026-10-14,
and git history holds the original.
