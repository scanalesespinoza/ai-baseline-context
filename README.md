# AI Baseline Context

Baseline guardrails, workflows, and product context extracted from the Homedir project to standardize AI-augmented development (ADev) work. Use this repo as a starting kit for new agents or projects that need clear constraints, alignment, and reference materials.

## What’s inside
- guardrails/: Agent notes and Codex optimization guidance (sandbox constraints, testing limits, recommended commands).
- workflows/: Step-by-step playbooks for fixes, releases, production verification, repo health, and community onboarding.
- prompts/: Prompt dashboard MVP content (EN/ES) for metrics-oriented interactions.
- glossary/: ADev terminology in English and Spanish.
- knowledge/homedir/: Homedir product overview plus architecture and persistence references used as the source context.

## How to use
1) Read guardrails/agent-notes.md before running commands; respect sandbox/test limitations and deployment expectations.
2) Pick the relevant workflows/ playbook for your task (bugfix, release, verification, health check, onboarding).
3) Leverage prompts/ and glossary/ to keep language and goals consistent across agents.
4) Reuse or adapt knowledge/homedir/ as seed context when bootstrapping similar platforms; replace with your domain docs as needed.

## Provenance
- Source materials pulled from os-santiago/homedir (agent context, guardrails, workflows, and supporting docs).
- Secrets were excluded; keep this repo public-safe.
