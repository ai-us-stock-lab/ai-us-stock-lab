# AI美股实验室 | AI US Stock Lab

I build local AI tools for difficult decisions, software work, and verifiable public-company research.

我在做一组本地优先的 AI 工具：让多个 CLI agent 一起讨论、质疑和审查决策，也把重复的美股研究流程沉淀成可复用的 Codex skills。

## Roundtable

[Roundtable](https://github.com/ai-us-stock-lab/roundtable) brings Codex, Claude Code, Gemini CLI, and other AI CLIs into one local workbench.

Use the Workbench for multi-CLI conversations and isolated code changes. When a decision needs more scrutiny, move it into a structured committee: agents give independent first takes, challenge one another, classify disagreements, and produce an evidence-linked verdict.

- Runs locally on `127.0.0.1`
- Uses the AI CLI subscriptions you already have
- Keeps each CLI's skills, memory, and global instructions
- Has no third-party runtime dependencies
- Supports English and Chinese

[Watch the 67-second walkthrough](https://github.com/ai-us-stock-lab/roundtable/blob/master/docs/demo-en.mp4) · [Get v0.3.1](https://github.com/ai-us-stock-lab/roundtable/releases/tag/v0.3.1) · [Share a real test](https://github.com/ai-us-stock-lab/roundtable/issues/1)

## Research skills

- [Nantian Decision Framework](https://github.com/ai-us-stock-lab/nantian-decision-framework): demand-first decision support, company research, business planning, and report delivery.
- [Disclosure Backtest](https://github.com/ai-us-stock-lab/disclosure-backtest-skill): compare a company's historical forward-looking statements with later official disclosures.

## Working principles

- Start from the user's real decision and current substitute.
- Prefer public, verifiable evidence.
- Separate facts, assumptions, inferences, and counterevidence.
- Keep tools local, inspectable, and reversible when possible.

> Research tooling only. Nothing here is investment advice.
