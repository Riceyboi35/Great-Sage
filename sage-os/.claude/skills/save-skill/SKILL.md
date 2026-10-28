---
name: save-skill
description: Turn a process that just worked into a reusable skill in .claude/skills. Use when Dan says "save this as a skill", or after a task he'll want done the same way again.
---

# Save a skill

1. Summarise the process just done as numbered steps, including every
   correction Dan made along the way.
2. Pick a short kebab-case name (e.g. `quote-follow-up`).
3. Create `.claude/skills/<name>/SKILL.md` with:
   - frontmatter: `name` and a one-line `description` saying when to use it
   - the steps, written so a new assistant could follow them without asking
   - an example of a good final output if there is one
4. Show Dan the skill and ask him to approve it before relying on it.
