# Project

## Project
- sepo-agent/sepo-agent: self-hosting repo for the Sepo agent; auth via oidc_broker + CLAUDE_CODE_OAUTH_TOKEN; rubrics branch not yet initialized
- Agent infra at v0.2.0; PR #3 (open 2026-06-01) upgrades to v0.3.0 — new optional vars: AGENT_ENABLED (pause all workflows), AGENT_MODEL_POLICY (model/effort override), ANTHROPIC_API_KEY (alt to OAuth token)
- Post-merge items for PR #3: add AGENT_ENABLED mention to README.md line ~71; remove orphaned .github/actions/resolve-agent-provider/resolve-provider.sh
