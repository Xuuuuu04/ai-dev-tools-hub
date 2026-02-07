# Install And Troubleshooting

## Prerequisites
- Node.js >= 20
- Git + GitHub CLI (`gh`)
- 可用网络与对应账号权限

## Quick Install

### Codex CLI
```bash
npm install -g @openai/codex
codex
```

### Claude Code
```bash
curl -fsSL https://claude.ai/install.sh | bash
claude
```

### Gemini CLI
```bash
npm install -g @google/gemini-cli
gemini
```

### Qwen Code
```bash
npm install -g @qwen-code/qwen-code@latest
qwen
```

### Copilot CLI
```bash
brew install copilot-cli
copilot
```

## Common Issues
- Command not found: 检查全局 npm bin 路径是否在 `PATH`。
- Login failed: 浏览器完成授权后重试。
- Rate limited: 切换账号或等待配额窗口。
- Too many approval prompts: 降低审批模式但保留关键操作确认。

## Naming Disambiguation
- `github/copilot-cli` 是主程序。
- `github/gh-copilot` 是 `gh` 扩展。
- Cursor/CodeBuddy 同名社区项目多，优先官方文档。
