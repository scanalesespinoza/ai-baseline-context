# How to Use This Baseline

Quick guide to apply the context across projects.

## Navigation
- Guardrails: `guardrails/` → constraints, sandbox notes, performance tips.
- Workflows: `workflows/` → pick the playbook that matches your task.
- Prompts: `prompts/` → ready-to-use prompt dashboard (EN/ES).
- Glossary: `glossary/` → shared ADev terminology.
- Knowledge: `knowledge/` → domain seed docs (replace with your project).
- Templates: `templates/` → scaffolds to add new guardrails, workflows, prompts, or knowledge.

## Typical Flows
- Bugfix/Hotfix: read `guardrails/agent-notes.md`, follow `workflows/production_fix_cycle.md`, reference domain in `knowledge/`.
- Release: `workflows/full_release_cycle.md`, then `workflows/production_verification.md` for final checks.
- Production verification only: `workflows/production_verification.md`.
- Repository health: `workflows/repository_health_check.md`.
- Community/onboarding: `workflows/verify_community_join.md`.
- New domain adoption: copy `templates/` files, replace `knowledge/` with your docs, update `README.md` and `CHANGELOG.md`.

## Hygiene (before sharing)
Run `PUBLISH_CHECKLIST.md` to confirm no secrets, correct versions, and clean links.
