# Agent Token Optimization Workflow

A documentation-first workflow for reducing token consumption in agent-driven development without degrading session quality, skill recall, or task success rate.

适用范围：`Codex`、`Claude Code` 及其他通用 Agent CLI。

## What This Repository Provides

This repository contains a reusable workflow for teams that want to:

- reduce fixed context cost
- reduce repeated context loading
- keep critical skill recall stable
- keep simple tasks fast
- support dynamic skill discovery as projects evolve

## Repository Structure

```text
.
├─ README.md
├─ LICENSE
├─ CHANGELOG.md
├─ TEAM_GUIDE.md
├─ STANDARD_OPERATING_PROCEDURE.md
├─ docs/
│  ├─ token-optimization-summary.md
│  ├─ token-optimization-report.md
│  └─ token-optimization-checklist.md
├─ templates/
│  └─ prompt-templates.md
└─ external-share/
   ├─ README.md
   ├─ 01-summary.md
   ├─ 02-team-guide.md
   ├─ 03-sop.md
   ├─ 04-checklist.md
   ├─ 05-prompt-templates.md
   └─ appendix-full-report.md
```

## Recommended Reading Order

1. `docs/token-optimization-summary.md`
2. `TEAM_GUIDE.md`
3. `STANDARD_OPERATING_PROCEDURE.md`
4. `docs/token-optimization-report.md`
5. `docs/token-optimization-checklist.md`
6. `templates/prompt-templates.md`

## Core Ideas

- Optimize fixed context cost before cutting capabilities.
- Keep skill installation broad, but default exposure narrow.
- Keep indexes resident, but load detailed content on demand.
- Replace long raw history with structured summaries.
- Support dynamic skill recall when new domains or task types appear.

## Suggested Usage

### For existing projects

Use this repository to audit current token costs, identify waste sources, and introduce a lower-cost context structure without breaking existing workflows.

### For new projects

Use this repository to design a low-token context model from the start, including minimal project context, skill tiers, summary templates, and dynamic skill recall.

## License

This repository is prepared with an MIT license by default. Change it if your distribution policy requires a different license.
