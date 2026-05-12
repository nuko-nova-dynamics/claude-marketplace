# Nuko Nova Tools — Claude Code Plugins

A marketplace of Claude Code plugins built at [Nuko Nova Dynamics](https://github.com/nuko-nova-dynamics).

## Install

```bash
/plugin marketplace add nuko-nova-dynamics/claude-marketplace
```

Then install individual plugins from the catalog:

```bash
/plugin install <plugin-name>@nuko-nova-tools
```

## Plugins

### claude-goal

Codex-style autonomous goal loop. Type `/goal-start "objective"` and the agent self-drives turns under deterministic token budgets, with pause/resume, `/goal-extend`, `/compact` recovery, per-subagent token attribution, and persistence across `claude` restart. Complements Claude Code 2.1.139+'s built-in `/goal`.

```bash
/plugin install claude-goal@nuko-nova-tools
```

Source: [nuko-nova-dynamics/claude-goal](https://github.com/nuko-nova-dynamics/claude-goal)

## Updating

Refresh the marketplace catalog to pick up new plugins or version bumps:

```bash
/plugin marketplace update nuko-nova-tools
/plugin update <plugin-name>
```

## Contributing

This marketplace catalog is open for Nuko Nova Dynamics tools. To propose a new plugin or fix the catalog, open a PR against this repo.

## License

MIT
