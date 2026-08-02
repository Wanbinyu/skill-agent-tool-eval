# Agent Tool Eval

[English](README.md) | **中文**

<p align="center"><strong>一个 skill · 30 秒安装 · 用于 Claude / Codex / Cursor</strong></p>
<p align="center"><code>agent-tool-eval</code> · MIT · Agent Skills 格式</p>

---

## 先从这里开始

### 安装

```powershell
git clone https://github.com/Wanbinyu/skill-agent-tool-eval.git
cd skill-agent-tool-eval
.\scripts\install.ps1 -Claude
```

```bash
git clone https://github.com/Wanbinyu/skill-agent-tool-eval.git
cd skill-agent-tool-eval
chmod +x scripts/install.sh && ./scripts/install.sh --claude
```

→ `~/.claude/skills/agent-tool-eval/` · **请重启 Claude Code**

### 然后可以直接说

- 「用 `agent-tool-eval` skill 处理我当前的改动」
- 或匹配 `SKILL.md` 顶部 `description` 里的中英文触发词

---

## 这个 skill 解决什么

Define a minimal evaluation set for agent tool use. Use when measuring if tools or prompts improved, regression after schema changes, or Chinese "tool 评测", "agent 回归", "工具调用评估". Lightweight task packs - not a full ML platform.

完整流程（步骤、完成标准、报告模板）见：**[`SKILL.md`](SKILL.md)**

> 给人看的文档：本页中文 + [English](README.md)。  
> `SKILL.md` 正文以英文为主，方便 agent 稳定执行。

---

## 一个 skill = 一个项目

- 本仓库：**仅** `agent-tool-eval`
- 整包装：[ai-surface-skills](https://github.com/Wanbinyu/ai-surface-skills)
- 全部独立 skill：https://github.com/Wanbinyu?tab=repositories&q=skill-

### 插件

```text
/plugin marketplace add Wanbinyu/skill-agent-tool-eval
/plugin install agent-tool-eval@agent-tool-eval
```

## 许可证

MIT · [Wanbinyu](https://github.com/Wanbinyu)
