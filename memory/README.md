# memory/ - the structured memory store

This directory is the authoritative memory store of this repository.
Write records with `env memory add --kind memory`, or write files here directly.

- `short-term/` - active context and checkpoints.
- `long-term/episodic/` - dated experiences and decisions.
- `long-term/semantic/` - durable understanding and constraints.

Every record keeps its own date and its provenance in the frontmatter.
Do not create a `MEMORY.md` file. The 2026-10-13 migration moved the former
`MEMORY.md` entries into this store. The file was deleted on 2026-10-14,
and git history holds the original.
