# JoAi Plugins

Install production-ready JoAi MCP apps for ChatGPT, Claude, Codex, Cursor, and other MCP clients.

[Browse apps](https://joai.ai/apps) · [Open JoAi](https://joai.ai) · [Follow on X](https://x.com/JoAiAgents)

## ✨ What You’ll Find

- One public repo per JoAi app plugin
- Hosted MCP integrations with clean install docs and app landing pages
- Dedicated app pages at `joai.ai/en/apps/<slug>`
- Generated plugin bundles synced from the JoAi app catalog

## 🚀 Quick Start

### ChatGPT

Paste any app MCP URL into ChatGPT MCP settings:

```text
https://cortex.joai.ai/mcp/apps/<slug>
```

### Claude

```bash
claude plugin install --scope user joai-plugins/<slug>
```

### Codex

```bash
codex mcp add joai-<slug> --transport http https://cortex.joai.ai/mcp/apps/<slug>
```

### Cursor

```bash
git clone https://github.com/joai-plugins/<slug>.git ~/.cursor/plugins/local/joai-<slug>
```

## 💡 Why This Org Exists

- Discover JoAi apps in a GitHub-native format
- Install the same app across multiple MCP clients
- Land on a clean JoAi app page with docs and context
- Keep public plugin repos lightweight and easy to browse

## ⚙️ How It Works

Every repo in this org maps to one JoAi app slug. The plugin repos are generated from the JoAi warp catalog, published as public install targets, and linked back to their canonical app pages for docs, discovery, and SEO.

That gives every app a clean GitHub repo, a dedicated JoAi landing page, and install paths for ChatGPT, Claude, Codex, Cursor, and other MCP clients.

## 🔎 Explore

- Discover the full catalog: [joai.ai/apps](https://joai.ai/apps)
- Open the main JoAi site: [joai.ai](https://joai.ai)
- Browse this GitHub org: [github.com/joai-plugins](https://github.com/joai-plugins)

## 🙂 A Few Friendly Notes

- These repos are generated artifacts, not hand-maintained codebases.
- OpenAI submission bundles stay private and are not published here.
- Repo homepages point to the corresponding JoAi app pages.
- ✨ Every plugin repo is meant to be easy to scan, install, and share.
