# Review software

[ai-trading-coach](ai-trading-coach/README.md) is the preserved local Python application: Bitget historical fills → position lifecycles → discipline events → reports, with SQLite storage, a FastAPI endpoint and optional scheduled Discord delivery.

It is separate from manual ES/NQ coaching. Its configuration, dependencies and Docker build context remain inside `apps/ai-trading-coach/`. No application source was changed during consolidation. The original Chinese README and MIT license are retained.

## Working directory

From the repository root, use PowerShell:

```powershell
cd apps/ai-trading-coach
python -m venv .venv
.venv/Scripts/python.exe -m pip install -r requirements.txt
Copy-Item config.example.env .env
$env:PYTHONPATH = './src'
```

Only copy the example configuration if `.env` does not already exist. Configure private values locally using the application README. Review scheduler and delivery settings before starting any process. Nothing was installed, connected or started during consolidation.

For Docker, use this application directory as the build context. Relative rules and data paths depend on this working directory.

| Module | Responsibility |
| --- | --- |
| src/ai_trading_coach/integrations/ | Bitget historical-data clients |
| src/ai_trading_coach/pipeline/ | Fill sync and lifecycle aggregation |
| src/ai_trading_coach/domain/ | Lifecycle models |
| src/ai_trading_coach/analysis/ | Event detection |
| src/ai_trading_coach/storage/ | SQLite persistence |
| src/ai_trading_coach/reports/ | Review generation and Discord preview |
| src/ai_trading_coach/scheduler/ | Scheduled review jobs |
| src/ai_trading_coach/server.py | FastAPI entry point |

The three local NQ documents now live in [research](../docs/research/nq/README.md). They are not application configuration.
