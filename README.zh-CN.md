# Agent Tool Eval

[English](README.md) | **中文**

<p align="center">
  <strong>独立 Agent Skill 项目</strong> · <code>agent-tool-eval</code>
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="MIT" /></a>
  <a href="https://github.com/agentskills/agentskills"><img src="https://img.shields.io/badge/format-Agent%20Skills-111827" alt="Agent Skills" /></a>
</p>

Define a minimal evaluation set for agent tool use. Use when measuring if tools or prompts improved, regression after schema changes, or Chinese "tool 评测", "agent 回归", "工具调用评估". Lightweight task packs - not a full ML platform.

---

## 安装（Claude Code）

```powershell
git clone https://github.com/Wanbinyu/skill-agent-tool-eval.git
cd skill-agent-tool-eval
.\scripts\install.ps1 -Claude
```

```bash
git clone https://github.com/Wanbinyu/skill-agent-tool-eval.git
cd skill-agent-tool-eval
chmod +x scripts/install.sh
./scripts/install.sh --claude
```

安装到 Claude 时目录名是 **`agent-tool-eval`**（不加 `skill-` 前缀）：

`~/.claude/skills/agent-tool-eval/`

装完后请重启 Claude Code。

### 插件方式

```text
/plugin marketplace add Wanbinyu/skill-agent-tool-eval
/plugin install agent-tool-eval@agent-tool-eval
/reload-plugins
```

---

## 这个 skill 做什么

正文说明见 [`SKILL.md`](SKILL.md)（与 `skills/agent-tool-eval/SKILL.md` 相同）。

触发词在 `SKILL.md` 顶部 YAML 的 `description` 里（常含中英文）。

> **说明：** `SKILL.md` 正文以**英文**为主，方便 agent 稳定执行。  
> 给人看的文档提供双语：[`README.md`](README.md)（英文）+ 本文件（中文）。

---

## 一个 skill = 一个项目

本仓库**只包含这一个 skill**。  
若要一次安装整包相关技能：

- 合集：[ai-surface-skills](https://github.com/Wanbinyu/ai-surface-skills)
- 目录：[`CATALOG.zh-CN.md`](../CATALOG.zh-CN.md) / [`CATALOG.md`](../CATALOG.md)

---

## 目录结构

```text
skill-agent-tool-eval/   （GitHub）或  solo/agent-tool-eval/  （本地）
  README.md              # 英文
  README.zh-CN.md        # 中文
  SKILL.md
  skills/agent-tool-eval/SKILL.md
  scripts/install.ps1
  .claude-plugin/
```

## 许可证

MIT · [Wanbinyu](https://github.com/Wanbinyu)
