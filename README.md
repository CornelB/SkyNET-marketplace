# SkyNET marketplace

Claude Code plugin marketplace for the SkyNET plugins.

| Plugin | Source repo | What it does |
|---|---|---|
| `SkyNET-review` | [SkyNET-review](https://github.com/CornelB/SkyNET-review) | Four-lens code review, local or as a multi-harness tribunal |
| `SkyNET-agents` | [SkyNET-agents](https://github.com/CornelB/SkyNET-agents) | Usage-aware delegation to Codex, Antigravity or Ollama |
| `SkyNET-skills` | [SkyNET-skills](https://github.com/CornelB/SkyNET-skills) | The skills under `skills/` (hooks are not packaged) |

## Install

```bash
claude plugin marketplace add CornelB/SkyNET-marketplace
```

```bash
claude plugin install SkyNET-review@SkyNET-marketplace
```

```bash
claude plugin install SkyNET-agents@SkyNET-marketplace
```

```bash
claude plugin install SkyNET-skills@SkyNET-marketplace
```

Private source repos clone with your own git credentials (`gh auth login` or an SSH key with access).

## Update

```bash
claude plugin marketplace update SkyNET-marketplace
```

Each plugin is fetched from its repo's default branch; this repo only lists them.
