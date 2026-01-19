# AI Baseline Context

Baseline guardrails, workflows, and product context extracted from the Homedir project to standardize AI-augmented development (ADev) work. Use this repo as a starting kit for new agents or projects that need clear constraints, alignment, and reference materials.

## ADev philosophy (simplicity first)
- Inspired by ADev: https://github.com/scanalesespinoza/adev
- Goal: reduce friction, not add ceremony. The baseline is a minimal, official source of truth that keeps agents aligned without over-specifying their work.
- Telling an agent to “work under this baseline” sets default principles and behaviors, creating a feedback loop during execution so development stays on track and improves over time.
- Keep the baseline small, composable, and easy to swap to another domain.

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

## Why it helps
- One instruction (“use this baseline”) sets expected agent behavior and guardrails.
- Reduces onboarding time and cognitive load; work stays consistent across agents and repos.
- Provides built-in feedback loops: workflows + guardrails make gaps obvious and easier to improve over time.

## Provenance
- Source materials pulled from os-santiago/homedir (agent context, guardrails, workflows, and supporting docs).
- Secrets were excluded; keep this repo public-safe.
