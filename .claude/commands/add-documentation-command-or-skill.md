---
name: add-documentation-command-or-skill
description: Workflow command scaffold for add-documentation-command-or-skill in everything-claude-code.
allowed_tools: ["Bash", "Read", "Write", "Grep", "Glob"]
---

# /add-documentation-command-or-skill

Use this workflow when working on **add-documentation-command-or-skill** in `everything-claude-code`.

## Goal

Adds new documentation for a command, skill, or agent to the ECC bundle.

## Common Files

- `.claude/commands/add-documentation-skill-or-agent.md`
- `.claude/commands/add-documentation-command-or-workflow.md`
- `.claude/skills/everything-claude-code/SKILL.md`
- `.agents/skills/everything-claude-code/SKILL.md`

## Suggested Sequence

1. Understand the current state and failure mode before editing.
2. Make the smallest coherent change that satisfies the workflow goal.
3. Run the most relevant verification for touched files.
4. Summarize what changed and what still needs review.

## Typical Commit Signals

- Create or update a markdown file in .claude/commands/ for commands.
- Create or update a markdown file in .claude/skills/ or .agents/skills/ for skills.
- Commit the new or updated documentation file.

## Notes

- Treat this as a scaffold, not a hard-coded script.
- Update the command if the workflow evolves materially.