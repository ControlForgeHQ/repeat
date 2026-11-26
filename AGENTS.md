# AGENTS.md

This file provides mandatory repository-wide instructions.

## Protected documents

Never modify the following files:

- `AGENTS.md`
- `docs/AI_WORKFLOW.md`
- `README.md` (repository root)

Modify any document under `docs/specifications/` only when explicitly authorized to modify that specific document. Permission must not be inferred from an implementation request, even when the implementation affects documented behavior.

If implementation reveals that a protected document is incorrect, ambiguous, contradictory, or outdated, report the discrepancy and recommend a specific correction without modifying the document.

## Conflicts and ambiguity

If an assigned requirement conflicts with these instructions, is internally contradictory, or requires a material decision not covered by the approved scope, stop and report the conflict.

If an approved change requires behavior that conflicts with authoritative documentation, report the discrepancy and obtain an approved documentation update before implementation.

Do not silently reinterpret ambiguous requirements, make unapproved architectural decisions, or expand the assigned scope.

## Mandatory development workflow

Before beginning work, read `docs/AI_WORKFLOW.md` in full and follow its instructions.

That document defines the authoritative documentation directory, development procedures, implementation expectations, and review requirements.

If `docs/AI_WORKFLOW.md` is unavailable, contradictory, or cannot be followed without violating the restrictions above, stop and report the problem rather than proceeding.
