# AI Dev Navigator

一个面向初学者与进阶开发者的 AI 开发工具信息集成仓库。  
目标：把分散在 GitHub/官网/文档中的信息，整理成**一页可检索导航**。

- 收录范围：AI 编码 CLI、IDE Agent 插件、本地推理与网关、Skills/MCP 生态。
- 收录原则：优先官方来源；命名冲突项单独标注；安装方式尽量给到可执行命令。
- 更新方式：人工核验 + GitHub 数据快照。

---

## 0) 筛选索引（CLI / IDE / Platform + 开源/闭源 + 国产）

### 快速筛选
- 形态：`CLI` / `IDE` / `Platform`
- 许可：`开源` / `闭源或混合`
- 生态：`国产` / `国际`

### 统一筛选总表

| Tool | 形态 | 开源/闭源 | 是否国产 | 入口 |
|---|---|---|---|---|
| Claude Code | CLI | 开源 | 国际 | [repo](https://github.com/anthropics/claude-code) |
| Codex CLI | CLI | 开源 | 国际 | [repo](https://github.com/openai/codex) |
| Gemini CLI | CLI | 开源 | 国际 | [repo](https://github.com/google-gemini/gemini-cli) |
| Qwen Code | CLI | 开源 | 国产 | [repo](https://github.com/QwenLM/qwen-code) |
| Kimi Code CLI | CLI | 开源 | 国产 | [repo](https://github.com/MoonshotAI/kimi-cli) |
| GitHub Copilot CLI | CLI | 开源 | 国际 | [repo](https://github.com/github/copilot-cli) |
| Continue CLI | CLI | 开源 | 国际 | [repo](https://github.com/continuedev/continue) |
| Aider | CLI | 开源 | 国际 | [repo](https://github.com/Aider-AI/aider) |
| Goose | CLI/Platform | 开源 | 国际 | [repo](https://github.com/block/goose) |
| OpenCode | CLI/Platform | 开源 | 国际 | [repo](https://github.com/anomalyco/opencode) |
| OpenHands CLI | CLI | 开源 | 国际 | [repo](https://github.com/OpenHands/OpenHands-CLI) |
| Cursor CLI / Agent | CLI/IDE | 闭源或混合 | 国际 | [docs](https://docs.cursor.com/en/agent/cli) |
| CodeBuddy CLI | CLI | 待核验 | 国产 | [ref](https://cloud.tencent.com/developer/article/2556464) |
| Cline | IDE | 开源 | 国际 | [repo](https://github.com/cline/cline) |
| Roo Code | IDE | 开源 | 国际 | [repo](https://github.com/RooCodeInc/Roo-Code) |
| Continue Extension | IDE | 开源 | 国际 | [repo](https://github.com/continuedev/continue) |
| gh-copilot | IDE/CLI 扩展 | 开源 | 国际 | [repo](https://github.com/github/gh-copilot) |
| Ollama | Platform | 开源 | 国际 | [repo](https://github.com/ollama/ollama) |
| LiteLLM | Platform | 开源 | 国际 | [repo](https://github.com/BerriAI/litellm) |
| OpenHands | Platform | 开源+企业版混合 | 国际 | [repo](https://github.com/OpenHands/OpenHands) |
| Cherry Studio | IDE/Desktop | 开源 | 国产 | [repo](https://github.com/CherryHQ/cherry-studio) |
| FastGPT | Platform | 开源 | 国产 | [repo](https://github.com/labring/FastGPT) |
| RAGFlow | Platform | 开源 | 国产团队主导 | [repo](https://github.com/infiniflow/ragflow) |
| Dify | Platform | 开源 | 国产团队主导 | [repo](https://github.com/langgenius/dify) |
| ModelScope SDK | Platform/SDK | 开源 | 国产 | [repo](https://github.com/modelscope/modelscope) |
| MCP Reference Servers | Platform/Protocol | 开源 | 国际 | [repo](https://github.com/modelcontextprotocol/servers) |

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

## 5) 国内可用 / 国产生态（新增）

> 这一组优先收录国内团队主导、国内可用且有公开仓库/文档的项目。

| Tool | Official Repo | Docs / Site | Install (Quick) | 类型 | GitHub Stars* |
|---|---|---|---|---|---:|
| Qwen Code | [QwenLM/qwen-code](https://github.com/QwenLM/qwen-code) | [qwen docs](https://qwenlm.github.io/qwen-code-docs/en/users/overview) | `curl -fsSL https://qwen-code-assets.oss-cn-hangzhou.aliyuncs.com/installation/install-qwen.sh \| bash` / `npm i -g @qwen-code/qwen-code@latest` | CLI Agent | 18,180 |
| Kimi Code CLI | [MoonshotAI/kimi-cli](https://github.com/MoonshotAI/kimi-cli) | [kimi docs](https://moonshotai.github.io/kimi-cli/en/) | 按官方 Getting Started 安装（PyPI 包：`kimi-cli`） | CLI Agent | 6,140 |
| Cherry Studio | [CherryHQ/cherry-studio](https://github.com/CherryHQ/cherry-studio) | [cherry-ai.com](https://cherry-ai.com) / [docs](https://docs.cherry-ai.com/docs/en-us) | 从 Releases 下载 Windows/macOS/Linux 安装包 | 桌面多模型客户端 | 39,408 |
| FastGPT | [labring/FastGPT](https://github.com/labring/FastGPT) | [fastgpt.io](https://fastgpt.io) | 按官方文档自托管（Docker/Sealos） | RAG/工作流平台 | 27,092 |
| RAGFlow | [infiniflow/ragflow](https://github.com/infiniflow/ragflow) | [ragflow.io](https://ragflow.io) | `docker compose -f docker-compose.yml up -d`（按官方部署文档） | RAG 平台 | 72,920 |
| Dify | [langgenius/dify](https://github.com/langgenius/dify) | [dify.ai](https://dify.ai) / [self-host docs](https://docs.dify.ai/getting-started/install-self-hosted) | `cd docker && docker compose up -d` | LLM 应用平台 | 128,955 |
| ModelScope SDK | [modelscope/modelscope](https://github.com/modelscope/modelscope) | [modelscope.cn](https://www.modelscope.cn/) | `pip install modelscope` | 模型生态 SDK | 8,698 |

---

## 6) 命名冲突与避坑（建议必读）

1. `copilot-cli` vs `gh-copilot`
- `github/copilot-cli`：独立 CLI 主程序。
- `github/gh-copilot`：GitHub CLI 扩展（旧路径/不同产品形态）。

2. Cursor / CodeBuddy
- 相关社区同名仓库很多，优先使用官方文档与官方分发渠道。
- 不确定来源时，不建议直接执行安装脚本。

3. “支持 XXX 模型”不等于“官方工具”
- 优先核验：仓库 owner、官网域名、发布渠道、文档一致性。

---

## 7) 按操作系统一键筛选安装命令（新增）

> 用法：先看你的系统，再直接复制对应区块命令。  
> 提示：以下主要覆盖 CLI 工具；桌面工具（如 Cherry Studio）建议从 Release 安装包安装。

### macOS

```bash
# Node-based CLIs
npm i -g @openai/codex @google/gemini-cli @qwen-code/qwen-code@latest @github/copilot opencode-ai

# Python-based CLIs / SDKs
python -m pip install --upgrade pip
python -m pip install aider-install litellm modelscope kimi-cli

# Install and run
codex
gemini
qwen
copilot
```

### Linux

```bash
# Official install scripts
curl -fsSL https://claude.ai/install.sh | bash
curl -fsSL https://opencode.ai/install | bash
curl -fsSL https://qwen-code-assets.oss-cn-hangzhou.aliyuncs.com/installation/install-qwen.sh | bash
curl -fsSL https://ollama.com/install.sh | sh

# npm path
npm i -g @openai/codex @google/gemini-cli @github/copilot @continuedev/cli

# Python path
python -m pip install aider-install litellm modelscope kimi-cli
```

### Windows (PowerShell)

```powershell
# Script-based installers
irm https://claude.ai/install.ps1 | iex
curl -fsSL -o $env:TEMP\\install-qwen.bat https://qwen-code-assets.oss-cn-hangzhou.aliyuncs.com/installation/install-qwen.bat
& $env:TEMP\\install-qwen.bat

# winget / npm
winget install GitHub.Copilot
npm i -g @openai/codex @google/gemini-cli @github/copilot

# Python
py -m pip install aider-install litellm modelscope kimi-cli
```

---

## 8) 初学者一周路线（快速拿结果）

1. Day 1: 从 `Claude Code / Codex / Gemini CLI / Qwen Code` 中选 1 个。
2. Day 2: 跑通“需求 -> 改代码 -> 本地测试 -> 提交”。
3. Day 3: 接 `Ollama` 或 `LiteLLM`，打通本地/多模型。
4. Day 4: 接一个 MCP server（如文件系统/Git/浏览器类）。
5. Day 5: 在 IDE 里加 `Cline/Roo/Continue` 任一扩展。
6. Day 6: 做一次失败复盘（问题、提示词、修复路径）。
7. Day 7: 对外发布你的 `AGENTS.md + skills` 模板仓库。

---

## 9) 这个仓库如何“更容易涨星”

- 保持“检索价值”而非泛泛介绍：每项都给官方入口和安装方式。
- 持续更新快照：至少每周一次（新增工具、失效链接、安装变更）。
- 明确受众：初学者、CLI 重度用户、IDE 用户分别给路径。
- 内容可复制：命令可直接运行，含命名消歧与避坑。

---

## 10) 前沿模型厂商情报总表（新增，核验日期：2026-02-07）

> 口径说明：  
> - 仅收录官方文档/官方公告/官方仓库可核验信息。  
> - `API 成本`优先写每 1M token 的公开价；若官方页面为动态渲染且无法稳定抓取，给出官方定价入口并标注“以页面实时显示为准”。  
> - `Benchmark`仅记录官方对外公布项，不做二次推导。

| 厂商 | 最新模型（官方页面可见） | 发布时间 | 官方 Benchmark 摘要 | API 成本（公开口径） | 开发者 Console | 聊天/体验入口 |
|---|---|---|---|---|---|---|
| OpenAI | GPT-5.2 / GPT-5.2 mini / GPT-5.2 nano | 见 [OpenAI API Pricing](https://openai.com/api/pricing/) & [Release Notes](https://help.openai.com/en/articles/9624314-model-release-notes) | OpenAI 在发布说明与模型页持续更新，详细分项见官方页 | GPT-5.2: Input `$1.75`, Cached `$0.438`, Output `$14.00` / 1M tokens（见官方价目表） | [platform.openai.com](https://platform.openai.com/) | [chatgpt.com](https://chatgpt.com/) |
| Anthropic | Claude Sonnet 4.5（另含 Opus/Sonnet/Haiku 4） | Sonnet 4.5: `2025-09-29`（官方新闻） | 官方强调 SWE-bench Verified 等编码指标改进 | Sonnet 4: Input `$3`, Output `$15` / 1M tokens；Haiku 4: `$1/$5` | [console.anthropic.com](https://console.anthropic.com/) | [claude.ai](https://claude.ai/) |
| Google | Gemini 2.5 Pro / Flash / Flash-Lite | 见 [Gemini API Release Notes](https://ai.google.dev/gemini-api/docs/release-notes) | 官方长期披露 Arena/HLE 等指标更新 | 2.5 Pro（<=200k 输入）Input `$1.25`, Output `$10` / 1M tokens；Flash 更低价（见官方价目） | [aistudio.google.com](https://aistudio.google.com/) | [gemini.google.com](https://gemini.google.com/) |
| xAI | Grok 4 系列（含 `grok-4-0709`） | 见 [xAI News](https://x.ai/news/grok-4) / 模型列表 | 官方新闻提供基准表现与定位说明 | `grok-4-0709`: Input `$3`, Output `$15` / 1M tokens（见 xAI docs） | [console.x.ai](https://console.x.ai/) | [grok.com](https://grok.com/) |
| DeepSeek | DeepSeek-V3.2 / V3.2-Exp / R1-0528 | `2025-09-29`（V3.2-Exp）等见官方 News | 官方披露长上下文、代码与前端能力提升方向 | DeepSeek Chat（V3.2-Exp）Input Cache Hit `$0.028`, Miss `$0.28`, Output `$0.42` / 1M tokens | [platform.deepseek.com](https://platform.deepseek.com/) | [chat.deepseek.com](https://chat.deepseek.com/) |
| Moonshot (Kimi) | Kimi-K2 系列（含 K2-0905、K2-Think） | `2025-09-05`、`2025-11-06`（官方博客） | 官方博客给出编码与推理能力更新 | 官方博客披露过 K2 Turbo API 调价（如 RMB 口径），以平台实时价目为准 | [platform.moonshot.cn](https://platform.moonshot.cn/) | [kimi.com](https://www.kimi.com/) |
| Zhipu / GLM | GLM-4.7 系列（含 Air / X / Thinking） | `2026-01-12`（GLM-4.7 发布文） | 官方发布文披露多基准领先/对比结果 | GLM-4.7 Air（input）`$0.11`/1M tokens；其余档位见官方定价表 | [open.bigmodel.cn](https://open.bigmodel.cn/) / [docs.z.ai](https://docs.z.ai/) | [chat.z.ai](https://chat.z.ai/) |
| MiniMax | MiniMax-M2 / M2.1 / M1 | M2.1: `2026-01-15`（官方新闻） | 官方给出 VibeCodingBench（88.6）与 Web/Android Agent 等指标 | 最新 API 价格见 [官方定价页](https://www.minimax.io/platform/document/price) | [platform.minimax.io](https://platform.minimax.io/) | [chat.minimax.io](https://chat.minimax.io/) |
| StepFun | Step-3 / Step-3.5 系列 | 见官方文档更新时间（持续） | 官方文档有 MMLU/AIME/Agent 等指标描述 | Step-3（1M tokens）输入 `¥8`、输出 `¥35`（按官方人民币计费） | [platform.stepfun.com](https://platform.stepfun.com/) | [stepfun.com](https://stepfun.com/) |
| Qwen / 阿里云百炼 | Qwen3-Next / Qwen3-Max 等 | `2025-09-23`（Qwen3-Next 发布） | 官方公告披露推理与多任务能力更新 | 百炼计费页有按模型分档价格（含输入/输出、缓存等） | [bailian.console.aliyun.com](https://bailian.console.aliyun.com/) | [chat.qwen.ai](https://chat.qwen.ai/) |
| 文心（百度千帆） | ERNIE-5.0 / X1.1（模型列表可见） | 见千帆文档更新记录（如 `2026-01-08`） | 官方文档给出模型能力与场景说明 | 示例：ERNIE-5.0 输入 `¥0.004/千token`，输出 `¥0.016/千token`（见计费页） | [console.bce.baidu.com/qianfan](https://console.bce.baidu.com/qianfan/overview) | [yiyan.baidu.com](https://yiyan.baidu.com/) |
| 豆包 / 火山方舟 | 豆包系列（Pro/Thinking/视觉等） | 见方舟文档与产品页 | 官方文档持续更新能力说明 | 定价页为动态渲染，建议直接查 [方舟定价文档](https://www.volcengine.com/docs/82379/1099320) | [console.volcengine.com/ark](https://console.volcengine.com/ark) | [doubao.com](https://www.doubao.com/) |
| 腾讯混元 | hunyuan 系列（T1/TurboS 等） | 计费页更新至 `2026-02-05` | 官方文档持续补充场景与模型能力 | 示例：`hunyuan-t1-latest` 输入 `¥4/百万token`，输出 `¥16/百万token` | [console.cloud.tencent.com/hunyuan](https://console.cloud.tencent.com/hunyuan) | [yuanbao.tencent.com](https://yuanbao.tencent.com/) |
| LongCat（美团） | LongCat-Flash-Chat | 技术报告 `2025`（arXiv:2509.01322） | 官方 README 公布了 MMLU、AIME、SWE-bench、TerminalBench、τ²-Bench 等大量分数 | 公开仓库未提供统一 API 商业计费页 | [longcat.ai](https://longcat.ai/)（含官方入口） | [longcat.ai](https://longcat.ai/) |
| MiMo（小米） | MiMo-7B-RL-0530 | 更新 `2025-05-30` | 官方 README 公布 AIME24 `80.1`、LCB v5 `60.9`、GPQA `60.6` 等 | 开源模型仓库口径，未给官方统一 API 商业价 | [huggingface.co/XiaomiMiMo](https://huggingface.co/XiaomiMiMo) / [modelscope](https://www.modelscope.cn/organization/XiaomiMiMo) | 开源模型为主（无独立官方聊天站） |

---

## 11) Claude Code / GPT Codex 相关 Coding Plan（新增）

| 方案 | 官方入口 | 价格/计费 | 备注 |
|---|---|---|---|
| Claude Code（Anthropic 官方） | [code.claude.com/pricing](https://www.anthropic.com/pricing#api) / [docs](https://docs.anthropic.com/en/docs/claude-code/costs) | Claude Code 本体按 Anthropic 订阅与 API 用量组合；API 单价见官方 pricing | 官方文档有成本控制与限额说明 |
| OpenAI Codex（CLI/Cloud） | [developers.openai.com/codex/pricing](https://developers.openai.com/codex/pricing/) | Plus `$20/月`，Pro `$200/月`，Business `$30/用户/月`，另可 API key 按 token 计费 | 适合“订阅 + API 混合”用法 |
| GLM Coding Plan | [z.ai/coding-plan](https://www.z.ai/coding-plan) | 官方页面显示从 `20 元/月` 起（并有更高档） | 提供面向编码场景的订阅层 |
| MiniMax Claude Code 方案 | [minimax 文档](https://www.minimax.io/platform/document/claude-code) | 官方文档显示 `$10 / $20 / $50` 分层 | 覆盖 Claude Code 兼容接入说明 |
| 火山引擎 ModelArk Coding 方案 | [modelark 产品页](https://www.volcengine.com/product/modelark) | 官方活动/套餐信息有阶段性变动，以产品页实时显示为准 | 建议绑定方舟控制台核验最新权益 |
| Kimi / Moonshot（CLI + API） | [kimi-cli docs](https://moonshotai.github.io/kimi-cli/en/) + [moonshot platform](https://platform.moonshot.cn/) | 当前以 API 计费为主；活动价/促销价见官方博客与控制台 | 暂未看到独立“Coding Plan”固定命名页 |

---

## 12) 主流 AI CLI 价格对比（新增）

> 价格变化很快，以下用于“入口导航 + 预算预估”，最终以官方链接实时价格为准。

| CLI | 官方入口 | 价格口径（2026-02-07 核验） |
|---|---|---|
| Claude Code | [Anthropic](https://www.anthropic.com/pricing#api) / [Docs](https://docs.anthropic.com/en/docs/claude-code/costs) | 订阅 + API 混合；API 参考 Sonnet/Haiku 档位 |
| Codex CLI | [OpenAI Codex Pricing](https://developers.openai.com/codex/pricing/) | Plus `$20/月`，Pro `$200/月`，Business `$30/seat/月`，或 API token 计费 |
| Gemini CLI | [Gemini CLI docs](https://geminicli.com/docs/) + [Gemini API Pricing](https://ai.google.dev/gemini-api/docs/pricing) | CLI 本身开源，实际成本取决于 Gemini API 用量 |
| Qwen Code | [Qwen Code docs](https://qwenlm.github.io/qwen-code-docs/en/users/overview) + [百炼计费](https://help.aliyun.com/zh/model-studio/billing-of-model-studio) | CLI 开源，按百炼/所接模型计费 |
| Kimi CLI | [Kimi CLI docs](https://moonshotai.github.io/kimi-cli/en/) | CLI 开源，按 Moonshot API 用量计费 |
| GitHub Copilot CLI | [GitHub Docs](https://docs.github.com/copilot/concepts/agents/about-copilot-cli) | 通常随 Copilot 订阅层提供（Free/Pro/Business/Enterprise） |
| Aider | [aider docs](https://aider.chat/docs/install.html) | 工具开源免费，按所用模型 API 计费 |
| OpenHands CLI | [OpenHands CLI](https://docs.openhands.dev/openhands/usage/cli/installation) | 工具开源免费，按所连模型/服务计费 |

---

## 13) 维护建议（针对“涨星/涨关注”）

1. 每周固定更新时间戳与新增模型（可在 README 顶部加 `Last verified`）。
2. 所有价格都配官方链接，避免转载二手截图。
3. 每次新增厂商时强制补齐 6 列：发布时间、Benchmark、API 成本、Console、Chat、CLI/SDK 入口。
4. 增加“变更日志”区块（按周记录新增模型和价格变化）。
5. 保持“能检索 + 能复制 + 能对比”：这是最容易被收藏/Star 的信息型仓库形态。

---

## Sources

已核验来源见 `SOURCES.md`（包含官方仓库、官网文档、消歧参考链接）。

## License
MIT
