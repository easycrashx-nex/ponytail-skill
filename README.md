# PONYTAIL

> Der beste Code ist der, den du nie geschrieben hast.
>
> Weniger ist mehr.

PONYTAIL is a portable Agent Skill for software work. It behaves like a pragmatic, pleasantly lazy senior developer: question unnecessary work, reuse what exists, and otherwise make the smallest clean change.

Minimal scope does not mean minimal quality. PONYTAIL preserves structure, readability, relevant tests, security, and data integrity.

## Protocol

- **P — Pause:** Verify the problem.
- **O — Observe:** Search for an existing solution.
- **N — Necessary:** Confirm it must be built now.
- **Y — YAGNI:** Serve current needs only.
- **T — Tiniest change:** Keep the change complete and reversible.
- **A — Avoid baggage:** Reject unnecessary dependencies and abstractions.
- **I — Inspect:** Check behavior, tests, security, and structure.
- **L — Leave it cleaner:** Avoid leaving more complexity behind.

## Install

PONYTAIL follows the [Agent Skills specification](https://agentskills.io/specification). Clone the repository into the personal skill directory used by your agent.

### Codex

```sh
git clone https://github.com/easycrashx-nex/ponytail-skill.git "$HOME/.agents/skills/ponytail"
```

See the [Codex skills documentation](https://developers.openai.com/codex/skills).

### Claude Code

```sh
git clone https://github.com/easycrashx-nex/ponytail-skill.git "$HOME/.claude/skills/ponytail"
```

See the [Claude Code skills documentation](https://code.claude.com/docs/en/skills).

### Other LLMs

If your tool supports the open Agent Skills format, install this repository in its skill directory. Otherwise, paste the contents of [`SKILL.md`](SKILL.md) into the system or custom instructions before starting software work.

Automatic activation depends on the host tool. The instructions themselves are model-independent and require no scripts, packages, network access, or external tools.

## License

[MIT](LICENSE)
