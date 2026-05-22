# b2b-pmm-claude

Personal Claude Code configuration for B2B product marketing work. Contains skills, slash commands, and prompts that encode my PMM methodology — built to produce consistent, expert-level output without starting from scratch each time.

## What's in here

```
claude/
├── CLAUDE.md          # Global preferences and context for Claude Code
├── skills/            # Domain expertise files (loaded when relevant)
├── commands/          # Slash commands for repeatable workflows
└── prompts/           # Standalone prompts for one-off tasks
```

## Skills

| Skill | What it does |
|---|---|
| `positioning-framework` | April Dunford's positioning methodology for B2B products |
| `battlecard-generator` | Competitive battlecards using consultative selling approach |
| `launch-brief` | Internal launch briefs for cross-functional alignment |
| `stakeholder-brief` | One-page briefs for new initiatives or assets |
| `customer-onepager` | Customer-facing one-pagers by audience or capability |
| `usecase-playbook` | GTM playbooks for specific use cases or segments |
| `pmm-newsletter` | Weekly PMM team update newsletters |

## Installation

```bash
git clone https://github.com/utkarshsinha24/b2b-pmm-claude.git
cp -r b2b-pmm-claude/claude/* ~/.claude/
```

Restart Claude Code. Skills and commands will be available globally.

## Updating

When you refine a skill or add a command:

```bash
cd ~/b2b-pmm-claude
git add .
git commit -m "update battlecard skill"
git push
cp -r claude/* ~/.claude/
```

## Philosophy

These skills encode methodology, not just instructions. The goal is for Claude to understand *how to think* about a PMM problem — not just follow a template. Each skill reflects real B2B SaaS experiences, particularly for technical B2B platforms (think API/SDK-based platforms) in AI development, ad tech, and research industries.
