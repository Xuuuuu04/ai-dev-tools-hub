# AI Dev Navigator

一个面向初学者与进阶开发者的 AI 开发工具信息集成仓库。

> 最新核验时间：`2026-02-07`

---

## 1. 前沿模型厂商情报

> **价格单位**：人民币（¥）/ 百万 tokens | **汇率参考**：$1 ≈ ¥7.2（2026-02-07）

| 厂商 | 最新模型 | 发布时间 | 输入（¥/百万tokens） | 输出（¥/百万tokens） | 缓存（¥/百万tokens） | 开发者 Console | 体验入口 |
|:---|:---|:---|:---:|:---:|:---:|:---|:---|
| **OpenAI** | GPT-5.3-Codex | `2026-02-05` | `12.6` | `100.8` | `1.26` | [platform.openai.com](https://platform.openai.com/) | [chatgpt.com](https://chatgpt.com/) |
| **OpenAI** | GPT-5.2 Pro | `2025-12-10` | `151.2` | `1209.6` | 不支持缓存 | [platform.openai.com](https://platform.openai.com/) | [chatgpt.com](https://chatgpt.com/) |
| **Anthropic** | Claude Opus 4.6 | `2026-02-05` | `36` | `180` | `3.6`（读）`45`（写） | [console.anthropic.com](https://console.anthropic.com/) | [claude.ai](https://claude.ai/) |
| **Anthropic** | Claude Sonnet 4.5 | `2025-10-01` | `21.6` | `108` | `2.16`（读）`27`（写） | [console.anthropic.com](https://console.anthropic.com/) | [claude.ai](https://claude.ai/) |
| **Anthropic** | Claude Haiku 4.5 | `2025-10-15` | `7.2` | `36` | `0.72`（读）`9`（写） | [console.anthropic.com](https://console.anthropic.com/) | [claude.ai](https://claude.ai/) |
| **Google** | Gemini 3 Pro（≤200k） | `2025-11-18` | `14.4` | `86.4` | `1.44`（≤200k）`2.88`（>200k）存储`32.4`/小时 | [aistudio.google.com](https://aistudio.google.com/) | [gemini.google.com](https://gemini.google.com/) |
| **Google** | Gemini 3 Pro（>200k） | `2025-11-18` | `28.8` | `129.6` | `2.88` 存储`32.4`/小时 | [aistudio.google.com](https://aistudio.google.com/) | [gemini.google.com](https://gemini.google.com/) |
| **Google** | Gemini 3 Flash | `2025-12-17` | `3.6` | `21.6` | `0.36` 存储`32.4`/小时 | [aistudio.google.com](https://aistudio.google.com/) | [gemini.google.com](https://gemini.google.com/) |
| **xAI** | Grok 4.1 Fast | `2025-11-17` | `1.44` | `3.6` | `0.36` | [console.x.ai](https://console.x.ai/) | [grok.com](https://grok.com/) |
| **xAI** | Grok 4 | `2025-07-09` | `21.6` | `108` | `5.4` | [console.x.ai](https://console.x.ai/) | [grok.com](https://grok.com/) |
| **DeepSeek** | DeepSeek-V3.2 | `2025-12-01` | `1.94` | `7.92` | `0.50` | [platform.deepseek.com](https://platform.deepseek.com/) | [chat.deepseek.com](https://chat.deepseek.com/) |
| **Moonshot (Kimi)** | Kimi K2.5 | `2026-01-27` | `3.24-4.32` | `18-21.6` | `0.72-1.08` | [platform.moonshot.cn](https://platform.moonshot.cn/) | [kimi.com](https://www.kimi.com/) |
| **Zhipu / GLM** | GLM-4.7 | `2025-12-22` | `2.88` | `10.8` | `0.41`（读）`0.41-0.79`（写） | [open.bigmodel.cn](https://open.bigmodel.cn/) | [chat.z.ai](https://chat.z.ai/) |
| **MiniMax** | MiniMax-M2.1 | `2025-12-23` | `2.16` | `8.64` | `0.22`（读）`2.7`（写） | [platform.minimax.io](https://platform.minimax.io/) | [chat.minimax.io](https://chat.minimax.io/) |
| **StepFun** | Step-3.5-Flash | `2026-02` | `0.70`（未命中）`0.14`（命中） | `2.10` | `0.14`（命中时按20%计费） | [platform.stepfun.com](https://platform.stepfun.com/) | [stepfun.com](https://stepfun.com/) |
| **StepFun** | Step3 | `2025-07-31` | `1.5-4`（未命中）`0.3-0.8`（命中） | `4-10` | `0.3-0.8`（命中时按20%计费，视上下文长度） | [platform.stepfun.com](https://platform.stepfun.com/) | [stepfun.com](https://stepfun.com/) |
| **Qwen** | Qwen3 Max | `2025-09-23` | `8.64` | `43.2` | `1.73`（读） | [bailian.console.aliyun.com](https://bailian.console.aliyun.com/) | [chat.qwen.ai](https://chat.qwen.ai/) |
| **Qwen** | Qwen3 Coder Plus | `2025-09-23` | `7.2` | `36` | `0.72` | [bailian.console.aliyun.com](https://bailian.console.aliyun.com/) | [chat.qwen.ai](https://chat.qwen.ai/) |
| **Qwen** | Qwen3-Coder-Next | `2026-02-03` | 本地部署模型，无官方API | 本地部署模型，无官方API | `-` | [bailian.console.aliyun.com](https://bailian.console.aliyun.com/) | [chat.qwen.ai](https://chat.qwen.ai/) |
| **Qwen** | Qwen3 Coder 480B | `2025-07-23` | `1.58` | `6.84` | 不支持缓存 | [bailian.console.aliyun.com](https://bailian.console.aliyun.com/) | [chat.qwen.ai](https://chat.qwen.ai/) |
| **文心（百度千帆）** | ERNIE-5.0-0110 | `2026-01-15` | `4` | `16` | 缓存价格待官方公布 | [console.bce.baidu.com/qianfan](https://console.bce.baidu.com/qianfan/overview) | [yiyan.baidu.com](https://yiyan.baidu.com/) |
| **豆包 / 火山方舟** | Doubao-Seed-Code | `2025-12-03` | `1.22`（≤32k） | `8.06` | `0.24`（读） | [console.volcengine.com/ark](https://console.volcengine.com/ark) | [doubao.com](https://www.doubao.com/) |
| **腾讯混元** | HY 2.0 Think / Instruct | `2025-12-05` | `4` | `16` | 缓存价格待官方公布 | [console.cloud.tencent.com/hunyuan](https://console.cloud.tencent.com/hunyuan) | [yuanbao.tencent.com](https://yuanbao.tencent.com/) |
| **LongCat（美团）** | LongCat-Flash-Thinking-2601 | `2026-01-16` | `1.44` | `5.76` | 缓存价格待官方公布 | [longcat.ai](https://longcat.ai/) | [longcat.ai](https://longcat.ai/) |
| **LongCat（美团）** | LongCat-Flash-Chat | `2025-09-09` | `1.44` | `5.76` | 缓存价格待官方公布 | [longcat.ai](https://longcat.ai/) | [longcat.ai](https://longcat.ai/) |
| **MiMo（小米）** | MiMo-V2-Flash | `2025-12-14` | `0.65` | `2.09` | `0.14`（读） | [huggingface.co/XiaomiMiMo](https://huggingface.co/XiaomiMiMo) | [mimo.xiaomi.com](https://mimo.xiaomi.com/) |

### 更新日志

| 日期 | 厂商 | 更新内容 |
|:---|:---|:---|
| `2026-02-05` | OpenAI | GPT-5.3-Codex 发布 |
| `2026-02-05` | Anthropic | Claude Opus 4.6 发布 |
| `2026-02-03` | Qwen | Qwen3-Coder-Next 发布 |
| `2026-02` | StepFun | Step-3.5-Flash 发布 |
| `2026-01-27` | Moonshot | Kimi K2.5 发布 |
| `2026-01-16` | LongCat | LongCat-Flash-Thinking-2601 发布 |
| `2026-01-15` | 百度 | ERNIE-5.0-0110 发布 |
| `2025-12-23` | MiniMax | MiniMax-M2.1 发布 |
| `2025-12-22` | Zhipu | GLM-4.7 发布 |
| `2025-12-17` | Google | Gemini 3 Flash 发布 |
| `2025-12-14` | MiMo | MiMo-V2-Flash 发布 |
| `2025-12-10` | OpenAI | GPT-5.2 Pro 发布 |
| `2025-12-05` | 腾讯 | HY 2.0 Think/Instruct 发布 |
| `2025-12-03` | 豆包 | Doubao-Seed-Code 发布 |
| `2025-12-01` | DeepSeek | DeepSeek-V3.2 发布 |
| `2025-11-18` | Google | Gemini 3 Pro 发布 |
| `2025-11-17` | xAI | Grok 4.1 Fast 发布 |
| `2025-10-15` | Anthropic | Claude Haiku 4.5 发布 |
| `2025-10-01` | Anthropic | Claude Sonnet 4.5 发布 |
| `2025-09-23` | Qwen | Qwen3 Max / Qwen3 Coder Plus 发布 |
| `2025-09-09` | LongCat | LongCat-Flash-Chat 发布 |
| `2025-07-31` | StepFun | Step3 发布 |
| `2025-07-23` | Qwen | Qwen3 Coder 480B 发布 |
| `2025-07-09` | xAI | Grok 4 发布 |

---

## 2. CLI 开发工具

### 2.1 国外付费使用

| Tool | Repo | Docs | 安装命令 | Stars | 免费额度/体验 | 备注 |
|:---|:---|:---|:---|:---:|:---|:---|
| **Claude Code** | [anthropics/claude-code](https://github.com/anthropics/claude-code) | [code.claude.com/docs](https://code.claude.com/docs/en/overview) | `curl -fsSL https://claude.ai/install.sh \| bash` | 64.9k | 免费账户：约 40 条消息/天（Claude Sonnet 4） | 需 Anthropic API key |
| **Codex CLI** | [openai/codex](https://github.com/openai/codex) | [developers.openai.com/codex](https://developers.openai.com/codex) | `npm i -g @openai/codex` | 59.3k | 免费 ChatGPT 包含基础 Codex 功能（受限） | 需 OpenAI 订阅或 API key |
| **GitHub Copilot CLI** | [github/copilot-cli](https://github.com/github/copilot-cli) | [GitHub docs](https://docs.github.com/copilot/concepts/agents/about-copilot-cli) | `brew install copilot-cli` 或 `npm i -g @github/copilot` | 8.1k | 免费计划：2000 条内联建议/月，50 次高级请求/月 | 需 GitHub Copilot 订阅 |
| **Cursor CLI / Agent** | [cursor/cursor](https://github.com/cursor/cursor) | [Cursor docs](https://docs.cursor.com/en/agent/cli) | 按官方文档安装 | 32.2k | Hobby 免费计划：有限的 Agent 请求和 Tab 补全 | 需 Cursor 订阅 |
| **Gemini CLI** | [google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli) | [geminicli.com/docs](https://geminicli.com/docs/) | `npm i -g @google/gemini-cli` | 93.8k | 免费：1000 次/天（Google 账户），250 次/天（API key，仅 Flash） | 需 Google API key |
| **Tabnine CLI** | [codota/TabNine](https://github.com/codota/TabNine) | [Tabnine docs](https://docs.tabnine.com/main/getting-started/tabnine-cli) | `docker pull ghcr.io/codota/tabnine-cli:latest` | 10.8k | 90 天免费试用 | 企业级，需订阅（2026-01 发布） |

### 2.2 国内/自定义 API 使用

| Tool | Repo | Docs | 安装命令 | Stars | 免费额度/体验 | 备注 |
|:---|:---|:---|:---|:---:|:---|:---|
| **Qwen Code** | [QwenLM/qwen-code](https://github.com/QwenLM/qwen-code) | [qwen docs](https://qwenlm.github.io/qwen-code-docs/en/users/overview) | `npm i -g @qwen-code/qwen-code@latest` | 18.2k | 2000 次请求/天（Qwen OAuth 账户，促销期） | 支持 Qwen API，可自定义 |
| **Kimi Code CLI** | [MoonshotAI/kimi-cli](https://github.com/MoonshotAI/kimi-cli) | [kimi docs](https://moonshotai.github.io/kimi-cli/en/) | `pip install kimi-cli` | 6.1k | 免费安装，需配置 API（Kimi K2.5 曾有一周免费） | 支持 Moonshot API，可自定义 |
| **腾讯 CodeBuddy Code** | [Tencent](https://www.codebuddy.ai/) | [CodeBuddy docs](https://www.codebuddy.ai/docs/cli/quickstart) | `npm i -g @tencent-ai/codebuddy-code` | - | 永久免费基础版：2000 次/月 | 国产，支持腾讯 API |
| **Continue CLI** | [continuedev/continue](https://github.com/continuedev/continue) | [docs.continue.dev](https://docs.continue.dev) | `npm i -g @continuedev/cli` | 31.3k | Solo 计划免费，可自带 API key 或购买 credits | 开源，支持多种 API |
| **Aider** | [Aider-AI/aider](https://github.com/Aider-AI/aider) | [aider.chat](https://aider.chat/docs/install.html) | `python -m pip install aider-install && aider-install` | 40.4k | 开源免费，需自带 API key | 开源，支持 DeepSeek 等国内 API |
| **Goose** | [block/goose](https://github.com/block/goose) | [block.github.io/goose](https://block.github.io/goose/docs/quickstart) | 见官方安装页 | 30.0k | 新用户 $10 免费 credits（通过 Tetrate） | 开源，支持自定义 API |
| **OpenCode** | [anomalyco/opencode](https://github.com/anomalyco/opencode) | [opencode.ai/docs](https://opencode.ai/docs) | `curl -fsSL https://opencode.ai/install \| bash` | 99.3k | 开源免费，需自带 API key | 开源，支持 75+ LLM 提供商 |
| **OpenHands CLI** | [OpenHands/OpenHands-CLI](https://github.com/OpenHands/OpenHands-CLI) | [OpenHands CLI docs](https://docs.openhands.dev/openhands/usage/cli/installation) | `uv tool install openhands --python 3.12` | 93 | 新用户 $10 免费 credits，本地版本免费 | 开源，支持自定义 API |
| **Cline CLI** | [cline/cline](https://github.com/cline/cline) | [Cline docs](https://docs.cline.bot/cline-cli/overview) | `npm i -g cline` | 57.6k | 个人开发者免费，新用户有限免费 credits | 开源，支持多种 API（CLI 预览版） |
| **Termineer** | - | [termineer.io](https://termineer.io/) | `npm i -g termineer` | - | 需查询官方定价 | 支持 Claude、Gemini、OpenRouter（闭源） |

> ⭐ Stars 快照时间：2026-02-07

---

## 3. IDE 开发插件

### 3.1 国外付费使用

| Tool | Repo / Marketplace | 安装方式 | Stars | 免费额度/体验 | 备注 |
|:---|:---|:---|:---:|:---|:---|
| **GitHub Copilot** | [github/copilot](https://github.com/github/copilot) / [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot) | VS Code 扩展市场安装 | - | 免费计划：2000 次内联补全/月，50 次高级请求/月 | 需 GitHub 账户 |
| **Tabnine** | [codota/TabNine](https://github.com/codota/TabNine) / [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode) | VS Code 扩展市场安装 | 10.8k | 无免费版 | $59/用户/月（企业级） |
| **Augment Code** | [augmentcode](https://github.com/augmentcode) / [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=augment.vscode-augment) | VS Code 扩展市场安装 | 693k+ | 无免费版 | $20/月起（Indie 计划） |
| **Bito** | [bito-ai/bito](https://github.com/bito-ai/bito) / [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=BitoAI.bito) | VS Code/JetBrains 插件安装 | - | 14 天免费试用 | $12/月起（Team 计划） |
| **Amazon CodeWhisperer** | [aws/amazon-codewhisperer](https://github.com/aws/amazon-codewhisperer) / [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=AmazonWebServices.aws-toolkits) | VS Code/JetBrains 插件安装 | - | 免费个人版：50 次安全扫描/月 | 需 AWS Builder ID |
| **JetBrains AI Assistant** | [JetBrains](https://www.jetbrains.com/ai-assistant/) / [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=jetbrains.jetbrains-ai-assistant) | VS Code/JetBrains 插件安装 | - | AI Free：3 个 AI 点数/30 天 | 支持本地模型 |

### 3.2 国内/自定义 API 使用

| Tool | Repo / Marketplace | 安装方式 | Stars | 免费额度/体验 | 备注 |
|:---|:---|:---|:---:|:---|:---|
| **Cline** | [cline/cline](https://github.com/cline/cline) / [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=saoudrizwan.claude-dev) | VS Code 扩展市场安装 | 57.7k | 个人开发者免费，Teams Q1 2026 前免费 | 开源，可自带 API key |
| **Roo Code** | [RooCodeInc/Roo-Code](https://github.com/RooCodeInc/Roo-Code) / [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=RooVeterinaryInc.roo-cline) | VS Code 扩展市场安装 | 22.1k | 完全免费（本地使用），Cloud 免费版 | 开源，可自带 API key |
| **Continue** | [continuedev/continue](https://github.com/continuedev/continue) / [Continue Marketplace](https://marketplace.visualstudio.com/items?itemName=Continue.continue) | VS Code/JetBrains 插件安装 | 31.3k | Solo 计划免费 | 开源，可自带 API key |
| **Codeium (Windsurf)** | [codeium](https://codeium.com/) / [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=Codeium.codeium) | VS Code/JetBrains 插件安装 | - | 免费：25 credits/月 | 支持 70+ IDE |
| **通义灵码** | [阿里云](https://tongyi.aliyun.com/lingma/) / [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=Aliyun.tongyi-lingma) | VS Code/JetBrains 插件安装 | - | 公测阶段完全免费 | 国产，基于通义千问 |
| **百度 Comate** | [百度智能云](https://comate.baidu.com/) / [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=baidu-intl.comate) | VS Code/JetBrains 插件安装 | - | 个人标准版完全免费 | 国产，基于文心大模型 |
| **GitHub CLI Copilot Extension** | [github/gh-copilot](https://github.com/github/gh-copilot) | `gh extension install github/gh-copilot` | 1.1k | 需 GitHub Copilot 订阅 | GitHub CLI 扩展 |

---

## 4. 原生 AI IDE

### 4.1 国际

| Tool | Repo / Site | 类型 | Stars | 免费额度/体验 | 备注 |
|:---|:---|:---|:---:|:---|:---|
| **Cursor** | [cursor/cursor](https://github.com/cursor/cursor) / [cursor.com](https://cursor.com/) | AI 原生 IDE | 32.2k | Hobby 免费：约 2000 次补全/月，50 次高级请求/月 | VS Code fork，支持自定义 API key |
| **Windsurf** | [codeium](https://codeium.com/) / [windsurf.com](https://windsurf.com/) | AI 原生 IDE | - | 免费：25 credits/月，无限 Cascade、Tab 补全 | Codeium 演进版，$15/月起（Pro） |
| **Google Antigravity** | [antigravity.google](https://antigravity.google/) | AI 原生 IDE | - | 免费预览版：无限 Tab 补全和 Command | 2025-11 发布，支持 5 个并行 Agent |
| **v0.dev** | [vercel/v0](https://github.com/vercel/v0) / [v0.dev](https://v0.dev/) | AI Web 应用构建 | - | 免费：$5 credits/月，7 条消息/天 | Vercel 出品，专注于 UI 生成 |
| **Replit** | [replit](https://replit.com/) | AI 云端 IDE | - | Starter 免费：每日 AI credits，1 个发布应用 | 云端开发环境 |
| **AWS Kiro** | [kiro.dev](https://kiro.dev/) | AI 原生 IDE | - | 免费：50 credits/月，新用户 500 credits（30 天） | AWS 出品，$20/月起（Pro） |
| **Zed** | [zed-industries/zed](https://github.com/zed-industries/zed) / [zed.dev](https://zed.dev/) | 高性能编辑器 | - | 免费：2000 次编辑预测/月，可自带 API key | 高性能 Rust 编辑器，$10/月起（Pro） |
| **GitHub Copilot Workspace** | [githubnext/copilot-workspace-user-manual](https://github.com/githubnext/copilot-workspace-user-manual) / [github.com/features/copilot](https://github.com/features/copilot) | AI 原生 IDE | - | 技术预览已结束（2025-05-30） | 已停止服务 |

### 4.2 国内

| Tool | Repo / Site | 类型 | Stars | 免费额度/体验 | 备注 |
|:---|:---|:---|:---:|:---|:---|
| **Trae（国内版）** | [trae.com.cn](https://www.trae.com.cn/) / [trae.cn](https://www.trae.cn/) | AI 原生 IDE | - | 完全免费 | 字节跳动出品，集成 Doubao-1.5-pro、DeepSeek R1/V3（2025-03 发布） |
| **Trae（国际版）** | [traeide.com](https://traeide.com/) / [trae.ai](https://www.trae.ai/) | AI 原生 IDE | - | 完全免费 | 字节跳动出品，支持 Claude 3.5-Sonnet、Claude 3.7-Sonnet、GPT-4o、DeepSeek R1/V3（截至 2026-02，尚未支持 Claude 4.6/GPT-5） |
| **通义灵码 IDE (Lingma IDE)** | [tongyi.aliyun.com/lingma](https://tongyi.aliyun.com/lingma/) | AI 原生 IDE | - | 个人基础版永久免费，专业版限免中 | 阿里云出品，支持 VS Code 插件 |
| **Cherry Studio** | [CherryHQ/cherry-studio](https://github.com/CherryHQ/cherry-studio) | 桌面多模型客户端 | 39.4k | 开源免费，支持免费模型 | 多模型 AI 客户端 |
| **CodeGeeX** | [THUDM/CodeGeeX](https://github.com/THUDM/CodeGeeX) | AI 代码助手 | 8.7k | 个人用户完全免费 | 智谱 AI 出品，支持 15+ 语言 |

---

## 5. CLI Coding Plan

| 方案 | 官方入口 | 价格/计费 | 备注 |
|:---|:---|:---|:---|
| **Claude Code（Anthropic 官方）** | [Anthropic Pricing](https://www.anthropic.com/pricing#api) / [Claude Code costs](https://docs.anthropic.com/en/docs/claude-code/costs) | 按 API token 消耗计费：平均 `¥43/开发者/天` 或 `¥720-1440/开发者/月`（Sonnet 4.5）。订阅计划：Pro `¥144/月`（年付`¥1440`），Max 基础版 `¥720/月`，Max 高级版 `¥1440/月` | 模型代际已到 Claude 4.6，无固定月费 Coding Plan |
| **OpenAI Codex（CLI/Cloud）** | [Codex Pricing](https://developers.openai.com/codex/pricing/) | Plus `¥144/月`（`$20/月`），Pro `¥1440/月`（`$200/月`），Business `¥216/用户/月`（`$30/用户/月`），或 API key token 计费 | 2026-02-07 核验，包含在 ChatGPT 订阅计划中 |
| **GLM Coding Plan** | [z.ai/coding-plan](https://www.z.ai/coding-plan) | Lite `¥20/月`（120 prompts/5h），Pro `¥30/月`（600 prompts/5h），Max `¥60/月`（2400 prompts/5h） | 智谱 AI 出品，支持 GLM-4.6，兼容 Claude Code/Cline 等工具 |
| **阿里云百炼 Coding Plan** | [阿里云 Coding Plan](https://www.aliyun.com/benefit/scene/codingplan) | Lite `¥10/月`（首月）`¥40/月`（续费，18k 次/月），Pro `¥50/月`（首月）`¥200/月`（续费，90k 次/月） | 支持 Qwen3-Coder-Plus，兼容 Claude Code/Qwen Code/Cline 等工具 |
| **MiniMax Claude Code 方案** | [MiniMax 文档](https://www.minimax.io/platform/document/claude-code) | Starter `¥10/月`（100 prompts/5h），Plus `¥20/月`（300 prompts/5h），Max `¥50/月`（1000 prompts/5h） | 覆盖 Claude Code 兼容接入说明，年付有折扣 |
| **火山引擎 ModelArk Coding 方案** | [modelark 产品页](https://www.volcengine.com/product/modelark) / [方舟 Coding Plan](https://www.volcengine.com/activity/codingplan) | Lite `¥9.9/月`（首购，首月可低至`¥8.9`，1200 次/5h），Pro `¥49.9/月`（首购，6000 次/5h） | 支持 Doubao-Seed-Code、GLM-4.7、DeepSeek-V3.2、Kimi-K2-Thinking，兼容 Claude Code/Cursor/Cline 等工具 |

---

## License

MIT License
