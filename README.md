# agent-harnesses

A composable collection of `.agentharness` templates, Model Context Protocol (MCP) guardrails, and "taste" evals for safely running AI agents in production.

## Quickstart (CLI Composer)

Combine role templates and global security baselines into a single `.agentharness.yaml` policy file:

```sh
# List available templates
./bin/agentharness list

# Compose a Coding Agent with the Global Security Baseline
./bin/agentharness compose root/Coding-Agent.yaml Global/Security-Baseline.yaml > .agentharness.yaml


