# Jintech Claude Marketplace

Internal Claude Code plugin marketplace for Jintech Engineering.

## Adding this marketplace

```bash
/plugin marketplace add https://github.com/jintech/claude-marketplace
```

## Available plugins

| Plugin | Description |
|---|---|
| `jintech-omg-dev` | Full SDLC toolkit for OMG — skills, code-review-graph MCP, hooks |

## Installing a plugin

```bash
/plugin install jintech-omg-dev
```

## Updating plugins

```bash
/plugin update jintech-omg-dev
```

## Adding a new plugin

1. Create the plugin repo under the `jintech` GitHub org following the `.claude-plugin/plugin.json` manifest format.
2. Add an entry to `marketplace.json` in this repo.
3. Open a PR — once merged the plugin becomes available to all users.
