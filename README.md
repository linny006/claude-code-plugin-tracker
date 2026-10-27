<!--
SEO: claude code plugin tracker
-->

<div align="center">

# Claude Code Plugin Tracker

Live index of Claude Code extensions, hooks, and plugins — refreshed every 15 minutes from GitHub

[![Stars](https://img.shields.io/github/stars/linny006/claude-code-plugin-tracker?style=for-the-badge&logo=github)](https://github.com/linny006/claude-code-plugin-tracker/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/linny006/claude-code-plugin-tracker?style=for-the-badge)](https://github.com/linny006/claude-code-plugin-tracker/commits)
[![Items](https://img.shields.io/badge/Tracked_Items-6-brightgreen?style=for-the-badge)](#)
[![Updated](https://img.shields.io/badge/Updates-every_15min-blue?style=for-the-badge)](#)

**⭐ Star this repo to bookmark — fresh data every 15 minutes**

[English](./README.md) · [中文](./README_CN.md) · [日本語](./README_JA.md) · [한국어](./README_KO.md) · [Español](./README_ES.md) · [Português](./README_PT.md)

</div>

---

## 💡 What is this?

Automatically discovers and indexes Claude Code plugins, extensions, and hook configurations by scanning GitHub topics, repositories, and release activity. Generates a browsable markdown catalog and JSON API updated every 15 minutes via GitHub Actions, so users never need to manually search for new tooling.

This list is **auto-updated every 15 minutes** by a GitHub Actions cron.
Each commit reflects a real change in the upstream data source — new items added,
expired items removed — so you can rely on what you see being current.

---

## 📋 Current Items

> ⏰ Last updated: 2026-10-27 12:30 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [rishb0/resume-harness](https://github.com/rishb0/resume-harness) | 0 | Python | 2026-10-27 | Open-source harness for AI coding agents that builds ATS-safe, job-specific resumes with a truth check, reusable saved d |
| 2 | [snuffish/dotfiles](https://github.com/snuffish/dotfiles) | 0 | Shell | 2026-10-27 | Modular Bash/zsh, Neovim (LazyVim), tmux and WezTerm dotfiles, plus a Claude Code agent skills folder. |
| 3 | [l69d/receipts](https://github.com/l69d/receipts) | 0 | JavaScript | 2026-10-27 | Show the receipts for your work: one link with what you shipped and what it changed, a link to every deliverable - kept  |
| 4 | [dravr-ai/dravr-embacle](https://github.com/dravr-ai/dravr-embacle) | 8 | Rust | 2026-10-27 | Rust library wrapping 12 AI CLI tools as pluggable LLM providers — with OpenAI API client, ACP headless mode, agent loop |
| 5 | [unmet23-lab/synk-appsscript](https://github.com/unmet23-lab/synk-appsscript) | 0 | JavaScript | 2026-10-27 | SYNK LAB 운영·교육 엔진 — 몽골 한국어 학원의 수업·운영 (Apps Script + 스프레드시트) |
| 6 | [Bake-Ware/rook](https://github.com/Bake-Ware/rook) | 4 | Python | 2026-10-27 | Run things on all your machines from one place: a web dashboard, a terminal UI, or any AI agent that speaks MCP. Self-ho |
<!-- TRACKER_TABLE_END -->

---

## 🔍 How it works

Every 15 minutes, a GitHub Action runs `tracker.py`. That script:

1. Fetches the latest state from `GitHub Search API`.
2. Diffs against `data/items.json` (the previous snapshot).
3. Rewrites the table above between the `<!-- TRACKER_TABLE_* -->` markers.
4. Commits `feat: +N added, -M removed (timestamp)` if anything changed.

No external services. No paid APIs. Just a public data source and a free GitHub Action.

---

## 🤝 Contributing

See `CONTRIBUTING.md` — usually you don't need to: the tracker keeps itself current.
If you spot a data-source bug or want to suggest a new column for the table, open
an issue.

---

## 🔗 Related live trackers

If you find this useful, you might also like these other auto-updated
trackers from the same maintainer — same mechanism, different upstream:

- [trending-claude-skills](https://github.com/linny006/trending-claude-skills) — What's shipping in Claude Skills this week (`topic:claude-skills`)
- [mcp-servers-live](https://github.com/linny006/mcp-servers-live) — Live index of newest MCP servers (`topic:mcp-server`)
- [cursor-rules-live](https://github.com/linny006/cursor-rules-live) — Newest Cursor rules and .cursorrules patterns (`topic:cursor-rules`)
- [llm-agents-radar](https://github.com/linny006/llm-agents-radar) — Newest LLM agent frameworks (`topic:llm-agent`)
- [rag-radar](https://github.com/linny006/rag-radar) — Newest RAG implementations and tools (`topic:rag`)
- [llm-eval-tracker](https://github.com/linny006/llm-eval-tracker) — Newest LLM evaluation tools and benchmarks (`topic:llm-eval`)
- [agent-framework-radar](https://github.com/linny006/agent-framework-radar) — Newest agent frameworks shipping on GitHub (`topic:agent-framework`)
- [vector-db-live](https://github.com/linny006/vector-db-live) — Newest vector DB projects and integrations (`topic:vector-database`)
- [llmops-radar](https://github.com/linny006/llmops-radar) — Newest LLMOps tooling (observability, deployment) (`topic:llmops`)
- [prompt-tools-live](https://github.com/linny006/prompt-tools-live) — Newest prompt-engineering tools and prompt repos (`topic:prompt-engineering`)
- [agent-eval-harness](https://github.com/linny006/agent-eval-harness) — Live benchmark of AI coding agents (`topic:llm-eval`)
- [skills-tracker](https://github.com/linny006/skills-tracker) — Tracking new GitHub 'skills' repos (`topic:agent-skills`)
- [awesome-agent-skills](https://github.com/linny006/awesome-agent-skills) — Curated auto-updated awesome-list of AI agent skills (`topic:agent-skills`)

---

## 📜 License

MIT — see `LICENSE`.
