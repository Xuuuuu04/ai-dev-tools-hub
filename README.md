# AI Dev Navigator

一个面向初学者与进阶开发者的 AI 开发工具信息集成仓库。  
目标：把分散在 GitHub/官网/文档中的信息，整理成**一页可检索导航**。

- 收录范围：AI 编码 CLI、IDE Agent 插件、本地推理与网关、Skills/MCP 生态。
- 收录原则：优先官方来源；命名冲突项单独标注；安装方式尽量给到可执行命令。
- 更新方式：人工核验 + GitHub 数据快照。

---

## 1) AI Coding CLI（终端主力）

| Tool | Official Repo | Docs / Site | Install (Quick) | 类型 | GitHub Stars* |
|---|---|---|---|---|---:|
| Claude Code | [anthropics/claude-code](https://github.com/anthropics/claude-code) | [code.claude.com/docs](https://code.claude.com/docs/en/overview) | `curl -fsSL https://claude.ai/install.sh \| bash` | CLI Agent | 64,940 |
| Codex CLI | [openai/codex](https://github.com/openai/codex) | [developers.openai.com/codex](https://developers.openai.com/codex) | `npm i -g @openai/codex` | CLI Agent | 59,323 |
| Gemini CLI | [google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli) | [geminicli.com/docs](https://geminicli.com/docs/) | `npm i -g @google/gemini-cli` 或 `npx @google/gemini-cli` | CLI Agent | 93,831 |
| Qwen Code | [QwenLM/qwen-code](https://github.com/QwenLM/qwen-code) | [qwen docs](https://qwenlm.github.io/qwen-code-docs/en/users/overview) | `npm i -g @qwen-code/qwen-code@latest` | CLI Agent | 18,180 |
| Kimi Code CLI | [MoonshotAI/kimi-cli](https://github.com/MoonshotAI/kimi-cli) | [kimi.com/code](https://www.kimi.com/code/) / [docs](https://moonshotai.github.io/kimi-cli/en/) | `pip install kimi-cli`（见官方文档） | CLI Agent | 6,140 |
| GitHub Copilot CLI | [github/copilot-cli](https://github.com/github/copilot-cli) | [GitHub docs](https://docs.github.com/copilot/concepts/agents/about-copilot-cli) | `brew install copilot-cli` 或 `npm i -g @github/copilot` | CLI Agent | 8,072 |
| Continue CLI | [continuedev/continue](https://github.com/continuedev/continue) | [docs.continue.dev](https://docs.continue.dev) | `curl -fsSL https://raw.githubusercontent.com/continuedev/continue/main/extensions/cli/scripts/install.sh \| bash` 或 `npm i -g @continuedev/cli` | CLI + IDE | 31,276 |
| Aider | [Aider-AI/aider](https://github.com/Aider-AI/aider) | [aider.chat](https://aider.chat/docs/install.html) | `python -m pip install aider-install && aider-install` | CLI Agent | 40,397 |
| Goose | [block/goose](https://github.com/block/goose) | [block.github.io/goose](https://block.github.io/goose/docs/quickstart) | 见官方安装页 | CLI/Desktop Agent | 30,034 |
| OpenCode | [anomalyco/opencode](https://github.com/anomalyco/opencode) | [opencode.ai/docs](https://opencode.ai/docs) | `curl -fsSL https://opencode.ai/install \| bash` 或 `npm i -g opencode-ai@latest` | CLI/Desktop Agent | 99,347 |
| OpenHands CLI | [OpenHands/OpenHands-CLI](https://github.com/OpenHands/OpenHands-CLI) | [OpenHands CLI docs](https://docs.openhands.dev/openhands/usage/cli/installation) | `uv tool install openhands --python 3.12` 或 `curl -fsSL https://install.openhands.dev/install.sh \| sh` | CLI Agent | 99 |
| Cursor CLI / Agent | N/A | [Cursor docs](https://docs.cursor.com/en/agent/cli) | 按官方文档安装 | CLI / IDE Agent | - |
| CodeBuddy CLI | N/A (命名冲突多) | [腾讯云活动文档示例](https://cloud.tencent.com/developer/article/2556464) | 建议先核验官方产品页再安装 | CLI (待核验) | - |

> *Stars 快照时间：2026-02-07（通过 `gh api` 抓取）。

---

## 2) IDE Agent / 扩展生态

| Tool | Repo / Marketplace | 安装方式 | 备注 | GitHub Stars* |
|---|---|---|---|---:|
| Cline | [cline/cline](https://github.com/cline/cline) / [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=saoudrizwan.claude-dev) | VS Code 扩展市场安装 | 高活跃，偏 VS Code 工作流 | 57,661 |
| Roo Code | [RooCodeInc/Roo-Code](https://github.com/RooCodeInc/Roo-Code) / [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=RooVeterinaryInc.roo-cline) | VS Code 扩展市场安装 | “编辑器内多 agent 团队”定位 | 22,140 |
| Continue | [continuedev/continue](https://github.com/continuedev/continue) / [Continue Marketplace](https://marketplace.visualstudio.com/items?itemName=Continue.continue) | VS Code/JetBrains 插件安装 | CLI + IDE 双形态 | 31,276 |
| GitHub CLI Copilot Extension（旧路径） | [github/gh-copilot](https://github.com/github/gh-copilot) | `gh extension install github/gh-copilot` | 注意它是 `gh` 扩展，不是新版 `copilot-cli` | 1,124 |

---

## 3) 本地模型与网关（给 CLI 提供底层能力）

| Tool | Official Repo | Docs / Site | Install (Quick) | 用途 | GitHub Stars* |
|---|---|---|---|---|---:|
| Ollama | [ollama/ollama](https://github.com/ollama/ollama) | [ollama.com](https://ollama.com) | Linux: `curl -fsSL https://ollama.com/install.sh \| sh` | 本地模型运行时 | 162,002 |
| LiteLLM | [BerriAI/litellm](https://github.com/BerriAI/litellm) | [docs.litellm.ai](https://docs.litellm.ai/docs/) | `pip install litellm` | 统一多模型 API 网关 | 35,418 |
| OpenHands (GUI/平台) | [OpenHands/OpenHands](https://github.com/OpenHands/OpenHands) | [openhands.dev](https://openhands.dev) | 见官方运行文档 | Agent 平台/本地与云 | 67,568 |

---

## 4) Skills / MCP / 规则生态（高相关）

| Project | Link | 用途 | GitHub Stars* |
|---|---|---|---:|
| MCP Reference Servers | [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) | 官方 MCP 参考实现（Filesystem/Git/Fetch 等） | 78,175 |
| Awesome Agent Skills | [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills) | 社区 skills 聚合 | 6,310 |
| Antigravity Awesome Skills | [sickn33/antigravity-awesome-skills](https://github.com/sickn33/antigravity-awesome-skills) | 大规模 skills 集合 | 7,657 |
| Agent Rules | [steipete/agent-rules](https://github.com/steipete/agent-rules) | 多 agent 规则模板 | 5,562 |
| Figma Context MCP | [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) | 设计到代码场景常用 MCP | 13,016 |

---

## 5) 命名冲突与避坑（建议必读）

1. `copilot-cli` vs `gh-copilot`
- `github/copilot-cli`：独立 CLI 主程序。
- `github/gh-copilot`：GitHub CLI 扩展（旧路径/不同产品形态）。

2. Cursor / CodeBuddy
- 相关社区同名仓库很多，优先使用官方文档与官方分发渠道。
- 不确定来源时，不建议直接执行安装脚本。

3. “支持 XXX 模型”不等于“官方工具”
- 优先核验：仓库 owner、官网域名、发布渠道、文档一致性。

---

## 6) 初学者一周路线（快速拿结果）

1. Day 1: 从 `Claude Code / Codex / Gemini CLI / Qwen Code` 中选 1 个。
2. Day 2: 跑通“需求 -> 改代码 -> 本地测试 -> 提交”。
3. Day 3: 接 `Ollama` 或 `LiteLLM`，打通本地/多模型。
4. Day 4: 接一个 MCP server（如文件系统/Git/浏览器类）。
5. Day 5: 在 IDE 里加 `Cline/Roo/Continue` 任一扩展。
6. Day 6: 做一次失败复盘（问题、提示词、修复路径）。
7. Day 7: 对外发布你的 `AGENTS.md + skills` 模板仓库。

---

## 7) 这个仓库如何“更容易涨星”

- 保持“检索价值”而非泛泛介绍：每项都给官方入口和安装方式。
- 持续更新快照：至少每周一次（新增工具、失效链接、安装变更）。
- 明确受众：初学者、CLI 重度用户、IDE 用户分别给路径。
- 内容可复制：命令可直接运行，含命名消歧与避坑。

---

## Sources

已核验来源见 `SOURCES.md`（包含官方仓库、官网文档、消歧参考链接）。

## License
MIT
