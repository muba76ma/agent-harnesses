# agent-harnesses

A collection of `.agentharness` and MCP guardrail templates for safely deploying AI agents in production.

## Folder structure

* **root/** contains core templates for common agent roles (e.g., Coding, Customer Support) to help you get started quickly.
* **Global/** contains universal security, PII-redaction, and audit policies that can be applied across any agent deployment.
* **community/** contains specialized vertical harnesses (e.g., Legacy SaaS Data Cleaning, RevOps, Legal) tailored to specific industry workflows and evals.
* **evals/** contains regression and "taste" test suites to verify agent behavior before deployment.
