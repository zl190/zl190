# AI Engineer → Agent Reliability

Building infrastructure that makes AI agents trustworthy — enforcement hooks, quality gates, empirical ablation studies. Tested across 60,000+ agent interactions.

High-stakes ML background (FDA 510(k)).

Contributor to [last30days](https://github.com/mvanhorn/last30days-skill) ![GitHub stars](https://img.shields.io/github/stars/mvanhorn/last30days-skill?style=flat&label=stars).

## What I Build

| Project | What it does | Evidence |
|---------|-------------|----------|
| [claude-code-harness](https://github.com/zl190/claude-code-harness) | Hook framework that enforces agent behavior at lifecycle points | 60K+ hook-fires, [ablation study](https://zl190.github.io/blog/do-hooks-actually-change-model-behavior) (83% divergence) |
| [noglaze](https://github.com/zl190/noglaze) | Output quality audit — blocks agents from shipping unverified claims | 25/25 tests |
| [agent-cockpit](https://github.com/zl190/agent-cockpit) | Real-time agent behavior monitoring dashboard | 142/142 tests |
| [pipeline-ops](https://github.com/zl190/pipeline-ops) | Operator pattern for AI pipelines — 177 lines, zero deps | 43/43 tests |

## Research

| Project | What it is |
|---------|-----------|
| [nano-agent-anatomy](https://github.com/zl190/nano-agent-anatomy) | Reverse-engineering production agent architecture — 4 layers, 95 tests |
| [sts-audit](https://github.com/zl190/sts-audit) | Empirical study: can architectural specs make AI code quality auditable? |

## Writing

[Blog](https://blog.ylab3.com) — what I learn from building AI agents and trying to make them reliable.
