# poenv agent skill

The [Agent Skill](https://agentskills.io) for [poenv](https://github.com/pogicodes/poenv), a local encrypted vault for app configs and secrets. It gives Claude Code, Codex, Cursor, Gemini CLI, GitHub Copilot, OpenCode and other agents a `/poenv` command: set up a repo, switch envs and run commands with an env injected, using key names only.

```bash
npx skills@1.7.6 add pogicodes/poenv-skill
```

The skill doesn't install poenv. It asks you to install it yourself: see [poenv's install instructions](https://github.com/pogicodes/poenv#install).

The skill is [`skills/poenv/SKILL.md`](skills/poenv/SKILL.md). Issues and changes go to [pogicodes/poenv](https://github.com/pogicodes/poenv).

MIT licensed.
