# Vivaminima · small tools for Claude Code

**AI coding session heavy before you type a word?** Our AI windows re-read **6.5 million tokens** of instructions in 19 days, at every new session and after every compaction. **4.3 million** of it came before the first question (estimate, our own 12 projects, Oct 29 – Nov 16). In one project a single `@import` line loaded 46,816 tokens per session; we halved it and kept all 40 rules.

Measure yours free with [context-file-audit](https://github.com/vivaminima/context-file-audit). All 16 Pro tools in one download: **[Vivaminima Pro - Everything](https://vivastory4.gumroad.com/l/pro-everything)** ($49; $344 one by one).

We run a small company where each department is a Claude Code window. These are the tools we wrote after our own windows broke something: a key left in a ZIP, a skill that never loaded, a note that went missing between windows.

- **Small.** Most are one Python file, standard library only. Nothing to install.
- **Local.** They read your folders and write a report. Only the budget router talks to the network, to the LLM provider you call.
- **Free and MIT** in these repositories. Most have a **Pro edition ($19, one-time)** with more checks and reports, on our store: https://vivastory4.gumroad.com

### Install inside Claude Code

One line per tool, no download:

```
/plugin install release-gate --marketplace vivaminima/vivaminima
```

Swap `release-gate` for any tool below. Twelve of the fifteen install this way. The starter kit is a folder you copy; directive-ledger and folder-undo are one Python file you download. On older Claude Code, run `/plugin marketplace add vivaminima/vivaminima` first, then `/plugin` to pick a tool.
## Before you ship or share a folder

<table>
<tr><td width="50%" valign="top"><a href="https://github.com/vivaminima/release-gate"><img src="img/release-gate.png" alt="release-gate"></a><br><b><a href="https://github.com/vivaminima/release-gate">release-gate</a></b> · free<br>A pre-release check for the ZIP or folder you are about to ship: keys, stray files, machine paths, version mismatches.<br><sub>Pro: <a href="https://vivastory4.gumroad.com/l/release-gate-pro">Release Gate Pro</a> ($19)</sub></td><td width="50%" valign="top"><a href="https://github.com/vivaminima/secret-map"><img src="img/secret-map.png" alt="secret-map"></a><br><b><a href="https://github.com/vivaminima/secret-map">secret-map</a></b> · free<br>See where API keys and passwords sit in a folder before you share it. Shows locations, never values.<br><sub>Pro: <a href="https://vivastory4.gumroad.com/l/secret-map-pro">Secret Map Pro</a> ($19)</sub></td></tr>
<tr><td width="50%" valign="top"><a href="https://github.com/vivaminima/console-safe"><img src="img/console-safe.png" alt="console-safe"></a><br><b><a href="https://github.com/vivaminima/console-safe">console-safe</a></b> · free<br>Run a Python command-line tool under several console encodings and see where it dies.<br><sub>Pro: <a href="https://vivastory4.gumroad.com/l/console-safe-pro">Console Safe Pro</a> ($19)</sub></td></tr>
</table>

## Claude Code skills

<table>
<tr><td width="50%" valign="top"><a href="https://github.com/vivaminima/skill-audit-kit"><img src="img/skill-audit-kit.png" alt="skill-audit-kit"></a><br><b><a href="https://github.com/vivaminima/skill-audit-kit">skill-audit-kit</a></b> · free<br>Find out why a Claude skill does not load, does not trigger, or eats your context. Read-only.<br><sub>Pro: <a href="https://vivastory4.gumroad.com/l/skill-audit-pro">Skill Audit Pro</a> ($19)</sub></td><td width="50%" valign="top"><a href="https://github.com/vivaminima/skill-install-gate"><img src="img/skill-install-gate.png" alt="skill-install-gate"></a><br><b><a href="https://github.com/vivaminima/skill-install-gate">skill-install-gate</a></b> · free<br>Look at a Claude Code skill before you install it: a check of a temporary copy with one of three verdicts.<br><sub>Pro: <a href="https://vivastory4.gumroad.com/l/skill-install-gate-pro">Skill Install Gate Pro</a> ($19)</sub></td></tr>
<tr><td width="50%" valign="top"><b><a href="https://github.com/vivaminima/beginner-readme-section">beginner-readme-section</a></b> · free<br>A Claude Code skill that writes a "New to this? Start here" section at the top of a README.<br><sub>Free only</sub></td></tr>
</table>

## Running several Claude windows

<table>
<tr><td width="50%" valign="top"><a href="https://github.com/vivaminima/inbox-ledger"><img src="img/inbox-ledger.png" alt="inbox-ledger"></a><br><b><a href="https://github.com/vivaminima/inbox-ledger">inbox-ledger</a></b> · free<br>A receipt book for the folder your Claude windows use to pass notes: nothing counted twice, nothing lost.<br><sub>Pro: <a href="https://vivastory4.gumroad.com/l/inbox-ledger-pro">Inbox Ledger Pro</a> ($19)</sub></td><td width="50%" valign="top"><a href="https://github.com/vivaminima/handoff-check"><img src="img/handoff-check.png" alt="handoff-check"></a><br><b><a href="https://github.com/vivaminima/handoff-check">handoff-check</a></b> · free<br>Checks an agent's "done, I sent it" report against the disk and writes a verification receipt.<br><sub>Pro: <a href="https://vivastory4.gumroad.com/l/handoff-check-pro">Handoff Check Pro</a> ($19)</sub></td></tr>
<tr><td width="50%" valign="top"><a href="https://github.com/vivaminima/checklist-stop"><img src="img/checklist-stop.png" alt="checklist-stop"></a><br><b><a href="https://github.com/vivaminima/checklist-stop">checklist-stop</a></b> · free<br>A Stop hook for Claude Code: the session cannot finish while your Markdown checklist still has an open item.<br><sub>Pro: <a href="https://vivastory4.gumroad.com/l/checklist-stop-pro">Checklist Stop Pro</a> ($19)</sub></td><td width="50%" valign="top"><a href="https://github.com/vivaminima/ai-company-starter-kit"><img src="img/ai-company-starter-kit.png" alt="ai-company-starter-kit"></a><br><b><a href="https://github.com/vivaminima/ai-company-starter-kit">ai-company-starter-kit</a></b> · free<br>A sample company made of folders: each folder is a department, each Claude window works as one.<br><sub>Pro: <a href="https://vivastory4.gumroad.com/l/ai-company-starter-kit">AI Company Starter Kit (full edition)</a> ($19)</sub></td></tr>
<tr><td width="50%" valign="top"><a href="https://github.com/vivaminima/directive-ledger"><img src="img/run/directive-ledger.png" alt="directive-ledger"></a><br><b><a href="https://github.com/vivaminima/directive-ledger">directive-ledger</a></b> · free · new<br>An append-only log of what the owner decided. New sessions read one line instead of the whole chat, and any edit to the past is caught.<br><sub>Full system: <a href="https://vivastory4.gumroad.com/l/backlog-os">Backlog OS</a> ($39): cards, index, morning brief, session hooks</sub></td><td width="50%" valign="top"><a href="https://github.com/vivaminima/folder-undo"><img src="img/folder-undo.png" alt="folder-undo"></a><br><b><a href="https://github.com/vivaminima/folder-undo">folder-undo</a></b> · free · new<br>Claude Code deleted files and they're not in the Recycle Bin? Keeps a copy right before a command deletes, moves or overwrites them: the part rewind doesn't cover.<br><sub>Pro: <a href="https://vivastory4.gumroad.com/l/folder-undo-pro">Folder Undo Pro</a> ($19): last 10 sessions, history per file, a report</sub></td></tr>
</table>

## Context, cost and decisions

<table>
<tr><td width="50%" valign="top"><a href="https://github.com/vivaminima/context-file-audit"><img src="img/context-file-audit.png" alt="context-file-audit"></a><br><b><a href="https://github.com/vivaminima/context-file-audit">context-file-audit</a></b> · free<br>Measure what your CLAUDE.md and its @imports cost at session start.<br><sub>Pro: <a href="https://vivastory4.gumroad.com/l/token-audit-kit">Token Audit Kit</a> ($19) · <a href="https://vivastory4.gumroad.com/l/context-split-planner">Context Split Planner</a> ($19) · both in the <a href="https://vivastory4.gumroad.com/l/context-bundle">Context Bundle</a> ($39)</sub></td><td width="50%" valign="top"><a href="https://github.com/vivaminima/llm-budget-router-lite"><img src="img/llm-budget-router-lite.png" alt="llm-budget-router-lite"></a><br><b><a href="https://github.com/vivaminima/llm-budget-router-lite">llm-budget-router-lite</a></b> · free<br>Route LLM requests and see what each call costs. One local Python file, standard library only.<br><sub>Pro: <a href="https://vivastory4.gumroad.com/l/llm-budget-router-pro">LLM Budget Router Pro</a> ($19)</sub></td></tr>
<tr><td width="50%" valign="top"><a href="https://github.com/vivaminima/go-no-go-verdict-skill"><img src="img/go-no-go-verdict-skill.png" alt="go-no-go-verdict-skill"></a><br><b><a href="https://github.com/vivaminima/go-no-go-verdict-skill">go-no-go-verdict-skill</a></b> · free<br>Turn one idea into a decision with explicit assumptions and stop conditions. A Claude Code skill and a small checker.<br><sub>Pro: <a href="https://vivastory4.gumroad.com/l/go-no-go-verdict-pro">Go/No-Go Verdict Pro</a> ($19)</sub></td></tr>
</table>

---

Questions or a broken check? Open an issue in the tool's repository.
