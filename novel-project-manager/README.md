# Novel Project Manager

An author-controlled Agent Skill for managing long-form fiction projects and their Markdown setting files.

## What it does

- Reads project-specific instructions and source-of-truth rules before interpreting canon.
- Separates confirmed facts, unresolved questions, inferences, and deprecated material.
- Checks character identity, knowledge, motivation, relationships, and timeline continuity.
- Analyzes worldbuilding rules without inventing missing mechanics.
- Tracks terminology changes and checks references in context.
- Classifies cross-file findings instead of treating every discrepancy as a contradiction.
- Makes minimal, authorized edits and verifies affected files afterward.

## Installation

Copy the `novel-project-manager/` directory into the location where your agent discovers skills. For agents that support repository-local skills, keep the directory in the repository and configure the agent to load its `SKILL.md`.

The exact discovery path and invocation syntax depend on the agent platform. This skill does not assume a particular vendor or runtime.

## Use

Ask the agent to do tasks such as:

- Audit a setting mechanism for logical gaps.
- Compare a term's current and former definitions.
- Check a character's knowledge against the timeline.
- Find contradictions across setting files.
- Plan a revision and list all dependent files.
- Implement an explicitly authorized, bounded file change.

## Design principles

- The novel project defines its own canon and authority hierarchy.
- The author retains final control over unresolved decisions.
- Inference is never silently promoted to fact.
- Missing information remains missing until established.
- The skill does not require a fixed project directory layout or data schema.

## License

MIT License. See [LICENSE](LICENSE).
