# Agent Tool Eval

**English** | [中文](README.zh-CN.md)

<p align="center"><strong>One skill. Install in 30 seconds. Use in Claude / Codex / Cursor.</strong></p>
<p align="center"><code>agent-tool-eval</code> · MIT · Agent Skills format</p>

---

## Start here

### Install

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

→ `~/.claude/skills/agent-tool-eval/` · **Restart Claude Code**

### Then say (examples)

- *Use the `agent-tool-eval` skill on my current change.*
- Or any phrase matching the triggers in `SKILL.md` frontmatter (EN + ZH).

---

## What this skill is for

Define a minimal evaluation set for agent tool use. Use when measuring if tools or prompts improved, regression after schema changes, or Chinese "tool 评测", "agent 回归", "工具调用评估". Lightweight task packs - not a full ML platform.

Full workflow (steps, exit criteria, report template): **[`SKILL.md`](SKILL.md)**

> Human docs: EN + [中文](README.zh-CN.md).  
> `SKILL.md` body is English so agents execute consistently.

---

## One skill = one project

- This repo: **only** `agent-tool-eval`
- Bulk packs: [ai-surface-skills](https://github.com/Wanbinyu/ai-surface-skills)
- All solo skills: https://github.com/Wanbinyu?tab=repositories&q=skill-

### Plugin

```text
/plugin marketplace add Wanbinyu/skill-agent-tool-eval
/plugin install agent-tool-eval@agent-tool-eval
```

## License

MIT · [Wanbinyu](https://github.com/Wanbinyu)
