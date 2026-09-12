# Complete resource index

Start with [the team guide](START-HERE.md). Every project file at consolidation is listed below; `.git` internals are excluded.

## Root

- [.gitignore](../.gitignore)
- [AGENTS.md](../AGENTS.md)
- [README.md](../README.md)

## apps

- [apps/ai-trading-coach/.cursorignore](../apps/ai-trading-coach/.cursorignore)
- [apps/ai-trading-coach/.cursorrules](../apps/ai-trading-coach/.cursorrules)
- [apps/ai-trading-coach/.devcontainer/devcontainer.json](../apps/ai-trading-coach/.devcontainer/devcontainer.json)
- [apps/ai-trading-coach/.dockerignore](../apps/ai-trading-coach/.dockerignore)
- [apps/ai-trading-coach/.gitattributes](../apps/ai-trading-coach/.gitattributes)
- [apps/ai-trading-coach/.gitignore](../apps/ai-trading-coach/.gitignore)
- [apps/ai-trading-coach/.vscode.example/settings.json](../apps/ai-trading-coach/.vscode.example/settings.json)
- [apps/ai-trading-coach/config.example.env](../apps/ai-trading-coach/config.example.env)
- [apps/ai-trading-coach/data/.gitkeep](../apps/ai-trading-coach/data/.gitkeep)
- [apps/ai-trading-coach/Dockerfile](../apps/ai-trading-coach/Dockerfile)
- [apps/ai-trading-coach/LICENSE](../apps/ai-trading-coach/LICENSE)
- [apps/ai-trading-coach/README.md](../apps/ai-trading-coach/README.md)
- [apps/ai-trading-coach/requirements.txt](../apps/ai-trading-coach/requirements.txt)
- [apps/ai-trading-coach/rules.yaml](../apps/ai-trading-coach/rules.yaml)
- [apps/ai-trading-coach/src/ai_trading_coach/__init__.py](../apps/ai-trading-coach/src/ai_trading_coach/__init__.py)
- [apps/ai-trading-coach/src/ai_trading_coach/analysis/__init__.py](../apps/ai-trading-coach/src/ai_trading_coach/analysis/__init__.py)
- [apps/ai-trading-coach/src/ai_trading_coach/analysis/events.py](../apps/ai-trading-coach/src/ai_trading_coach/analysis/events.py)
- [apps/ai-trading-coach/src/ai_trading_coach/config.py](../apps/ai-trading-coach/src/ai_trading_coach/config.py)
- [apps/ai-trading-coach/src/ai_trading_coach/discord_webhook.py](../apps/ai-trading-coach/src/ai_trading_coach/discord_webhook.py)
- [apps/ai-trading-coach/src/ai_trading_coach/domain/__init__.py](../apps/ai-trading-coach/src/ai_trading_coach/domain/__init__.py)
- [apps/ai-trading-coach/src/ai_trading_coach/domain/trade_lifecycle.py](../apps/ai-trading-coach/src/ai_trading_coach/domain/trade_lifecycle.py)
- [apps/ai-trading-coach/src/ai_trading_coach/integrations/__init__.py](../apps/ai-trading-coach/src/ai_trading_coach/integrations/__init__.py)
- [apps/ai-trading-coach/src/ai_trading_coach/integrations/bitget_readonly.py](../apps/ai-trading-coach/src/ai_trading_coach/integrations/bitget_readonly.py)
- [apps/ai-trading-coach/src/ai_trading_coach/integrations/bitget_rest.py](../apps/ai-trading-coach/src/ai_trading_coach/integrations/bitget_rest.py)
- [apps/ai-trading-coach/src/ai_trading_coach/llm_client.py](../apps/ai-trading-coach/src/ai_trading_coach/llm_client.py)
- [apps/ai-trading-coach/src/ai_trading_coach/pipeline/__init__.py](../apps/ai-trading-coach/src/ai_trading_coach/pipeline/__init__.py)
- [apps/ai-trading-coach/src/ai_trading_coach/pipeline/aggregate_lifecycles.py](../apps/ai-trading-coach/src/ai_trading_coach/pipeline/aggregate_lifecycles.py)
- [apps/ai-trading-coach/src/ai_trading_coach/pipeline/sync_bitget.py](../apps/ai-trading-coach/src/ai_trading_coach/pipeline/sync_bitget.py)
- [apps/ai-trading-coach/src/ai_trading_coach/reports/discord_preview.py](../apps/ai-trading-coach/src/ai_trading_coach/reports/discord_preview.py)
- [apps/ai-trading-coach/src/ai_trading_coach/reports/generator.py](../apps/ai-trading-coach/src/ai_trading_coach/reports/generator.py)
- [apps/ai-trading-coach/src/ai_trading_coach/scheduler/run_reviews.py](../apps/ai-trading-coach/src/ai_trading_coach/scheduler/run_reviews.py)
- [apps/ai-trading-coach/src/ai_trading_coach/scheduler/scheduler_app.py](../apps/ai-trading-coach/src/ai_trading_coach/scheduler/scheduler_app.py)
- [apps/ai-trading-coach/src/ai_trading_coach/server.py](../apps/ai-trading-coach/src/ai_trading_coach/server.py)
- [apps/ai-trading-coach/src/ai_trading_coach/storage/__init__.py](../apps/ai-trading-coach/src/ai_trading_coach/storage/__init__.py)
- [apps/ai-trading-coach/src/ai_trading_coach/storage/sqlite_store.py](../apps/ai-trading-coach/src/ai_trading_coach/storage/sqlite_store.py)
- [apps/README.md](../apps/README.md)

## docs

- [docs/architecture/deep-module-rules.md](../docs/architecture/deep-module-rules.md)
- [docs/architecture/live-swarm-charter.md](../docs/architecture/live-swarm-charter.md)
- [docs/archive/original-repository-readme.md](../docs/archive/original-repository-readme.md)
- [docs/inventory/CONSOLIDATION.md](../docs/inventory/CONSOLIDATION.md)
- [docs/inventory/source-manifest.json](../docs/inventory/source-manifest.json)
- [docs/memory/journal-memory-plan.md](../docs/memory/journal-memory-plan.md)
- [docs/playbooks/trading-coach-os/00-start-here.md](../docs/playbooks/trading-coach-os/00-start-here.md)
- [docs/playbooks/trading-coach-os/01-pre-market-analysis.md](../docs/playbooks/trading-coach-os/01-pre-market-analysis.md)
- [docs/playbooks/trading-coach-os/02-strategy-library.md](../docs/playbooks/trading-coach-os/02-strategy-library.md)
- [docs/playbooks/trading-coach-os/03-in-session-workflow.md](../docs/playbooks/trading-coach-os/03-in-session-workflow.md)
- [docs/playbooks/trading-coach-os/04-trade-journal-template.md](../docs/playbooks/trading-coach-os/04-trade-journal-template.md)
- [docs/playbooks/trading-coach-os/05-same-day-review.md](../docs/playbooks/trading-coach-os/05-same-day-review.md)
- [docs/playbooks/trading-coach-os/06-weekly-review-audit.md](../docs/playbooks/trading-coach-os/06-weekly-review-audit.md)
- [docs/playbooks/trading-coach-os/07-overnight-os-audit.md](../docs/playbooks/trading-coach-os/07-overnight-os-audit.md)
- [docs/playbooks/trading-coach-os/08-personal-rulebook.md](../docs/playbooks/trading-coach-os/08-personal-rulebook.md)
- [docs/playbooks/trading-coach-os/09-backtest-forward-test-protocol.md](../docs/playbooks/trading-coach-os/09-backtest-forward-test-protocol.md)
- [docs/playbooks/trading-coach-os/10-profitable-trader-insights-upgrade-roadmap.md](../docs/playbooks/trading-coach-os/10-profitable-trader-insights-upgrade-roadmap.md)
- [docs/playbooks/trading-coach-os/11-fabio-carmine-order-flow-battle-test.md](../docs/playbooks/trading-coach-os/11-fabio-carmine-order-flow-battle-test.md)
- [docs/playbooks/trading-coach-os/12-hermes-market-data-and-grok-bridge.md](../docs/playbooks/trading-coach-os/12-hermes-market-data-and-grok-bridge.md)
- [docs/playbooks/trading-coach-os/13-team-training-and-fabio-skill-loop.md](../docs/playbooks/trading-coach-os/13-team-training-and-fabio-skill-loop.md)
- [docs/playbooks/trading-coach-os/AGENTS.md](../docs/playbooks/trading-coach-os/AGENTS.md)
- [docs/research/nq/01-order-flow-battle-test.md](../docs/research/nq/01-order-flow-battle-test.md)
- [docs/research/nq/02-volume-profile-framing.md](../docs/research/nq/02-volume-profile-framing.md)
- [docs/research/nq/03-scenario-building.md](../docs/research/nq/03-scenario-building.md)
- [docs/research/nq/README.md](../docs/research/nq/README.md)
- [docs/START-HERE.md](../docs/START-HERE.md)
- [docs/STATUS.md](../docs/STATUS.md)

## profiles

- [profiles/fabio-trading-copilot/resources/test-prompts.md](../profiles/fabio-trading-copilot/resources/test-prompts.md)
- [profiles/fabio-trading-copilot/SCORECARD.md](../profiles/fabio-trading-copilot/SCORECARD.md)
- [profiles/fabio-trading-copilot/SYSTEM.md](../profiles/fabio-trading-copilot/SYSTEM.md)
- [profiles/fabio-trading-copilot/ubiquitous_language.md](../profiles/fabio-trading-copilot/ubiquitous_language.md)

## resources

- [resources/README.md](../resources/README.md)

## skills

- [skills/fabio-aaa-setup-copilot/README.md](../skills/fabio-aaa-setup-copilot/README.md)
- [skills/fabio-aaa-setup-copilot/SKILL.md](../skills/fabio-aaa-setup-copilot/SKILL.md)
- [skills/fabio-live-alert-watchlist/README.md](../skills/fabio-live-alert-watchlist/README.md)
- [skills/fabio-live-alert-watchlist/SKILL.md](../skills/fabio-live-alert-watchlist/SKILL.md)
- [skills/fabio-post-trade-journal/README.md](../skills/fabio-post-trade-journal/README.md)
- [skills/fabio-post-trade-journal/SKILL.md](../skills/fabio-post-trade-journal/SKILL.md)
- [skills/fabio-premarket-sentiment/README.md](../skills/fabio-premarket-sentiment/README.md)
- [skills/fabio-premarket-sentiment/SKILL.md](../skills/fabio-premarket-sentiment/SKILL.md)
- [skills/fabio-screenshot-pattern-gate/agents/openai.yaml](../skills/fabio-screenshot-pattern-gate/agents/openai.yaml)
- [skills/fabio-screenshot-pattern-gate/references/check-order.md](../skills/fabio-screenshot-pattern-gate/references/check-order.md)
- [skills/fabio-screenshot-pattern-gate/references/training-intake.md](../skills/fabio-screenshot-pattern-gate/references/training-intake.md)
- [skills/fabio-screenshot-pattern-gate/SKILL.md](../skills/fabio-screenshot-pattern-gate/SKILL.md)
- [skills/fabio-weighted-story-builder/agents/openai.yaml](../skills/fabio-weighted-story-builder/agents/openai.yaml)
- [skills/fabio-weighted-story-builder/references/evidence-weights.md](../skills/fabio-weighted-story-builder/references/evidence-weights.md)
- [skills/fabio-weighted-story-builder/references/story-patterns.md](../skills/fabio-weighted-story-builder/references/story-patterns.md)
- [skills/fabio-weighted-story-builder/SKILL.md](../skills/fabio-weighted-story-builder/SKILL.md)
- [skills/README.md](../skills/README.md)
