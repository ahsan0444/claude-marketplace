# Jintech Claude Marketplace

Internal Claude Code plugin marketplace for Jintech Engineering.

**Supports macOS and Windows.**

---

## Adding this marketplace

```
/plugin marketplace add https://github.com/ahsan0444/claude-marketplace
```

---

## Available plugins

| Plugin | Description | Platforms |
|---|---|---|
| `jintech-omg-dev` | Full SDLC toolkit for OMG — skills, code-review-graph MCP, hooks | macOS, Windows |

---

## Installing a plugin

```
/plugin install jintech-omg-dev
```

---

## Updating a plugin

```
/plugin update jintech-omg-dev
```

---

## Platform notes

All plugins in this marketplace are cross-platform. Hook scripts and server bootstraps are written in Python (not bash) so they work natively on both macOS and Windows without Git Bash or WSL.

**Prerequisites on Windows:**
- Python 3.9+ on PATH (`python3 --version` to verify)
- Git for Windows ([git-scm.com](https://git-scm.com/download/win))
- Claude Code (latest stable)

---

## Adding a new plugin

1. Create the plugin repo following the `.claude-plugin/plugin.json` manifest format.
2. Ensure all scripts are cross-platform (Python preferred over bash).
3. Add an entry to `.claude-plugin/marketplace.json` in this repo.
4. Open a PR — once merged the plugin becomes available to all users.

For questions: #dev-tooling on Slack.
