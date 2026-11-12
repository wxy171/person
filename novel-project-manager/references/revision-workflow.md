# Revision Workflow

## Purpose

Make authorized changes to project documents safely, with minimal scope and explicit verification.

## 1. Classify the requested operation

Determine whether the user asked for:

- explanation or retrieval;
- review or diagnosis;
- proposal or design;
- a change plan;
- a specific file edit;
- a broad implementation across multiple files;
- prose drafting or continuation.

Do not treat "check", "analyze", "what should change", or "find inconsistencies" as permission to edit files.

## 2. Determine authorization and scope

Editing is authorized when the user explicitly requests a file change or clearly instructs implementation. For ambiguous requests, provide a plan and ask one focused question before writing.

Record:

- requested outcome;
- files or sections in scope;
- constraints and content to preserve;
- whether the user authorized direct implementation;
- decisions still requiring author input.

Do not ask for approval again when the user has already clearly authorized the same bounded implementation.

## 3. Read sufficient context

Before editing:

1. read project instructions and authority rules;
2. read the complete target section, not only an isolated sentence, when context affects meaning;
3. read relevant definitions and dependencies;
4. search for references that may become stale;
5. inspect adjacent prose when editing manuscript text.

If a source is unavailable, state the limitation and do not fill its contents from memory or guesswork.

## 4. Prepare a minimal change plan

For non-trivial changes, list:

- issue being corrected;
- evidence and source locations;
- exact intended change;
- files that must change;
- files that need review;
- unresolved decisions and risks;
- content explicitly out of scope.

Do not broaden the task into a general rewrite.

## 5. Execute the edit

- Preserve existing file structure, headings, frontmatter, naming conventions, and links unless the task requires changing them.
- Preserve confirmed content outside the authorized scope.
- Keep unresolved items unresolved.
- Label proposals and inferences.
- Update dependent files only when the change actually affects them.
- Avoid mass replacement unless each occurrence has been context-checked.
- Do not invent metadata, dates, version numbers, authors, or approval states.
- For repository changes, inspect the target path before creating or replacing a file. Never overwrite an existing file without reading it and confirming the intended replacement.

## 6. Verify after editing

Re-read every changed file. Then check:

- the requested change is present and accurately expressed;
- no contradictory wording remains in the changed section;
- terminology is consistent;
- links and references still resolve;
- affected character knowledge, relationships, and timeline remain coherent;
- dependent files were updated or explicitly marked for review;
- unrelated content was not changed.

If automated checks are available, run only checks that are relevant and actually supported by the project. Report their real results; do not imply that a check ran when it did not.

## 7. Report completion

A completion report should state:

- files created or changed;
- summary of each substantive change;
- checks actually performed and their results;
- unresolved issues or author decisions;
- anything not changed and why.

Do not say "fully consistent" when only a limited set of files was inspected. Describe the audit scope.

## 8. Stop conditions

Pause and ask the author when:

- two authoritative sources conflict and no project rule resolves them;
- the requested change requires inventing a missing fact;
- a term's intended meaning is unclear;
- a character relationship or identity is not established;
- a revision would change a major rule beyond the user's stated scope;
- the target file already exists and replacement intent is unclear;
- available tools cannot safely preserve or verify the target content.
