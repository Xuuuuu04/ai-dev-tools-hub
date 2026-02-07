# AI Dev Tools Hub

面向初学者的 AI 开发工具信息集成仓库：统一收录**官方仓库 / 官网 / 安装方式 / 入门备注**。

## Why
- 解决“工具太多、命名相似、安装入口分散”的问题。
- 用一张表快速判断：这是不是官方、怎么装、适合谁。

## Quick Index (2026-02-07)

| Tool | Official Repo | Official Site / Docs | Install (Quick) | Notes |
|---|---|---|---|---|
| Claude Code | [anthropics/claude-code](https://github.com/anthropics/claude-code) | [code.claude.com/docs](https://code.claude.com/docs/en/overview) | `curl -fsSL https://claude.ai/install.sh | bash` | npm 安装已标记 deprecated（见仓库 README） |
| Gemini CLI | [google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli) | [geminicli.com/docs](https://geminicli.com/docs/) | `npm i -g @google/gemini-cli` | 支持 `npx @google/gemini-cli` |
| Qwen Code | [QwenLM/qwen-code](https://github.com/QwenLM/qwen-code) | [qwen-code-docs](https://qwenlm.github.io/qwen-code-docs/en/users/overview) | `npm i -g @qwen-code/qwen-code@latest` | 也提供 shell 安装脚本 |
| Codex CLI | [openai/codex](https://github.com/openai/codex) | [developers.openai.com/codex](https://developers.openai.com/codex) | `npm i -g @openai/codex` | 也可 `brew install --cask codex` |
| Kimi Code CLI | [MoonshotAI/kimi-cli](https://github.com/MoonshotAI/kimi-cli) | [kimi.com/code](https://www.kimi.com/code/) / [docs](https://moonshotai.github.io/kimi-cli/en/) | 参考官方 Getting Started | PyPI 包名 `kimi-cli` |
| GitHub Copilot CLI | [github/copilot-cli](https://github.com/github/copilot-cli) | [GitHub Docs](https://docs.github.com/copilot/concepts/agents/about-copilot-cli) | `brew install copilot-cli` 或 `npm i -g @github/copilot` | **注意**与旧工具同名混淆 |
| GitHub CLI Copilot Extension (旧) | [github/gh-copilot](https://github.com/github/gh-copilot) | [GitHub Docs](https://docs.github.com/en/copilot/github-copilot-in-the-cli) | `gh extension install github/gh-copilot` | 这是 `gh` 扩展，不是新版 Copilot CLI 主程序 |
| Cursor CLI / Agent | N/A (未见统一官方仓库) | [Cursor docs](https://docs.cursor.com/en/agent/cli) | 见 Cursor 文档 | 当前更多以官方文档分发为准 |
| CodeBuddy CLI | N/A (社区项目较多) | [Tencent Cloud CodeBuddy CLI Activity](https://cloud.tencent.com/developer/article/2556464) | 以活动/产品页为准 | 同名社区仓库较多，建议先核验来源 |

## Star Snapshot (GitHub repos only)
- google-gemini/gemini-cli: **93,832**
- anthropics/claude-code: **64,933**
- openai/codex: **59,322**
- QwenLM/qwen-code: **18,180**
- github/copilot-cli: **8,071**
- MoonshotAI/kimi-cli: **6,140**
- github/gh-copilot: **1,124**

> Snapshot generated on **2026-02-07** via `gh api`.

## Positioning
- 本仓库不是评测排名，而是**检索入口**。
- 目标：让新手 3 分钟内选型并装上第一个 CLI。

## Contribution
欢迎 PR：
- 新工具补充（必须给出官方来源）
- 安装命令更新
- 失效链接修复

## License
MIT
