# Hermes · Ammar · Fabio Copilot

One home for our trading-coach playbooks, agent skills, NQ study material, and review software. The human executes all trades.

**Start with [the team guide](docs/START-HERE.md).** Use [the complete resource index](docs/RESOURCE-INDEX.md) to find any file.

| Place | What belongs here |
| --- | --- |
| [profiles/](profiles/fabio-trading-copilot/SYSTEM.md) | Copilot identity, shared language, scorecard |
| [skills/](skills/README.md) | Six reusable coaching skills |
| [docs/playbooks/](docs/playbooks/trading-coach-os/00-start-here.md) | Daily workflow, rulebook, journal and review templates |
| [docs/research/nq/](docs/research/nq/README.md) | NQ auction, volume-profile and scenario study guides |
| [docs/architecture/](docs/architecture/live-swarm-charter.md) | Role design and context management |
| [docs/memory/](docs/memory/journal-memory-plan.md) | Reviewed-learning process |
| [apps/](apps/README.md) | Separate Bitget historical-review Python app |
| [resources/](resources/README.md) | Sanitized training examples and source notes |
| [docs/inventory/](docs/inventory/CONSOLIDATION.md) | Sources, preservation manifest and alignment decisions |

The ES/NQ coaching workflow uses manually supplied evidence. The Bitget app is a separate implementation for historical crypto trade reviews; it is not wired into Hermes. Swarm roles, data bridges, and memory sidecars describe designs, not verified running services.

Real trading logs and screenshots belong outside Git at `~/TradingCoachLogs/YYYY-MM-DD/`. Keep secrets and private account data out of this repository.

For maintainers: read [AGENTS.md](AGENTS.md), then [status and next work](docs/STATUS.md). Update the existing authoritative file and its index rather than creating another competing copy.
