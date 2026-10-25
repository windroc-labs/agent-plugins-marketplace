# agent-plugins-marketplace

The `windroc` plugin marketplace for Claude Code and Codex: `.claude-plugin/marketplace.json` for Claude Code, `.agents/plugins/marketplace.json` for Codex. Keep the two plugin lists the same.

## Install

In Claude Code:

```
/plugin marketplace add windroc-labs/agent-plugins-marketplace
/plugin install updraft@windroc
/plugin install ensemble@windroc
```

In Codex:

```
codex plugin marketplace add windroc-labs/agent-plugins-marketplace
codex plugin add updraft@windroc
codex plugin add ensemble@windroc
```

## Plugins

| Plugin | Description |
| :- | :- |
| [updraft](https://github.com/windroc-labs/updraft) | Autonomous end-to-end feature pipeline: spec, plan, implementation, tests, review loops and docs. |
| [ensemble](https://github.com/windroc-labs/ensemble) | Commander session guidelines, core roles (researcher, pm, engineer) run in this conversation, and fixed board issue commands. |

## License

[MIT](LICENSE)
