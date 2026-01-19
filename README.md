# AI Baseline Context

Baseline guardrails, workflows, and product context extracted from the Homedir project to standardize AI-augmented development (ADev) work. Use this repo as a starting kit for new agents or projects that need clear constraints, alignment, and reference materials.

## What’s inside
- guardrails/: Agent notes and Codex optimization guidance (sandbox constraints, testing limits, recommended commands).
- workflows/: Step-by-step playbooks for fixes, releases, production verification, repo health, and community onboarding.
- prompts/: Prompt dashboard MVP content (EN/ES) for metrics-oriented interactions.
- glossary/: ADev terminology in English and Spanish.
- knowledge/: Seed domain docs (Homedir); swap for your project when reusing.
- templates/: Scaffolds to add new guardrails, workflows, prompts, or knowledge.
- USAGE.md: Quick navigation and typical flows.
- PUBLISH_CHECKLIST.md: Hygiene before sharing.
- CHANGELOG.md: Version trail.

## How to use
1) Read guardrails/agent-notes.md before running commands; respect sandbox/test limitations and deployment expectations.
2) Pick the relevant workflows/ playbook for your task (bugfix, release, verification, health check, onboarding).
3) Leverage prompts/ and glossary/ to keep language and goals consistent across agents.
4) Reuse or adapt knowledge/ as seed context when bootstrapping similar platforms; replace with your domain docs as needed.
5) Follow USAGE.md for quick flow mapping and PUBLISH_CHECKLIST.md before distributing.

## Provenance
- Source materials pulled from os-santiago/homedir (agent context, guardrails, workflows, and supporting docs).
- Secrets were excluded; keep this repo public-safe.
