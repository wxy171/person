---
name: novel-project-manager
description: Manage an existing novel project’s canon, characters, worldbuilding, terminology, continuity, and Markdown setting files. Use when analyzing, organizing, checking, planning, or revising a fiction project with established documents. Prioritize the project’s own authority rules and preserve author control; do not invent missing canon.
---

# Novel Project Manager

Use this skill to work with an existing fiction project as a document system. The project files—not generic writing conventions or this skill—define the story's canon.

## Core contract

1. **Inspect before interpreting.** Locate project instructions, indexes, setting documents, timelines, character files, terminology lists, and relevant manuscript sections before making claims.
2. **Follow local authority rules.** Discover how this project resolves conflicts between documents. Never impose a universal hierarchy.
3. **Keep evidence states separate.** Use the project's own status vocabulary if it exists. Otherwise distinguish:
   - **Confirmed**: explicitly established by the author or established by a project document under its stated authority rules.
   - **Unresolved**: explicitly undecided, incomplete, or conflicting.
   - **Inferred**: a reasoned interpretation, not confirmed canon.
   - **Deprecated**: explicitly withdrawn or superseded.
4. **Preserve uncertainty.** Do not turn silence into a negative fact, inference into canon, or a proposal into an established rule.
5. **Preserve author control.** Analysis and recommendations do not authorize file edits. Edit only when the user asks for edits or clearly authorizes implementation.
6. **Make minimal, traceable changes.** Change only what the task requires; preserve unrelated wording, structure, and confirmed content.
7. **Verify after editing.** Re-read changed files and inspect affected references and dependent documents.

## Task routing

Classify the request before acting:

| Task | Action |
|---|---|
| Explain / retrieve | Find source passages and answer with evidence; do not edit |
| Audit / consistency check | Inspect relevant files and report findings; do not edit |
| Design / brainstorm | Label proposals as proposals; do not silently add them to canon |
| Plan a revision | Identify affected files and propose a change plan; do not edit yet |
| Revise / update files | Confirm scope from the request, inspect evidence, make minimal authorized edits, then verify |
| Continue prose | Read canon and relevant surrounding prose; do not resolve canon gaps by invention |

## Standard workflow

1. **Identify project root and instructions.** Find repository guidance such as `AGENTS.md`, project README files, and setting indexes. Follow their scope.
2. **Map relevant sources.** Search for the requested subject and its aliases. Read the full governing section when snippets are insufficient.
3. **Establish authority and status.** Read [authority-and-canon.md](references/authority-and-canon.md). Record source paths and any unresolved conflict in authority.
4. **Load the relevant domain guide.** Use the character, worldbuilding, or terminology guide as appropriate.
5. **Check dependencies.** Use [cross-file-consistency.md](references/cross-file-consistency.md) to identify affected references and possible contradictions.
6. **Report before changing.** For non-trivial revisions, state the evidence, issues, proposed changes, and unresolved decisions. If the user has already clearly authorized the requested implementation, do not ask for redundant approval.
7. **Edit within scope.** Follow [revision-workflow.md](references/revision-workflow.md). Never rewrite unrelated sections for stylistic neatness.
8. **Verify.** Check changed text, links, terminology, timeline, character knowledge, and dependent files. Report what was changed and what remains unresolved.

## Reference guides

- [authority-and-canon.md](references/authority-and-canon.md) — source authority, evidence, canon status
- [character-management.md](references/character-management.md) — character facts, knowledge, motivation, relationships
- [worldbuilding-management.md](references/worldbuilding-management.md) — rules, mechanisms, conditions, dependencies
- [terminology-management.md](references/terminology-management.md) — definitions, distinctions, renames, deprecated terms
- [cross-file-consistency.md](references/cross-file-consistency.md) — conflict classification and impact analysis
- [revision-workflow.md](references/revision-workflow.md) — authorized, minimal, verifiable edits
- [forbidden-assumptions.md](references/forbidden-assumptions.md) — assumptions and actions that must not be made

## Required response discipline

When useful, separate the result into:

- **Documented facts** — directly supported by identified project sources.
- **Interpretations** — conclusions derived from those facts, with reasoning.
- **Problems** — contradictions, omissions, or ambiguous wording, with source locations.
- **Proposals** — suggested changes that are not yet canon.
- **Unresolved items** — questions the documents do not settle.

Do not claim a file was changed, a check was run, or a conflict was resolved unless that action actually occurred.
