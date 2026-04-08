# Scope — Architectural Plans Index

## What belongs here

Repositories whose primary content is **planning, specification, or architectural documentation** for a project — the *blueprint*, not the build.

Include a repo if it is:

- A written spec, design doc, or architecture description for something to be built (or being built elsewhere)
- Planning notes, ideation, or brainstorming captured as a standalone repo
- A "spec-driven development" starting point (e.g. one long prompt that specs an idea)
- A template or pattern for producing plans/specs
- An architectural model or data model describing how a system should fit together
- A "parked idea" repo where the artifact is the written concept, not code

The defining test: **if you deleted the docs, there would be nothing left.** The repo exists to hold the plan.

## What does NOT belong here

- **Actively-built projects with real code** → use `WIP-Index` (even if a spec exists inside the repo)
- **General reference docs, notes, or tutorials** published for reading → use `Docs-And-Notes-Index`
- **Finished / shipped projects** → use the appropriate topical index

## Overlap rules

- A repo can appear in both `Architectural-Plans-Index` and `WIP-Index` if it has both a substantial planning artifact *and* active implementation work
- A repo can appear in both `Architectural-Plans-Index` and a topical index (e.g. `MCP-Projects-Index`) if the plan is topic-specific
- Prefer this index over `WIP-Index` when the repo is **plan-heavy / code-light**
