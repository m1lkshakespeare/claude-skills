# My Claude Code skills

Personal skills for Claude Code. Symlinked to `~/.claude/skills` on every host.

## Layout
Each skill is a folder containing a `SKILL.md` with YAML frontmatter:

```
<skill-name>/
  SKILL.md
  scripts/      # optional
  references/   # optional
```

## Sync on a new host
```bash
git clone <repo-url> ~/gitClones/claude-skills
ln -sfn ~/gitClones/claude-skills ~/.claude/skills
```
