# Fabio Live Swarm Charter

## Purpose

The Fabio copilot scales through specialized live-session agents.

The goal is not more noise. The goal is less cognitive load, cleaner alerts, and stronger risk discipline.

## Roles

| Agent | Owns | Main Job | Cannot Do |
| --- | --- | --- | --- |
| Orchestrator | `profiles/`, `docs/architecture/`, `docs/playbooks/` | Routes work and enforces no-execution rules. | Approve or execute trades. |
| Scout | `skills/fabio-premarket-sentiment/`, `resources/news/`, `resources/market-notes/` | Compresses news, sentiment, and important numbers. | Tell trader to enter. |
| Setup Copilot | `skills/fabio-aaa-setup-copilot/`, `skills/fabio-live-alert-watchlist/` | Watches levels and setup criteria. | Give blind buy/sell calls. |
| Risk Sentinel | `SCORECARD.md`, `skills/fabio-post-trade-journal/`, `docs/memory/` | Enforces risk/no-trade conditions and creates memory candidates. | Override human risk rules. |

## Alert Escalation

```text
Scout catalyst -> Setup Copilot watchlist update
Setup forming -> Risk Sentinel no-trade check
Risk Sentinel pass -> trader-facing alert
Risk Sentinel fail -> avoid/stand-down alert
Trade complete -> post-trade journal
Journal reviewed -> memory/skill update candidate
```

## Live Context Rule

Never load the whole repo during a live session.

Use:

```text
SYSTEM.md
ubiquitous_language.md
specific skill README/SKILL.md
today's pre-market plan
today's key levels
```

Avoid:

```text
raw news dumps
full archives
old screenshots
implementation folders
large logs
```
