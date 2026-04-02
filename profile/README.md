# JoAi Plugins

Install production-ready JoAi MCP apps for ChatGPT, Claude, Codex, Cursor, and other MCP clients.

[Browse apps](https://joai.ai/apps) · [Open JoAi](https://joai.ai) · [Follow on X](https://x.com/JoAiAgents)

## What This Org Contains

- One public repo per JoAi app plugin
- Hosted MCP integrations with clean install docs and app landing pages
- Dedicated app pages at `joai.ai/en/apps/<slug>`
- Generated plugin bundles synced from the JoAi app catalog

## Quick Start

### Claude

```bash
claude plugin install --scope user joai-plugins/anthropic
```

### Codex

```bash
codex mcp add joai-anthropic --transport http https://cortex.joai.ai/mcp/apps/anthropic
```

### Cursor

```bash
git clone https://github.com/joai-plugins/anthropic.git ~/.cursor/plugins/local/joai-anthropic
```

### ChatGPT

Paste the app MCP URL into ChatGPT MCP settings:

```text
https://cortex.joai.ai/mcp/apps/anthropic
```

## Popular Apps

- [anthropic](https://github.com/joai-plugins/anthropic)
- [openai](https://github.com/joai-plugins/openai)
- [multiversx](https://github.com/joai-plugins/multiversx)
- [xexchange](https://github.com/joai-plugins/xexchange)
- [peerme](https://github.com/joai-plugins/peerme)
- [appointments](https://github.com/joai-plugins/appointments)

## How It Works

Every repo in this org maps to one JoAi app slug. The plugin repos are generated from the JoAi warp catalog, published as public install targets, and linked back to their canonical app pages for docs, discovery, and SEO.

That gives every app a clean GitHub repo, a dedicated JoAi landing page, and install paths for ChatGPT, Claude, Codex, Cursor, and other MCP clients.

## App Directory

See the full catalog here:

- [joai.ai/apps](https://joai.ai/apps)
- [joai.ai/en/apps/anthropic](https://joai.ai/en/apps/anthropic)
- [joai.ai/en/apps/openai](https://joai.ai/en/apps/openai)
- [joai.ai/en/apps/multiversx](https://joai.ai/en/apps/multiversx)

## Notes

- These repos are generated artifacts, not hand-maintained codebases.
- OpenAI submission bundles stay private and are not published here.
- Repo homepages point to the corresponding JoAi app pages.
