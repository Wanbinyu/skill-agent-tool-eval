# Agent Tool Eval

**English** | [中文](README.zh-CN.md)

<p align="center">
  <strong>Standalone Agent Skill</strong> · <code>agent-tool-eval</code>
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="MIT" /></a>
  <a href="https://github.com/agentskills/agentskills"><img src="https://img.shields.io/badge/format-Agent%20Skills-111827" alt="Agent Skills" /></a>
</p>

Define a minimal evaluation set for agent tool use. Use when measuring if tools or prompts improved, regression after schema changes, or Chinese "tool 评测", "agent 回归", "工具调用评估". Lightweight task packs - not a full ML platform.

---

## Install (Claude Code)

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

Claude skill id remains **`agent-tool-eval`** (no `skill-` prefix):

`~/.claude/skills/agent-tool-eval/`

Restart Claude Code after install.

### Plugin

```text
/plugin marketplace add Wanbinyu/skill-agent-tool-eval
/plugin install agent-tool-eval@agent-tool-eval
/reload-plugins
```

---

## What this skill does

See [`SKILL.md`](SKILL.md) (same as `skills/agent-tool-eval/SKILL.md`).

The YAML `description` at the top of `SKILL.md` holds triggers (often EN + ZH).

> **Note:** `SKILL.md` body is English so agents follow instructions reliably.  
> Human docs are bilingual: this file + [`README.zh-CN.md`](README.zh-CN.md).

---

## One skill = one project

This repo ships **only this skill**.  
Bulk install of related skills:

- Collection: [ai-surface-skills](https://github.com/Wanbinyu/ai-surface-skills)
- Catalog: [`CATALOG.md`](../CATALOG.md) / [`CATALOG.zh-CN.md`](../CATALOG.zh-CN.md) (local `G:\\skill\\solo`)

---

## Layout

```text
skill-agent-tool-eval/   (GitHub)  or  solo/agent-tool-eval/  (local)
  README.md              # English
  README.zh-CN.md        # Chinese
  SKILL.md
  skills/agent-tool-eval/SKILL.md
  scripts/install.ps1
  .claude-plugin/
```

## License

MIT · [Wanbinyu](https://github.com/Wanbinyu)
