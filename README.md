# SkyNET marketplace

Claude Code plugin marketplace for the SkyNET plugins.

| Plugin | Source repo | What it does |
|---|---|---|
| `review-council` | [SkyNET-review](https://github.com/CornelB/SkyNET-review) | Four-lens code review, local or as a multi-harness tribunal |
| `skynet` | [SkyNET-agents](https://github.com/CornelB/SkyNET-agents) | Usage-aware delegation to Codex, Antigravity or Ollama |
| `skynet-skills` | [SkyNET-skills](https://github.com/CornelB/SkyNET-skills) | The skills under `skills/` (hooks are not packaged) |

## Install

```bash
claude plugin marketplace add CornelB/SkyNET-marketplace
```

```bash
claude plugin install review-council@skynet-marketplace
```

```bash
claude plugin install skynet@skynet-marketplace
```

```bash
claude plugin install skynet-skills@skynet-marketplace
```

Private source repos clone with your own git credentials (`gh auth login` or an SSH key with access).

## Update

```bash
claude plugin marketplace update skynet-marketplace
```

Each plugin is fetched from its repo's default branch; this repo only lists them.
