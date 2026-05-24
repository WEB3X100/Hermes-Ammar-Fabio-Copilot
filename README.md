# Hermes Ammar Fabio Copilot

## Purpose

This repo is the operating home for Ammar's Fabio-style trading copilot.

The goal is to build a human-executed trading assistant that helps Ammar prepare, focus, alert, journal, and improve every week.

This is not an auto-trading bot.

The trader executes. Hermes assists.

## North Star

Build a copilot that helps Ammar become sharper at:

- pre-market preparation,
- market sentiment reading,
- important numbers and levels,
- AAA setup recognition,
- live-session alert discipline,
- risk control,
- post-trade journaling,
- weekly reflection,
- recursive improvement.

## Core Rule

Hermes can observe, analyze, remind, summarize, and journal.

Hermes cannot:

- place trades,
- click trade buttons,
- connect to broker execution APIs,
- modify orders,
- move money,
- override risk rules,
- give blind buy/sell calls.

## Fabio Mode Architecture

Fabio mode is not one sequential agent.

It is a live swarm with strict roles:

| Agent | Role | Owns |
| --- | --- | --- |
| Orchestrator | Routes work, enforces no-execution rules, protects context. | `profiles/`, `docs/architecture/`, `docs/playbooks/` |
| Scout | Compresses pre-market sentiment, catalysts, and important numbers. | `skills/fabio-premarket-sentiment/`, `resources/news/`, `resources/market-notes/` |
| Setup Copilot | Watches key levels and AAA setup criteria. | `skills/fabio-aaa-setup-copilot/`, `skills/fabio-live-alert-watchlist/` |
| Risk Sentinel | Blocks bad alerts, enforces no-trade conditions, turns journals into memory. | `SCORECARD.md`, `skills/fabio-post-trade-journal/`, `docs/memory/` |

Before any pre-market, live, or journal output, Hermes must use:

```text
profiles/fabio-trading-copilot/ubiquitous_language.md
```

This file defines AAA Setup, Key Level, Important Number, Trigger, Confirmation, Invalidation, No-Trade Condition, Alert, Journal Entry, and Memory Candidate.

The full live swarm charter is here:

```text
docs/architecture/live-swarm-charter.md
```

The deep module rules are here:

```text
docs/architecture/deep-module-rules.md
```

The journal memory plan is here:

```text
docs/memory/journal-memory-plan.md
```

## Repo Structure

Use this structure as the repo grows:

```text
profiles/
  fabio-trading-copilot/
    SYSTEM.md
    MEMORY.md
    SCORECARD.md
    ubiquitous_language.md
    resources/
      test-prompts.md
      references.md
      review-notes.md
      backlog.md
skills/
  fabio-aaa-setup-copilot/
  fabio-premarket-sentiment/
  fabio-live-alert-watchlist/
  fabio-post-trade-journal/
docs/
  architecture/
  memory/
  playbooks/
  daily/
  weekly/
  monthly/
resources/
  screenshots/
  examples/
```

Do not commit secrets, account numbers, broker credentials, API keys, private keys, or raw financial account exports.

## Daily Workflow

### 1. Pre-Market

Before the session, add or ask Hermes to create:

```text
Instrument:
Session:
Overnight high/low:
Key levels:
Important numbers:
News/events:
Premarket sentiment:
AAA setups to watch:
Risk limit:
No-trade conditions:
```

Expected Hermes output:

- market context,
- sentiment read,
- important numbers,
- AAA setup checklist,
- alert/watch conditions,
- no-trade conditions,
- risk reminder.

### 2. During The Session

Hermes should help track:

- price near key levels,
- whether AAA confirmations are appearing,
- invalidation conditions,
- session risk,
- overtrading risk,
- emotional discipline.

The best live alerts should sound like:

```text
Price is approaching yesterday high. Watch for confirmation. No action unless AAA criteria are present.
```

Not:

```text
Buy now.
```

### 3. Post-Trade Journal

After each trade or session:

```text
Date:
Instrument:
Setup:
Entry reason:
Exit reason:
Result:
Screenshot/context:
Rule followed:
Rule broken:
Emotion:
Lesson:
What should Hermes remember:
What skill should improve:
```

Expected Hermes output:

- clean journal entry,
- setup classification,
- rule adherence review,
- mistake pattern,
- improvement suggestion,
- memory or skill update candidate.

## Weekly Workflow

Every week, review:

- best setup,
- worst setup,
- most repeated mistake,
- most useful alert,
- least useful alert,
- risk rule most often challenged,
- one skill to improve,
- one rule to tighten.

Weekly scorecard:

```text
Preparation quality:
AAA setup clarity:
Alert usefulness:
Risk discipline:
Journal quality:
Emotional control:
Decision quality:
```

## Monthly Workflow

Every month, decide:

- Which setups deserve more focus?
- Which setups should be removed?
- Which alerts are noise?
- Which levels/numbers matter most?
- Which trading mistakes are repeating?
- Which Hermes skill should be promoted to a stronger version?

Monthly output:

- rulebook update,
- setup library update,
- skill improvement backlog,
- trader improvement plan.

## How To Use This Repo With Codex

Clone:

```bash
git clone git@github.com:WEB3X100/Hermes-Ammar-Fabio-Copilot.git
cd Hermes-Ammar-Fabio-Copilot
```

Create a branch:

```bash
git switch -c codex/ammar/fabio-copilot-mvp
```

Ask Codex to work only inside this repo. Good first tasks:

```text
Create the profiles/fabio-trading-copilot folder with SYSTEM.md, MEMORY.md, SCORECARD.md, and resources/test-prompts.md.
```

```text
Create the fabio-aaa-setup-copilot skill with rules for checking AAA setups without giving blind trade calls.
```

```text
Create a daily pre-market brief template and post-trade journal template.
```

Before committing:

```bash
git status --short
git diff --stat
```

Commit and push:

```bash
git add .
git commit -m "Add Fabio copilot MVP foundation"
git push -u origin codex/ammar/fabio-copilot-mvp
```

Then open a pull request into `main`.

## What To Build First

Phase 0:

- `profiles/fabio-trading-copilot/SYSTEM.md`
- `profiles/fabio-trading-copilot/ubiquitous_language.md`
- `profiles/fabio-trading-copilot/SCORECARD.md`
- `docs/architecture/live-swarm-charter.md`
- `docs/architecture/deep-module-rules.md`
- `docs/memory/journal-memory-plan.md`
- `skills/fabio-premarket-sentiment/SKILL.md`
- `skills/fabio-aaa-setup-copilot/SKILL.md`
- `skills/fabio-live-alert-watchlist/SKILL.md`
- `skills/fabio-post-trade-journal/SKILL.md`

Phase 1:

- `profiles/fabio-trading-copilot/MEMORY.md`
- `resources/market-notes/`
- `resources/news/`
- `resources/screenshots/`
- `resources/examples/`
- first pre-market test prompt,
- first post-trade journal test prompt.

Phase 2:

- pre-market template,
- live alert template,
- post-trade journal template,
- weekly review template.

Phase 3:

- Claude Computer Use / MCP observation rules,
- chart screenshot review workflow,
- recursive memory update workflow.

Phase 4:

- Claude Mem or LightRAG sidecar plan,
- nightly journal indexing,
- relevant mistake retrieval during next pre-market brief.

## Definition Of Success

This repo is working when:

- Ammar can prep faster before market open.
- Hermes helps identify only high-quality AAA conditions.
- Alerts improve focus without forcing trades.
- Journaling becomes consistent.
- Weekly review produces better rules.
- The copilot gets smarter from reviewed trades.

The trader remains in control.
